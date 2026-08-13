---
title: get_Overlap()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 2-D 차트에서 막대와 열이 겹치는 정도를 백분율( -100%에서 100%까지)로 지정합니다. 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 적용됩니다. 이는 상위 시리즈 그룹의 해당 속성을 투영한 것이며, 따라서 이 속성은 읽기 전용입니다. 값을 변경하려면 get_ParentSeriesGroup()->get(set)_Overlap() 읽기/쓰기 속성을 사용하십시오. 읽기 전용 int8_t.
type: docs
weight: 690
url: /ko/aspose.slides.charts/ichartseries/get_overlap/
---
## IChartSeries::get_Overlap() 메서드

2-D 차트에서 막대와 열이 겹치는 정도를 백분율( -100%에서 100%까지)로 지정합니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에도 적용됩니다. 이는 상위 시리즈 그룹의 해당 속성을 투영한 것이며, 따라서 이 속성은 읽기 전용입니다. 값을 변경하려면 [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap() 읽기/쓰기 속성을 사용하십시오. 읽기 전용 **int8_t**.

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeries::get_Overlap()=0
```

## 비고

Overlap는 막대와 열 사이의 겹침 또는 간격 정도를 너비의 백분율로 지정합니다:
* -100%: 최대 간격 (막대가 완전히 분리됩니다).
* 0%: 막대가 겹치거나 간격 없이 나란히 배치됩니다.
* 100%: 최대 겹침 (막대가 서로 완전히 겹칩니다). 이는 [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap() 속성을 투영한 것입니다.

## 참고

* 클래스 [IChartSeries](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)