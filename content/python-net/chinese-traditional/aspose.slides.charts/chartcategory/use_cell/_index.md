---
title: use_cell property
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartcategory/use_cell/
weight: 50
---
## use_cell 屬性
如果為 true，則 AsCell property 為實際使用。換句話說，worksheet 用於儲存 category（此情況支援多層 category）。  
如果為 false，則 AsLiteral property 為實際使用。換句話說，worksheet 未用於儲存 category（且此情況不支援多層 categories）。  
唯讀 **bool**。


### 備註

若要變更此屬性的值（針對集合中的所有 categories），請將新值設定至 ChartCategoryCollection.UseCells property。

### 定義：
```python
@property
def use_cell(self):
    ...
```


### 參見
* 類別 [`ChartCategory`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategory)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)