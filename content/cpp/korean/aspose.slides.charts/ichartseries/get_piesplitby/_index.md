---
title: get_PieSplitBy()
second_title: Aspose.Slides for C++ API 레퍼런스
description: pie-of-pie 또는 bar-of-pie 차트에서 두 번째 파이 또는 막대에 포함되는 데이터 포인트를 결정하는 방법을 지정합니다. 이 속성은 해당 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성이며, 해당 그룹 속성의 프로젝션입니다. 따라서 이 속성은 읽기 전용입니다. 상위 시리즈 그룹에 액세스하려면 ParentSeriesGroup 속성을 사용하십시오. 값 변경을 위해 get_ParentSeriesGroup()->get(set)_PieSplitBy() 읽기/쓰기 속성을 사용하십시오. 읽기 전용 PieSplitType.
type: docs
weight: 729
url: /ko/aspose.slides.charts/ichartseries/get_piesplitby/
---
## IChartSeries::get_PieSplitBy() method


이 속성은 pie-of-pie 또는 bar-of-pie 차트에서 두 번째 파이 또는 막대에 포함되는 데이터 포인트를 결정하는 방법을 지정합니다. 이 속성은 해당 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성이며, 해당 그룹 속성의 프로젝션입니다. 따라서 이 속성은 읽기 전용입니다. 상위 시리즈 그룹에 액세스하려면 ParentSeriesGroup 속성을 사용하십시오. 값 변경을 위해 [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() 읽기/쓰기 속성을 사용하십시오. 읽기 전용 [PieSplitType](../../piesplittype/).

```cpp
virtual PieSplitType Aspose::Slides::Charts::IChartSeries::get_PieSplitBy()=0
```

## 비고


1) 이것은 [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() 속성의 프로젝션입니다. 2) 속성 값이 [PieSplitType::Custom](../../piesplittype/)인 경우 [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/) 속성을 사용하여 사용자 정의 분할 정보를 정의할 수 있습니다.

## 참고

* 열거형 [PieSplitType](../../piesplittype/)
* 클래스 [IChartSeries](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)