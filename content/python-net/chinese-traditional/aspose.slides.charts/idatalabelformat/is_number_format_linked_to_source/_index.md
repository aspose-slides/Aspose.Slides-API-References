---
title: is_number_format_linked_to_source property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/idatalabelformat/is_number_format_linked_to_source/
weight: 70
---
## is_number_format_linked_to_source 屬性
讀/寫 **bool**.

### 備註

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性取得或設定新資料標籤在 DataLabelCollection 中的 IsNumberFormatLinkedToSource 屬性的預設值。以此屬性設定值時，同時會將此值設定給 DataLabelCollection 中所有資料標籤的 IsNumberFormatLinkedToSource 屬性（例如 "DataLabels.DefaultDataLabelFormat.IsNumberFormatLinkedToSource = val;" 會導致所有 DataLabels[i].IsNumberFormatLinkedToSource 等於 val）。

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
* 類別 [`IDataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelformat)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 程式庫 [`Aspose.Slides`](/slides/python-net)