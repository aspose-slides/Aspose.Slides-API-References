---
title: pie_split_by property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/ichartseries/pie_split_by/
weight: 340
---
## pie_split_by 속성
Specifies how to determine which data points are in the second pie or bar 
            파이-오브-파이 또는 바-오브-파이 차트에서.
            이 속성은 이 시리즈에만 해당되는 것이 아니라 상위 시리즈 그룹의 모든 시리즈에 해당합니다 
            그룹 - 이는 적절한 그룹 속성의 투영입니다. 따라서 이 속성은 
            읽기 전용입니다.
            Use ParentSeriesGroup 속성을 사용하여 상위 시리즈 그룹에 접근하십시오.
            Use ParentSeriesGroup.PieSplitBy 읽기/쓰기 속성을 사용하여 값을 변경하십시오.
            읽기 전용 [`PieSplitType`](/slides/python-net/ko/aspose.slides.charts/piesplittype).

### 비고

1) 이는 속성 ParentSeriesGroup.PieSplitBy의 투영입니다.
            2) 속성 값이 PieSplitType.Custom인 경우 사용자 정의 분할을 정의할 수 있습니다 
            ParentSeriesGroup.PieSplitCustomPoints 속성을 사용하여 정보를 정의할 수 있습니다.

### 정의:
```python
@property
def pie_split_by(self):
    ...
```

### 참고
* 클래스 [`IChartSeries`](/slides/python-net/ko/aspose.slides.charts/ichartseries)
* 열거형 [`PieSplitType`](/slides/python-net/ko/aspose.slides.charts/piesplittype)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)