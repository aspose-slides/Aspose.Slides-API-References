---
title: Remove()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션에서 항목을 제거합니다.
type: docs
weight: 79
url: /ko/aspose.slides.charts/piesplitcustompointcollection/remove/
---
## PieSplitCustomPointCollection::Remove(const System::SharedPtr\<IChartDataPoint\>\&) 메서드

컬렉션에서 항목을 제거합니다.

```cpp
bool Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(const System::SharedPtr<IChartDataPoint> &dataPoint) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| dataPoint | const [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\& | 제거할 데이터 포인트. |

### 반환 값

항목이 성공적으로 제거되면 true, 그렇지 않으면 false를 반환합니다. 이 메서드는 항목이 [System::Collections::Generic::List](../../../system.collections.generic/list/){T}에서 찾을 수 없는 경우에도 false를 반환합니다.

## PieSplitCustomPointCollection::Remove(int32_t) 메서드

컬렉션에서 항목을 부모 시리즈 포인트 컬렉션의 인덱스로 제거합니다.

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(int32_t dataPointIndex) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| dataPointIndex | **int32_t** | 부모 시리즈 포인트 컬렉션에서 데이터 포인트의 인덱스. |

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartDataPoint](../../ichartdatapoint/)
* 클래스 [PieSplitCustomPointCollection](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)