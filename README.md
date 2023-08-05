# DBlook3

数据库操作工具，可以在web上运行，可以在pc上运行

http://localhost:8001/dblook

## For Development

### branch 说明

|          |                            |
|----------|----------------------------|
| release: | 正式发布, 用于GitHub Action 自动构建 | 
| main:    | 开发                         |

### how to build

```bash
mvn clean package -Dmaven.test.skip=true -T4
```

### local test

```bash
pc端运行: java -jar dblook3.jar
web运行:  dblook.war 部署 
```
