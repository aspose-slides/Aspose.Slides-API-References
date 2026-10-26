---
title: number_format property
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/datalabelformat/number_format/
weight: 80
---
## number_format 屬性
表示 DataLabels 物件的格式字串。
            讀寫 **str**.


### 備註

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性取得或設定新資料標籤在 DataLabelCollection 集合中的 NumberFormat 屬性的預設值。\
當此屬性被設定為某個值時，該值也會套用到 DataLabelCollection 集合中所有資料標籤的 NumberFormat 屬性（即「DataLabels.DefaultDataLabelFormat.NumberFormat = val;」會導致所有 DataLabels[i].NumberFormat 等於 val）。

### 定義:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```


### 相關資訊
* 類別 [`DataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)