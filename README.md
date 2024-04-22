# C-work
This project is created to finish my C# homework in 2024. \
Hope that I can get a high mark in this crouse!!!  \
Bless on me.  \

*****************************************************************  
#assignment1  
##1、编写一个实现计算器的控制台程序，接受两个数字和一个运算符作为输入，并打印\出计算结果。  
##2、编写一个实现计算器的Windows窗体应用程序：在两个文本框内输入数字，选择运算\符，点击“计算”按钮，然后显示结果  
\
#assignment2  
##1、编写程序输出用户指定数据的所有素数因子。    
##2、编程求一个整数数组的最大值、最小值、平均值和所有数组元素的和。    
##3、用“埃氏筛法”求2~ 100以内的素数。2~ 100以内的数，先去掉2的倍数，再去掉3的倍数，再去掉4的倍数，以此类推...最后剩下的就是素数。    
##4、如果矩阵上每一条由左上到右下的对角线上的元素都相同，那么这个矩阵是托普茨矩阵 。给定一个 M x N 的矩阵，当且仅当它是托普利茨矩阵时返回 True。  
\
#assignment3  
##1、编写面向对象程序实现长方形、正方形、三角形等形状的类。每个形状类都能计算面积、判断形状是否合法。 请尝试合理使用接口/抽象类、属性来实现。  
##2、随机创建10个形状对象，计算这些对象的面积之和。 尝试使用简单工厂设计模式来创建对象。  (我将两个要求通过循环的方式一起完成。)

#assignment4  
##1、为示例中的泛型链表类添加类似于List<T>类的ForEach(Action<T> action)方法。通过调用这个方法打印链表元素，求最大值、最小值和求和（使用lambda表达式实现）。  
##2、使用事件机制，模拟实现一个闹钟功能。闹钟可以有嘀嗒（Tick）事件和响铃（Alarm）两个事件。在闹钟走时时或者响铃时，在控制台显示提示信息。  

#assignment5  
写一个订单管理的控制台程序，能够实现添加订单、删除订单、修改订单、查询订单（按照订单号、商品名称、客户、订单金额等进行查询）功能。并对各个Public方法编写测试用例。\  
提示：主要的类有Order（订单）、OrderDetails（订单明细），OrderService（订单服务），订单数据可以保存在OrderService中一个List中。在Program里面可以调用OrderService的方法完成各种订单操作。  \

要求：\
（1）使用LINQ语言实现各种查询功能，查询结果按照订单总金额排序返回。\
（2）在订单删除、修改失败时，能够产生异常并显示给客户错误信息。\
（3）作业的订单和订单明细类需要重写Equals方法，确保添加的订单不重复，每个订单的订单明细不重复。\
（4）订单、订单明细、客户、货物等类添加ToString方法，用来显示订单信息。\
（5） OrderService提供排序方法对保存的订单进行排序。默认按照订单号排序，也可以使用Lambda表达式进行自定义排序。\

#assignment6
为订单管理的程序添加一个WinForm的界面。通过这个界面，调用OrderService的各个方法，实现创建订单、删除订单、修改订单、查询订单等功能。\
要求：\
（1）WinForm的界面部分单独写一个项目，依赖于原来的项目。\
（2）可以使用两个窗口。主窗口实现查询展示功能，以及放置各种功能按钮。新建/修改订单功能使用弹出窗口。\
（3）注意窗口的布局，在窗口尺寸变化时，不出现错位挤压等情况。\
（4）尽量通过数据绑定来实现功能。订单和订单明细各使用一个bindingsource，通过DataMember来实现主从对象绑定。\

#assignment8
修改之前做的订单程序，基于EF框架，将订单保存到MySql数据库中，并实现订单的增删改查功能。(我将直接在在assignment6的窗体程序上进行修改)\
