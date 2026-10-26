---
title: gap_depth property
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/ichartseries/gap_depth/
weight: 160
---
## gap_depth 속성
Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart.
            This is the property not only of this series but of all series of parent series 
            group - this is projection of appropriate group property. And so this property 
            is read-only.
            Use ParentSeriesGroup property for access to parent series group.
            Use ParentSeriesGroup.GapDepth read/write property for change value.
            Read-only **int**.

### 비고

This is the projection of the property ParentSeriesGroup.GapDepth.

### 정의:
```python
@property
def gap_depth(self):
    ...
```

### 관련 보기
* 클래스 [`IChartSeries`](/slides/python-net/ko/aspose.slides.charts/ichartseries)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)