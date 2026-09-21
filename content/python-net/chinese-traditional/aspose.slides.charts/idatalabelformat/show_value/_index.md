---
title: show_value property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/idatalabelformat/show_value/
weight: 200
---
## show_value 屬性
表示指定圖表的資料標籤百分比值顯示行為。 
True 顯示百分比值。False 隱藏。 
可讀寫 **bool**。

### 備註

如果此 DataLabelFormat 物件的父項是 DataLabelCollection 資料標籤集合，則此屬性取得或設定 DataLabelCollection 集合中新資料標籤的 ShowValue 屬性的預設值。 
將此屬性設定為某個值時，同時會將此值設定為 DataLabelCollection 集合中所有資料標籤的 ShowValue 屬性 (i.e. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" cause to all DataLabels[i].ShowValue is equal to val)。

### 定義：
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```

### 另請參閱
* 類別 [`IDataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelformat)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)