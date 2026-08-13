---
title: get_Overlap()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 2D 차트에서 막대와 열이 겹치는 정도를 백분율( -100%에서 100%까지)로 지정합니다. 이는 해당 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성입니다. 상위 시리즈 그룹의 해당 속성을 투영한 것이므로 이 속성은 읽기 전용입니다. 값을 변경하려면 get_ParentSeriesGroup()->Overlap() 읽기/쓰기 속성을 사용하십시오. 읽기 전용 int8_t.
type: docs
weight: 690
url: /ko/aspose.slides.charts/chartseries/get_overlap/
---
## ChartSeries::get_Overlap() 메서드

Specifies how much bars and columns overlap on 2-D charts, as a percentage (from -100% to 100%). This is the property not only of this series but of all series of parent series group. It is a projection of the appropriate property in the parent series group, and so this property is read-only. To change the value, use the [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/) read/write property. Read-only **int8_t**.

```cpp
int8_t Aspose::Slides::Charts::ChartSeries::get_Overlap() override
```

## 비고

Overlap는 막대와 열 사이의 겹침 정도 또는 간격을 너비의 백분율로 지정합니다:* -100%: 최대 간격(막대가 완전히 분리됨).
* 0%: 막대가 겹치거나 간격 없이 나란히 배치됩니다.
* 100%: 최대 겹침(막대가 서로 완전히 겹칩니다). 이는 [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/) 속성의 투영입니다.

## 참고

* 클래스 [ChartSeries](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)