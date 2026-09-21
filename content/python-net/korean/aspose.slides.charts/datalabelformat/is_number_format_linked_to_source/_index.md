---
title: is_number_format_linked_to_source property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/datalabelformat/is_number_format_linked_to_source/
weight: 70
---
## is_number_format_linked_to_source 속성
읽기/쓰기 **bool**.

### 비고

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
property gets or sets the default value of the IsNumberFormatLinkedToSource property for the new data 
labels in the DataLabelCollection collection.
Set this property with value also sets this value to the IsNumberFormatLinkedToSource property 
for all data labels in the DataLabelCollection collection
(i.e. "DataLabels.DefaultDataLabelFormat.IsNumberFormatLinkedToSource = val;" cause to 
all DataLabels[i].IsNumberFormatLinkedToSource is equal to val).

### 정의:
```python
@property
def is_number_format_linked_to_source(self):
    ...

@is_number_format_linked_to_source.setter
def is_number_format_linked_to_source(self, value):
    ...
```

### 참조
* 클래스 [`DataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/datalabelformat)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)