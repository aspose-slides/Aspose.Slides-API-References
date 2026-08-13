---
title: ToArray()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 모든 도형을 포함하는 배열을 생성하고 반환합니다.
type: docs
weight: 326
url: /ko/aspose.slides/shapecollection/toarray/
---
## ShapeCollection::ToArray() 메서드

모든 도형을 포함하는 배열을 생성하고 반환합니다.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray() override
```

### 반환 값

[IShape](../../ishape/) 객체의 배열입니다.

## ShapeCollection::ToArray(int32_t, int32_t) 메서드

지정된 범위 내의 모든 도형을 포함하는 배열을 생성하고 반환합니다.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray(int32_t startIndex, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startIndex | **int32_t** | 첫 번째 반환할 도형의 인덱스입니다. |
| count | **int32_t** | 반환할 도형의 수입니다. |

### 반환 값

[IShape](../../ishape/) 객체의 배열입니다.

## 관련 항목

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IShape](../../ishape/)
* 클래스 [ShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)