---
title: formula property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.animation/point/formula/
weight: 20
---
## 公式属性
Formulas within values, from, to, by attributes can be made up of these:
            Standard arithmetic operators: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Constants: ‘pi’ ‘e’
            Conditional operators: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            Comparison operators: '==', '>=', '', '!=', '!'
            Trigonometric operators: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            Natural logarithm ‘ln()’
            Property references（主机支持的属性）
            
            for example: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
            Read/write **str**.

### 定义:
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```


### 另请参见
* 类 [`Point`](/slides/python-net/zh/aspose.slides.animation/point)
* 模块 [`aspose.slides.animation`](/slides/python-net/zh/aspose.slides.animation)
* 库 [`Aspose.Slides`](/slides/python-net)