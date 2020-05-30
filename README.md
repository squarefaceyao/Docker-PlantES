# 1. 启动docker
```
docker-compose up
```
# 2. 在hbase容器里面建立两个表

- 进入hbase容器
```
docker exec -it hbase容器ID bash
```
- 进入hbase shell
```
hbase shell
```
- 分别输入下面两行指令，建立两张表

```bash
create 'h_file', 'h_info', 'h_content'
create 'analysis_result', 'image'
```
## (docker常用命令)[https://colobu.com/2018/05/15/Stop-and-remove-all-docker-containers-and-images/]
