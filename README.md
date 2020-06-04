V2备份
~~~
// ws 示例
xxxxx.com;10550;64;ws;;path=/v2ray|host=oxxxx.com

// ws + tls 
xxxxx.com;0;64;tls;ws;path=/v2ray|host=oxxxx.com|inside_port=10550|outside_port=443
xxxxx.com;;64;tls;ws;path=/v2ray|host=oxxxx.com|inside_port=10550|outside_port=443
~~~

### [可选] 增加swap
~~~
wget https://www.moerats.com/usr/shell/swap.sh && bash swap.sh
~~~

### [推荐] 脚本部署

#### Docker-compose 安装 
~~~
mkdir v2ray-agent  &&  \
cd v2ray-agent && \
curl https://raw.githubusercontent.com/haig233/v2ray-sspanel-v3-mod_Uim-plugin/master/install.sh -o install.sh && \
chmod +x install.sh && \
bash install.sh
~~~
