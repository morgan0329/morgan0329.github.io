# git知识点滴


## 关于github SSL报错

如果git提交或克隆时类似报错：OpenSSL SSL_read: SSL_ERROR_SYSCALL, errno 10054； Failed to connect to github.com port 44

就尝试这么解决：  

```bash
git config --global http.sslVerify false
```

