---
title: CopyTo()
second_title: Aspose.Slides for C++ API 참조
description: "ICollection의 요소를 System::Array에 복사하며, 특정 System::Array 인덱스에서 시작합니다."
type: docs
weight: 118
url: /ko/aspose.slides/portioncollection/copyto/
---
## PortionCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IPortion\>\>, int32_t) method

[ICollection](../../../system.collections.generic/icollection/)의 요소들을 [System::Array](../../../system/array/)에 복사하며, 특정 [System::Array](../../../system/array/) 인덱스부터 시작합니다.

```cpp
void Aspose::Slides::PortionCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IPortion>> array, int32_t arrayIndex)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\>\> | [ICollection](../../../system.collections.generic/icollection/)에서 복사된 요소들의 대상이 되는 일차원 [System::Array](../../../system/array/)입니다. [System::Array](../../../system/array/)는 0 기반 인덱스를 가져야 합니다. |
| arrayIndex | **int32_t** | *array*에서 복사가 시작되는 0 기반 인덱스입니다. |

## 또 보기

* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPortion](../../iportion/)
* 클래스 [PortionCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)