---
title: formula property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.animation/point/formula/
weight: 20
---
## 数式 プロパティ
Formulas within values, from, to, by attributes can be made up of these:
            標準算術演算子: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            定数: ‘pi’ ‘e’
            条件演算子: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            比較演算子: '==', '>=', '', '!=', '!'
            三角演算子: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            自然対数 ‘ln()’
            プロパティ参照 (host supported properties)
            
            例: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
            読み書き **str**.

### 定義:
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```


### 参照
* クラス [`Point`](/slides/python-net/ja/aspose.slides.animation/point)
* モジュール [`aspose.slides.animation`](/slides/python-net/ja/aspose.slides.animation)
* ライブラリ [`Aspose.Slides`](/slides/python-net)