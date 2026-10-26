---
title: formula property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.animation/ipoint/formula/
weight: 10
---
## 公式属性
公式可以在 values、from、to、by 属性中使用，由以下内容组成：
            标准算术运算符: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            常量: ‘pi’ ‘e’
            条件运算符: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            比较运算符: '==', '>=', '', '!=', '!'
            三角运算符: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            自然对数 ‘ln()’
            属性引用（host 支持的属性）
            
            例如: "#ppt_x+(cos(-2-pi*(1-$))*-#ppt_x-sin(-2-pi*(1-$))*(1-#ppt_y))*(1-$)"
            读取/写入 **str**。

### 定义：
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```

### 另见
* 类 [`IPoint`](/slides/python-net/zh/aspose.slides.animation/ipoint)
* 模块 [`aspose.slides.animation`](/slides/python-net/zh/aspose.slides.animation)
* 库 [`Aspose.Slides`](/slides/python-net)