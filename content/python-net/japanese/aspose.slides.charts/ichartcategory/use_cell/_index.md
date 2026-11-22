---
title: use_cell property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartcategory/use_cell/
weight: 60
---
## use_cell プロパティ
If true then AsCell property is actual. In other words, worksheet is used for 
            storing category (this case supports a multi-level category).
            If false then AsLiteral property is actual. In other words, worksheet is NOT used 
            for storing category (and this case doesn't support a multi-level categories).
            Read-only **bool**.


### 備考

For change value of this property (for all categories in collection) set new 
            value to ChartCategoryCollection.UseCells property.

### 定義:
```python
@property
def use_cell(self):
    ...
```


### 関連項目
* クラス [`IChartCategory`](/slides/python-net/ja/aspose.slides.charts/ichartcategory)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)