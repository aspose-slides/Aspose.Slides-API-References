---
title: CopyTo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "ICollection의 요소를 System::Array에 복사하며, 특정 System::Array 인덱스에서 시작합니다."
type: docs
weight: 326
url: /ko/aspose.slides.effects/imagetransformoperationcollection/copyto/
---
## ImageTransformOperationCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IImageTransformOperation\>\>, int32_t) method

[ICollection](../../../system.collections.generic/icollection/)의 요소를 [System::Array](../../../system/array/)에 복사합니다. 특정 [System::Array](../../../system/array/) 인덱스부터 시작합니다.

```cpp
void Aspose::Slides::Effects::ImageTransformOperationCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IImageTransformOperation>> array, int32_t arrayIndex) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IImageTransformOperation](../../iimagetransformoperation/)\>\> | 복사된 요소가 [ICollection](../../../system.collections.generic/icollection/)에서 온 목적지인 일차원 [System::Array](../../../system/array/)입니다. [System::Array](../../../system/array/)는 0부터 시작하는 인덱스를 가져야 합니다. |
| arrayIndex | **int32_t** | *array*에서 복사가 시작되는 0부터 시작하는 인덱스입니다. |

## 참조

* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IImageTransformOperation](../../iimagetransformoperation/)
* 클래스 [ImageTransformOperationCollection](../)
* 네임스페이스 [Aspose::Slides::Effects](../../)
* 라이브러리 [Aspose.Slides](../../../)