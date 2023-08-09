# Awd-Backups
CTF AWD自动化备份工具使用教程

```
root@root: $ ./Awd-Backups_darwin_amd64 -h
Usage of ./Awd-Backups_darwin_amd64:
  -b	默认开启在远程主机tmp下执行cp备份 (default true)
  -f string
    	默认远程文件路径为'/var/www'
  -i string
    	主机地址，例如：127.0.0.0:22
  -p string
    	密码
  -u string
    	用户名
```

已完成文件备份自动化功能，自动识别/var/www以及其链接目录，并自动下载至本地和解压到/tmp目录
