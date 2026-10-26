---
title: show_series_name property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/datalabelformat/show_series_name/
weight: 190
---
## show_series_name 속성
Returns or sets a Boolean to indicate the series name display behavior for the data labels on a chart. 
            True 시리즈 이름을 표시합니다. False는 숨깁니다.
            읽기/쓰기 **bool**.


### 참고

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowSeriesName property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowSeriesName property 
            for all data labels in the DataLabelCollection collection
            (예: "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" 로 인해 
            all DataLabels[i].ShowSeriesName is equal to val).

### 정의:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```


### 참조
* 클래스 [`DataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/datalabelformat)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)