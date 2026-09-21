---
title: show_series_name property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/datalabelformat/show_series_name/
weight: 190
---
## show_series_name property
傳回或設定布林值，以指示圖表資料標籤的系列名稱顯示行為。  
True 為顯示系列名稱。False 為隱藏。  
可讀寫 **bool**。

### Remarks

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowSeriesName 屬性的預設值。將此屬性設定為某值時，也會將同一值設定給 DataLabelCollection 中所有資料標籤的 ShowSeriesName 屬性（即 "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" 會導致所有 DataLabels[i].ShowSeriesName 等於 val）。

### Definition:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```

### See Also
* class [`DataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)