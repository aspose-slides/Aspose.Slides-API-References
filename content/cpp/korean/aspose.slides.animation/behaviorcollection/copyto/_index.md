---
title: CopyTo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "ICollection의 요소를 System::Array에 복사하며, 특정 System::Array 인덱스부터 시작합니다."
type: docs
weight: 66
url: /ko/aspose.slides.animation/behaviorcollection/copyto/
---
## BehaviorCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IBehavior\>\>, int32_t) 메서드


[ICollection](../../../system.collections.generic/icollection/)의 요소를 [System::Array](../../../system/array/)에 복사하며, 특정 [System::Array](../../../system/array/) 인덱스에서 시작합니다.

```cpp
void Aspose::Slides::Animation::BehaviorCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IBehavior>> array, int32_t arrayIndex)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IBehavior](../../ibehavior/)\>\> | [ICollection](../../../system.collections.generic/icollection/)에서 복사된 요소들의 대상이 되는 일차원 [System::Array](../../../system/array/)입니다. [System::Array](../../../system/array/)는 0 기반 인덱스를 사용해야 합니다. |
| arrayIndex | **int32_t** | 복사가 시작되는 *array*의 0 기반 인덱스입니다. |

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IBehavior](../../ibehavior/)
* 클래스 [BehaviorCollection](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)