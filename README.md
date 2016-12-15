# https-
苹果审核即将使用https加密协议

HTTPS协议是由SSL+HTTP协议构建的可进行加密传输、身份认证的网络协议、其实在http的基础上加了个验证

1、# 生成一个RSA密钥 
$ openssl genrsa -des3 -out server.key 1024  用des3加密方式生成1024位rsa密钥
