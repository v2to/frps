# frps

# frps.ini place in ./conf/frps.ini
docker run -d --name frp-server -v ./conf:/conf --restart=always tozehu/frps-docker
