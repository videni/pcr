# 介绍

2017年最新全国省市区数据库。包含名称、城市代码、上级代码、级别、邮编。 

在应用程序中，省市区级联选择是比较常用的功能，在多数情况下，需要集成到自己的系统中，而不是调用一些地图提供方的API。 我创建这个库有以下目的：

1. 一个中心的库，对数据提供持续更新。
2. 让开发能够便捷的将地址选择功能集成到自己的系统中。

# 为什么命名为pcr？

只是为了简单，pcr代表`P`rovice， `C`ity， `R`egion。

# 贡献

为了让数据尽量准确，任何时候，如果你发现数据有遗漏，请让我知道，我会更新其为最新状态。

# 下一步

1. PHP脚本将其转换为SQL表结构。

采用不同的算法。 

* 邻接模型 
* 嵌套集模型
* 省市区每个单独表模型。 

2. 一个的PHP库，封装实现省市区级联操作功能。

3. 与Symfony集成。 

4. 一个专门的网站，提供一下支持。

* 让大家可维护数据
* 也可以XSL，JSON，CSV格式下载。
* 提供三种模型的SQL结构化数据


# 更改日志

参见[CHANGELOG](./CHANGELOG.MD)

# 版权

你可将本数据用于任何用途，无需经过我的授权。 