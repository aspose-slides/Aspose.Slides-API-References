---
title: IPoint class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.animation/ipoint/
---
## IPoint 类

表示动画点。

IPoint 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`time`](/slides/python-net/zh/aspose.slides.animation/ipoint/time/) | 表示时间值。<br/>            读/写 **float**. |
| [`value`](/slides/python-net/zh/aspose.slides.animation/ipoint/value/) | 表示点值。<br/>            仅: bool, ColorFormat, float, int, string.<br/>            读/写 **any**. |
| [`formula`](/slides/python-net/zh/aspose.slides.animation/ipoint/formula/) | 值、from、to、by 属性中的公式可以由以下组成：<br/>            标准算术运算符：‘+’，‘-‘，‘*’，‘/’，‘^’，‘%’ (mod)<br/>            常数：‘pi’ ‘e’<br/>            条件运算符：‘abs’，‘min’，‘max’，‘?’ (if)<br/>            比较运算符： '==', '>=', '', '!=', '!'<br/>            三角函数运算符：‘sin()’，‘cos()’，‘tan()’，‘asin()’，‘acos()’，‘atan()’<br/>            自然对数 ‘ln()’<br/>            属性引用（主机支持的属性）<br/>            <br/>            例如: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            读/写 **str**. |


### 另请参见
* 模块 [`aspose.slides.animation`](/slides/python-net/zh/aspose.slides.animation)
* 库 [`Aspose.Slides`](/slides/python-net)