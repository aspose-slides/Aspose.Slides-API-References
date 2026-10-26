---
title: formula property
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.animation/point/formula/
weight: 20
---
## 公式屬性
在值、from、to、by 屬性中的公式可以由以下組成：
            標準算術運算子: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            常數: ‘pi’ ‘e’
            條件運算子: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            比較運算子: '==', '>=', '', '!=', '!'
            三角運算子: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            自然對數 ‘ln()’
            屬性參照（主機支援的屬性）
            
            例如: "#ppt_x+(cos(-2-pi*(1-$))*-#ppt_x-sin(-2-pi*(1-$))*(1-#ppt_y))*(1-$)"
            讀/寫 **str**。

### 定義：
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```

### 另見
* 類別 [`Point`](/slides/python-net/zh-hant/aspose.slides.animation/point)
* 模組 [`aspose.slides.animation`](/slides/python-net/zh-hant/aspose.slides.animation)
* 函式庫 [`Aspose.Slides`](/slides/python-net)