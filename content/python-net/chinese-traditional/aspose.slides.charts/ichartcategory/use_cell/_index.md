---
title: use_cell property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartcategory/use_cell/
weight: 60
---
## use_cell 屬性
If true then AsCell property is actual. In other words, worksheet is used for 
            storing category (this case supports a multi-level category).
            If false then AsLiteral property is actual. In other words, worksheet is NOT used 
            for storing category (and this case doesn't support a multi-level categories).
            Read-only **bool**.

### 備註

For change value of this property (for all categories in collection) set new 
            value to ChartCategoryCollection.UseCells property.

### 定義:
```python
@property
def use_cell(self):
    ...
```

### 另請參閱
* 類別 [`IChartCategory`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategory)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)