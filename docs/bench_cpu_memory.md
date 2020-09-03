###   并发测试     
> 2核8G阿里云服务器, 并发（Qps）可以达到1w+，所有请求100%成功！  
![压力测试图](http://139.196.101.31:2080/concurrent.png)  

> 4核8G阿里云服务器, 并发（Qps）可以达到1.6w+，所有请求100%成功！  
![压力测试图](http://139.196.101.31:2080/images/bench_test2.png)  

##  性能分析报告  
> 1.开发之初，我们的目标就是追求极致的高性能,因此在项目整体功能越来越趋于完善之时，我们现将进行一次全面的性能分析评测.    
> 2.通过执行相关代码, 跟踪 cpu 耗时 和 内存占用 来分析各个部分的性能,CPU耗时越短性、内存占用越低能越优秀,反之就比较垃圾.        

###  通过CPU的耗时来分析相关代码段的性能  
序号|分析对象 | 文档地址  
---|---|---
1| 项目骨架主线逻辑| [主线分析报告](./project_analysis_1.md)
2| 操作数据库代码段| [操作数据库代码段分析报告](./project_analysis_2.md)

###  通过内存占用来分析相关代码段的性能 
序号|分析对象 | 文档地址  
---|---|---
1| 操作数据库代码段| [操作数据库代码段](./project_analysis_3.md) 