---
title: IndexOf()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 IChartSeries를 검색하고 전체 컬렉션에서 첫 번째 발생의 0부터 시작하는 인덱스를 반환합니다
type: docs
weight: 40
url: /ko/aspose.slides.charts/ichartseriescollection/indexof/
---
## IChartSeriesCollection::IndexOf(System::SharedPtr\<IChartSeries\>) 메서드

지정된 [IChartSeries](../../ichartseries/)를 검색하고 전체 컬렉션에서 첫 번째 발생의 0부터 시작하는 인덱스를 반환합니다.

```cpp
virtual int32_t Aspose::Slides::Charts::IChartSeriesCollection::IndexOf(System::SharedPtr<IChartSeries> value)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartSeries](../../ichartseries/)\> | [Chart](../../chart/) 시리즈 값. |

### 반환값

값이 전체 CollectionBase 내에서 처음 발생한 경우의 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartSeries](../../ichartseries/)
* 클래스 [IChartSeriesCollection](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)