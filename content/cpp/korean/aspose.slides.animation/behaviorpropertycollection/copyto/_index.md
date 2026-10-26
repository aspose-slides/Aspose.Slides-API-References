---
title: CopyTo()
second_title: Aspose.Slides C++ API 레퍼런스
description: "ICollection의 요소들을 System::Array에 복사하며, 특정 System::Array 인덱스에서 시작합니다."
type: docs
weight: 66
url: /ko/aspose.slides.animation/behaviorpropertycollection/copyto/
---
## BehaviorPropertyCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IBehaviorProperty\>\>, int32_t) 메서드

[ICollection](../../../system.collections.generic/icollection/)의 요소를 [System::Array](../../../system/array/)에 복사하며, 특정 [System::Array](../../../system/array/) 인덱스에서 시작합니다.

```cpp
void Aspose::Slides::Animation::BehaviorPropertyCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IBehaviorProperty>> array, int32_t arrayIndex) override
```

### 인수

| 매개변수 | 형식 | 설명 |

| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\> | 복사된 [ICollection](../../../system.collections.generic/icollection/) 요소들의 목적지가 되는 1차원 [System::Array](../../../system/array/)입니다. [System::Array](../../../system/array/)는 0 기반 인덱스를 가져야 합니다. |
| arrayIndex | **int32_t** | *array*에서 복사가 시작되는 0 기반 인덱스입니다. |

## 참고

* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IBehaviorProperty](../../ibehaviorproperty/)
* 클래스 [BehaviorPropertyCollection](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)