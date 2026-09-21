---
title: show_percentage property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/datalabelformat/show_percentage/
weight: 180
---
## show_percentage 屬性
表示指定圖表的資料標籤百分比值顯示行為。 
True 顯示百分比值。False 隱藏。 
可讀寫 **bool**.


### 備註

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            屬性取得或設定 ShowPercentage 屬性的預設值，供新資料
            標籤在 DataLabelCollection 集合中。
            設定此屬性時，同時會將此值設定至 ShowPercentage 屬性
            給 DataLabelCollection 集合中的所有資料標籤
            (例如 "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" 會導致
            所有 DataLabels[i].ShowPercentage 等於 val)。

### 定義:
```python
@property
def show_percentage(self):
    ...

@show_percentage.setter
def show_percentage(self, value):
    ...
```


### 另見
* 類別 [`DataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)