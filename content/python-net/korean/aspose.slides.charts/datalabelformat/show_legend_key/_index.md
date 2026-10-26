---
title: show_legend_key property
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/datalabelformat/show_legend_key/
weight: 170
---
## show_legend_key 속성
Represents a specified chart's data label legend key display behavior. 
            True if the data label legend key is visible.
            Read/write **bool**.

### 비고

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowLegendKey property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowLegendKey property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" cause to 
            all DataLabels[i].ShowLegendKey is equal to val).

### 정의:
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```

### 또 보기
* 클래스 [`DataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/datalabelformat)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)