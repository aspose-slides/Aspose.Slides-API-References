---
title: IndexOf()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 ChartSeries를 검색하고 전체 Collection에서 첫 번째 발생의 0부터 시작하는 인덱스를 반환합니다
type: docs
weight: 79
url: /ko/aspose.slides.charts/chartseriescollection/indexof/
---
## ChartSeriesCollection::IndexOf(System::SharedPtr\<IChartSeries\>) 메서드

지정된 [ChartSeries](../../chartseries/)를 검색하고 전체 컬렉션에서 첫 번째 발생의 0부터 시작하는 인덱스를 반환합니다

```cpp
int32_t Aspose::Slides::Charts::ChartSeriesCollection::IndexOf(System::SharedPtr<IChartSeries> value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartSeries](../../ichartseries/)\> | [Chart](../../chart/) 시리즈 값. |

### 반환 값

값이 전체 CollectionBase 내에서 처음 나타나는 경우의 0부터 시작하는 인덱스이며, 찾지 못한 경우 -1을 반환합니다.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartSeries](../../ichartseries/)
* 클래스 [ChartSeriesCollection](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)