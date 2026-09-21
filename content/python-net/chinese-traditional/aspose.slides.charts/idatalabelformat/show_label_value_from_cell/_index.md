---
title: show_label_value_from_cell property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/idatalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell 屬性
表示指定圖表的資料標籤儲存格值顯示行為。 
True 會顯示儲存格值。False 會隱藏。 
讀寫 **bool**。


### 備註

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性會取得或設定 DataLabelCollection 中新資料標籤的 ShowLabelValueFromCell 屬性的預設值。 
將此屬性設定為某個值同時也會將該值設定給 DataLabelCollection 中所有資料標籤的 ShowLabelValueFromCell 屬性 
(即 "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" 會導致所有 DataLabels[i].ShowLabelValueFromCell 等於 val)。

### 定義：
```python
@property
def show_label_value_from_cell(self):
    ...

@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```


### 另見
* 類別 [`IDataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelformat)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)