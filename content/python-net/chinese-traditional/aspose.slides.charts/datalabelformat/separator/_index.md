---
title: separator property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/datalabelformat/separator/
weight: 110
---
## 分隔符屬性
設定或傳回表示圖表上資料標籤所使用的分隔符之 Variant。
            可讀寫 **str**。

### 說明

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            屬性取得或設定新資料標籤在 DataLabelCollection 集合中的 Separator 屬性的預設值。
            以值設定此屬性同時會將此值設定至 DataLabelCollection 集合中所有資料標籤的 Separator 屬性
            (i.e. "DataLabels.DefaultDataLabelFormat.Separator = val;" 會導致所有 DataLabels[i].Separator 等於 val)。

### 定義：
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```

### 另見
* 類別 [`DataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)