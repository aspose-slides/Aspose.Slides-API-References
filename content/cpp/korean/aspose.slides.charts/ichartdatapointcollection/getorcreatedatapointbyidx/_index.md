---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "컬렉션에 이미 인덱스 index 인 데이터 포인트가 포함되어 있으면 해당 데이터 포인트를 반환합니다. 컬렉션에 인덱스 index ==N인 데이터 포인트가 없고(이 컬렉션의 데이터 포인트 수가 N보다 작거나 같은 경우) 결손 데이터 포인트를 추가하고 마지막(요청된 인덱스를 가진) 데이터를 반환합니다. 예를 들어 컬렉션 인덱스가 {0, 1, 2}이고 요청된 인덱스가 5인 경우, 메서드는 결손 데이터 포인트를 추가합니다: {0, 1, 2, 3, 4, 5}. 그리고 인덱스 5인 데이터 포인트를 반환합니다."
type: docs
weight: 131
url: /ko/aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx/
---
## IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) 메서드

컬렉션에 이미 *index* 인덱스의 데이터 포인트가 포함되어 있으면 해당 데이터 포인트를 반환합니다. 컬렉션에 *index* ==N 인덱스의 데이터 포인트가 없고(컬렉션의 데이터 포인트 수가 N보다 작거나 같은 경우) 결손 데이터 포인트를 추가하고 마지막(요청된 인덱스를 가진) 데이터를 반환합니다. 예를 들어 컬렉션 인덱스가 {0, 1, 2}이고 요청된 인덱스가 5인 경우, 메서드는 결손 데이터 포인트를 추가합니다: {0, 1, 2, 3, 4, 5}. 그리고 인덱스 5인 데이터 포인트를 반환합니다.

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | **uint32_t** | 인덱스. |

### 반환 값

요청된 인덱스의 데이터 포인트를 반환합니다.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [IChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)