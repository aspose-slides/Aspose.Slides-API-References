---
title: CopyTo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "ICollection의 요소들을 System::Array에 복사하며, 특정 System::Array 인덱스에서 시작합니다."
type: docs
weight: 105
url: /ko/aspose.slides/paragraphcollection/copyto/
---
## ParagraphCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IParagraph\>\>, int32_t) 메서드


[ICollection](../../../system.collections.generic/icollection/)의 요소들을 [System::Array](../../../system/array/)에 복사하며, 특정 [System::Array](../../../system/array/) 인덱스에서 시작합니다.

```cpp
void Aspose::Slides::ParagraphCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IParagraph>> array, int32_t arrayIndex)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\>\> | 복사된 요소들의 대상이 되는 1차원 [System::Array](../../../system/array/)입니다. [ICollection](../../../system.collections.generic/icollection/)에서 복사된 요소들입니다. [System::Array](../../../system/array/)는 0부터 시작하는 인덱싱이어야 합니다. |
| arrayIndex | **int32_t** | *array*에서 복사가 시작되는 0부터 시작하는 인덱스입니다. |

## 참고

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IParagraph](../../iparagraph/)
* 클래스 [ParagraphCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)