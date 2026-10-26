---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "컬렉션에 이미 인덱스 index인 데이터 포인트가 포함되어 있으면 해당 데이터 포인트를 반환합니다. 컬렉션에 인덱스 index == N인 데이터 포인트가 없고(이 컬렉션의 데이터 포인트 수가 N 이하인 경우) 부족한 데이터 포인트를 추가하고 마지막 데이터 포인트(요청된 인덱스를 가진)를 반환합니다. 예를 들어, 컬렉션 인덱스가 {0, 1, 2}이고 요청된 인덱스가 5인 경우, 메서드는 부족한 데이터 포인트를 추가합니다: {0, 1, 2, 3, 4, 5}. 그리고 인덱스 5인 데이터 포인트를 반환합니다."
type: docs
weight: 170
url: /ko/aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx/
---
## ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) 메서드

컬렉션에 이미 인덱스 *index*의 데이터 포인트가 포함되어 있으면 해당 데이터 포인트를 반환합니다. 컬렉션에 인덱스 *index* == N인 데이터 포인트가 없고(이 컬렉션의 데이터 포인트 수가 N 이하인 경우) 부족한 데이터 포인트를 추가하고 마지막 데이터 포인트(요청된 인덱스를 갖는)를 반환합니다. 예를 들어, 컬렉션 인덱스가 {0, 1, 2}이고 요청된 인덱스가 5인 경우, 메서드는 부족한 데이터 포인트를 추가합니다: {0, 1, 2, 3, 4, 5}. 그리고 인덱스 5인 데이터 포인트를 반환합니다.

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **uint32_t** | 인덱스. |

### 반환 값

요청된 인덱스의 데이터 포인트를 반환합니다.

## 관련 항목

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartDataPoint](../../ichartdatapoint/)
* 클래스 [ChartDataPointCollection](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)