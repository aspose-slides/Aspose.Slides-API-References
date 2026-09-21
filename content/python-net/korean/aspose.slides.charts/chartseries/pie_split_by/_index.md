---
title: pie_split_by property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/chartseries/pie_split_by/
weight: 340
---
## pie_split_by 속성
두 번째 파이 또는 바가 파이-오브-파이 또는 바-오브-파이 차트에서 어떤 데이터 포인트에 해당하는지를 결정하는 방법을 지정합니다.
이 속성은 이 시리즈에만 해당되는 것이 아니라 부모 시리즈 그룹의 모든 시리즈에 적용되며, 해당 그룹 속성의 투영입니다.
따라서 이 속성은 읽기 전용입니다.
ParentSeriesGroup 속성을 사용하여 부모 시리즈 그룹에 접근합니다.
값을 변경하려면 ParentSeriesGroup.PieSplitBy 읽기/쓰기 속성을 사용합니다.
읽기 전용 [`PieSplitType`](/slides/python-net/ko/aspose.slides.charts/piesplittype).

### 비고

1) 이것은 속성 ParentSeriesGroup.PieSplitBy의 투영입니다.
2) 속성 값이 PieSplitType.Custom인 경우, ParentSeriesGroup.PieSplitCustomPoints 속성을 사용하여 사용자 지정 분할 정보를 정의할 수 있습니다.

### 정의:
```python
@property
def pie_split_by(self):
    ...
```

### 참조
* 클래스 [`ChartSeries`](/slides/python-net/ko/aspose.slides.charts/chartseries)
* 열거형 [`PieSplitType`](/slides/python-net/ko/aspose.slides.charts/piesplittype)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)