---
title: data_source_type property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/basechartvalue/data_source_type/
weight: 20
---
## data_source_type 속성
Specifies whether AsCell, AsCells, AsLiteralString or AsLiteralDouble 
            property is actual in descendants. In other words it specifies the type 
            of value of the Data property.
            읽기/쓰기 [`DataSourceType`](/slides/python-net/ko/aspose.slides.charts/datasourcetype).

### 비고

For points in ChartDataPointCollection this property is read-only. 
            In this case for changing value of this property you can use one of the 
            ChartDataPointCollection.DataSourceTypeFor<...> properties.

### 정의:
```python
@property
def data_source_type(self):
    ...

@data_source_type.setter
def data_source_type(self, value):
    ...
```

### 참조
* 클래스 [`BaseChartValue`](/slides/python-net/ko/aspose.slides.charts/basechartvalue)
* 열거형 [`DataSourceType`](/slides/python-net/ko/aspose.slides.charts/datasourcetype)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)