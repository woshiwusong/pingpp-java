ping++ java SDK
============

###简介
 1. docs 目录下为ping++ Java sdk 的使用文档。
 1. example 目录下面为一个eclipse IDE 的示例工程。
 1. libs 为ping++ Java sdk 的jar包和ping++ Java sdk 所依赖的Gson 包。
 1. src  为ping++ Java sdk 的源代码，可以关联到ping-java.jar文件。 或者直接把源代码引入到工程之中。


###版本要求

Java SDK 要求JDK版本1.6及以上
  
###安装

将libs/下面的jar包导入工程

###初始化

    Pingpp.apiKey = "YOUR-KEY"; 
    
####使用示例
    
    参考example/SimpleExample 示例项目工程。改工程提供了付款、退款、微信公共号付款相关的demo。
    
    
####2.0.4版本

    更改sdk目录格式，修复wx_pub渠道timeStamp 类型问题。



