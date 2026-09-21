---
title: is_number_format_linked_to_source property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/datalabelformat/is_number_format_linked_to_source/
weight: 70
---
## is_number_format_linked_to_source 屬性
讀/寫 **bool**.

### 備註

如果此 DataLabelFormat 物件的父項是 DataLabelCollection 資料標籤集合，則此
            屬性取得或設定新資料
            標籤在 DataLabelCollection 集合中的 IsNumberFormatLinkedToSource 屬性的預設值。
            設定此屬性的值也會將此值設定為所有 DataLabelCollection 集合中資料標籤的 IsNumberFormatLinkedToSource 屬性
            針對 DataLabelCollection 集合中的所有資料標籤
            （例如 "DataLabels.DefaultDataLabelFormat.IsNumberFormatLinkedToSource = val;" 會導致
            所有 DataLabels[i].IsNumberFormatLinkedToSource 均等於 val）。

### 定義:
```python
@property
def is_number_format_linked_to_source(self):
    ...

@is_number_format_linked_to_source.setter
def is_number_format_linked_to_source(self, value):
    ...
```

### 另請參閱
* 類別 [`DataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)