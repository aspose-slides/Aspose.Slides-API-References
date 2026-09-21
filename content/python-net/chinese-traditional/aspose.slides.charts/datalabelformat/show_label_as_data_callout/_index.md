---
title: show_label_as_data_callout property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/datalabelformat/show_label_as_data_callout/
weight: 140
---
## show_label_as_data_callout 屬性
決定指定圖表的資料標籤是顯示為資料引線還是資料標籤。

            如果此 DataLabelFormat 物件的父項是 DataLabelCollection 資料標籤集合，則此
            property 取得或設定 ShowLabelAsDataCallout property 的預設值，用於新的資料 
            標籤在 DataLabelCollection 集合中。
            設定此 property 的值也會將此值設定為 ShowLabelAsDataCallout property 
            適用於 DataLabelCollection 集合中的所有資料標籤
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" 會導致 
            所有 DataLabels[i].ShowLabelAsDataCallout 均等於 val)。

### 定義:
```python
@property
def show_label_as_data_callout(self):
    ...

@show_label_as_data_callout.setter
def show_label_as_data_callout(self, value):
    ...
```

### 參見
* 類別 [`DataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 程式庫 [`Aspose.Slides`](/slides/python-net)