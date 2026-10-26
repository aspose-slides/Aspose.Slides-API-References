---
title: ToArray()
second_title: Aspose.Slides for C++ API 참조
description: 모든 모양을 포함하는 배열을 생성하고 반환합니다.
type: docs
weight: 287
url: /ko/aspose.slides/ishapecollection/toarray/
---
## IShapeCollection::ToArray() 메서드

모든 모양을 포함하는 배열을 생성하고 반환합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray()=0
```

### 반환값

[IShape](../../ishape/) 객체의 배열.

## IShapeCollection::ToArray(int32_t, int32_t) 메서드

지정된 범위에 있는 모든 모양을 포함하는 배열을 생성하고 반환합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startIndex | **int32_t** | 반환할 첫 번째 모양의 인덱스입니다. |
| count | **int32_t** | 반환할 모양의 개수입니다. |

### 반환값

[IShape](../../ishape/) 객체의 배열.

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IShape](../../ishape/)
* 클래스 [IShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)