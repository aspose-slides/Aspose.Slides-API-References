---
title: show_label_value_from_cell property
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/datalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell 屬性
表示特定圖表的資料標籤儲存格數值顯示行為。  
True 會顯示儲存格數值。 False 會隱藏。  
可讀寫 **bool**。

### 備註
如果此 DataLabelFormat 物件的父項是 DataLabelCollection 的資料標籤集合，則此屬性可取得或設定新資料標籤在 DataLabelCollection 集合中的 ShowLabelValueFromCell 屬性的預設值。將此屬性設定為某個值時，也會將此值設定給 DataLabelCollection 集合中所有資料標籤的 ShowLabelValueFromCell 屬性（例如 "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" 會導致所有 DataLabels[i].ShowLabelValueFromCell 等於 val）。

### 定義:
```python
@property
def show_label_value_from_cell(self):
    ...

@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```

### 另見
* 類別 [`DataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)