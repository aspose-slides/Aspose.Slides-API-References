---
title: show_series_name property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/idatalabelformat/show_series_name/
weight: 190
---
## show_series_name 屬性
傳回或設定布林值，以指示圖表上資料標籤的系列名稱顯示行為。 
            True 表示顯示系列名稱。 False 表示隱藏。
            讀/寫 **bool**.


### 備註

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性取得或設定新資料標籤在 DataLabelCollection 集合中的 ShowSeriesName 屬性的預設值。 
            設定此屬性時，同時也會將此值設定給 DataLabelCollection 集合中所有資料標籤的 ShowSeriesName 屬性
            （即 "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" 會導致所有 DataLabels[i].ShowSeriesName 等於 val）。

### 定義：
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```


### 另見
* 類別 [`IDataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelformat)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)