---
title: Point class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.animation/point/
---
## Point 类

表示动画点。

Point 类型公开以下成员：

## 构造函数

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides.animation/point/__init__/#) | 默认构造函数。 |
| [`__init__(self, time, value, formula)`](/slides/python-net/zh/aspose.slides.animation/point/__init__/#float-any-str) | 使用时间、数值和公式创建动画点。 |

## 属性

| Property | Description |
| :- | :- |
| [`time`](/slides/python-net/zh/aspose.slides.animation/point/time/) | 表示时间值。<br/>            可读写 **float**。 |
| [`value`](/slides/python-net/zh/aspose.slides.animation/point/value/) | 表示点的值。<br/>            仅限：bool, ColorFormat, float, int, string。<br/>            可读写 **any**。 |
| [`formula`](/slides/python-net/zh/aspose.slides.animation/point/formula/) | 值、from、to、by 属性中的公式可以由以下元素组成：<br/>            标准算术运算符：‘+’，‘-‘，‘*’，‘/’，‘^’，‘%’（mod）<br/>            常量：‘pi’ ‘e’<br/>            条件运算符：‘abs’，‘min’，‘max’，‘?’（if）<br/>            比较运算符：'==', '>=', '', '!=', '!'<br/>            三角运算符：‘sin()’，‘cos()’，‘tan()’，‘asin()’，‘acos()’，‘atan()’<br/>            自然对数 ‘ln()’<br/>            属性引用（主机支持的属性）<br/>            <br/>            例如：“#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)”<br/>            可读写 **str**。 |

### 另见
* 模块 [`aspose.slides.animation`](/slides/python-net/zh/aspose.slides.animation)
* 库 [`Aspose.Slides`](/slides/python-net)