# silk2wav
convert silk format to wav format
该项目结合skpye官方提供的silk_sdk的API，将silk编码的音频文件转换为wav(Microsoft开发的一种声音文件格式)，提供了windows平台下vs编译的
可执行程序和转换部分的全部源码，写的拙劣请见谅！！！



/code/silk2wav使用的方法：
在官方提供的SILK_SDK_SRC_ARM_v1.0.9的解决方案中添加一个项目，然后在将/code/silk2wav下的文件添加到新增的项目，添加完成后需对项目属性进
行配置，在通用属性-->引用中添加Silk_FIX即可成功编译。
