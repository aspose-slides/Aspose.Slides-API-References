---
title: get_PieSplitBy()
second_title: Aspose.Slides for C++ API 참조
description: pie-of-pie 또는 bar-of-pie 차트에서 두 번째 파이 또는 바에 포함되는 데이터 포인트를 결정하는 방법을 지정합니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하십시오. 값 변경을 위해 get_ParentSeriesGroup()->get(set)_PieSplitBy() 읽기/쓰기 속성을 사용하십시오. 읽기 전용 PieSplitType.
type: docs
weight: 755
url: /ko/aspose.slides.charts/chartseries/get_piesplitby/
---
## ChartSeries::get_PieSplitBy() 메서드

Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup 속성 for access to parent series group. Use [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() 읽기/쓰기 속성 for change value. 읽기 전용 [PieSplitType](../../piesplittype/).

```cpp
PieSplitType Aspose::Slides::Charts::ChartSeries::get_PieSplitBy() override
```

## 비고

1) 이는 [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() 속성의 투영입니다. 2) 속성 값이 [PieSplitType::Custom](../../piesplittype/)이면 [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/) 속성을 사용하여 사용자 정의 분할 정보를 정의할 수 있습니다. 

## 참고

* Enum [PieSplitType](../../piesplittype/)
* Class [ChartSeries](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)