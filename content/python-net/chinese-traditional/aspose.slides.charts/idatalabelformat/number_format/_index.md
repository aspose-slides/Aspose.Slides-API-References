---
title: number_format property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/idatalabelformat/number_format/
weight: 80
---
## number_format 屬性
表示 DataLabels 物件的格式字串。
            讀/寫 **str**。


### 備註

            如果此 DataLabelFormat 物件的父項是 DataLabelCollection 資料標籤集合，則此屬性會取得或設定 DataLabelCollection 集合中新資料標籤的 NumberFormat 屬性的預設值。
            當此屬性設定為某個值時，該值也會同時設定到 DataLabelCollection 集合中所有資料標籤的 NumberFormat 屬性 (例如 "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" 會導致所有 DataLabels[i].NumberFormat 等於 val)。

### 定義:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```


### 另見
* 類別 [`IDataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelformat)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)