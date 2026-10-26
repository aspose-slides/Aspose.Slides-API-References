---
title: formula property
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.animation/ipoint/formula/
weight: 10
---
## 公式屬性
Formulas within values, from, to, by attributes can be made up of these:
            Standard arithmetic operators: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Constants: ‘pi’ ‘e’
            Conditional operators: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            Comparison operators: '==', '>=', '', '!=', '!'
            Trigonometric operators: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            Natural logarithm ‘ln()’
            Property references (host supported properties)
            
            for example: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
            Read/write **str**.

### 定義:
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```


### 另見
* 類別 [`IPoint`](/slides/python-net/zh-hant/aspose.slides.animation/ipoint)
* 模組 [`aspose.slides.animation`](/slides/python-net/zh-hant/aspose.slides.animation)
* 函式庫 [`Aspose.Slides`](/slides/python-net)