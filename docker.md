# docker
    docker images   查看所有已下载的镜像
    docker rm 镜像名(id) 删除镜像实例
    docker rmi 镜像名(id) 从docker 删除镜像

    docker pull 镜像:版本 下载镜像
    docker ps 查看运行镜像实例
    docker run 创建镜像实例
    
    docker update 镜像实例名(id) --restart=always 开机启动
    docker logs 镜像名(id) 查看
    docker exec -it 名 进入实例镜像内部