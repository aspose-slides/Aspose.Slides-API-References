---
title: CopyTo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "ICollection의 요소를 System::Array에 복사하고, 특정 System::Array 인덱스에서 시작합니다."
type: docs
weight: 118
url: /ko/aspose.slides.charts/piesplitcustompointcollection/copyto/
---
## PieSplitCustomPointCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IChartDataPoint\>\>, int32_t) 메서드

[ICollection](../../../system.collections.generic/icollection/)의 요소를 [System::Array](../../../system/array/)에 복사하며, 특정 [System::Array](../../../system/array/) 인덱스에서 시작합니다.

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IChartDataPoint>> array, int32_t arrayIndex) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\> | [ICollection](../../../system.collections.generic/icollection/)에서 복사된 요소들의 대상이 되는 1차원 [System::Array](../../../system/array/)입니다. [System::Array](../../../system/array/)는 0 기반 인덱스를 가져야 합니다. |
| arrayIndex | **int32_t** | *array*에서 복사가 시작되는 0 기반 인덱스입니다. |

## 관련 항목

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartDataPoint](../../ichartdatapoint/)
* 클래스 [PieSplitCustomPointCollection](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)