### A docker Image with a pre-installed `aria2` for alist
[基本教程](【进阶版render AList白嫖方法，免费无服务器搭建AList】 https://b23.tv/jmNNNjD)
#### Usage

```bash
docker run -d --restart=always -v /etc/alist:/opt/alist/data -p 5244:5244 -e PUID=0 -e PGID=0 -e UMASK=022 --name="alist" xhofe/alist-aria2:latest
```
