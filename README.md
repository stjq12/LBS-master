### 目录
> - output文件夹是输出的解密照片 
>- pic中original是原图，QR是需要往原图打进去的隐藏水印。
>- LSBcode.py是加密操作
>- decodeLSB.py是解密操作
### 步骤
用LSBcode是利用LSB（最低有效位算法）加密图片，然后用decodeLSP去解密图片。
origin_str.py是基于傅立叶变换得到的加密 字符串的算法