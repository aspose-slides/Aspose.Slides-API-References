---
title: separator property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/idatalabelformat/separator/
weight: 110
---
## separator 屬性
設定或傳回代表圖表中資料標籤使用的 separator 的 Variant。
讀/寫 **str**.

### 備註

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性取得或設定在 DataLabelCollection 集合中新資料標籤的 Separator 屬性的預設值。  
設定此屬性時，同時會將此值設定給 DataLabelCollection 集合中所有資料標籤的 Separator 屬性（即 `"DataLabels.DefaultDataLabelFormat.Separator = val;"` 會導致所有 `DataLabels[i].Separator` 等於 `val`）。

### 定義:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```

### 另見
* 類別 [`IDataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelformat)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)