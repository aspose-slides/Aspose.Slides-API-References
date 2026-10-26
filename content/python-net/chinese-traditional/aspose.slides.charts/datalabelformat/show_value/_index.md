---
title: show_value property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/datalabelformat/show_value/
weight: 200
---
## show_value 屬性
表示指定圖表的資料標籤百分比值顯示行為。  
True 會顯示百分比值。 False 則隱藏。  
讀/寫 **bool**。

### 備註

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此
屬性會取得或設定 DataLabelCollection 中新資料標籤的 ShowValue Property 的預設值。  
將此屬性設定為某個值時，也會將該值設定給 DataLabelCollection 中所有資料標籤的 ShowValue 屬性  
（即 "DataLabels.DefaultDataLabelFormat.ShowValue = val;" 會導致  
所有 DataLabels[i].ShowValue 等於 val）。

### 定義：
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```

### 參見
* 類別 [`DataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)