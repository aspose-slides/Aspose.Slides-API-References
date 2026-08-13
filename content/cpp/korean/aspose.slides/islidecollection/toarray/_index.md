---
title: ToArray()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 모든 슬라이드가 포함된 배열을 만들고 반환합니다.
type: docs
weight: 92
url: /ko/aspose.slides/islidecollection/toarray/
---
## ISlideCollection::ToArray() method

모든 슬라이드가 포함된 배열을 만들고 반환합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray()=0
```

### 반환값

[ISlide](../../islide/) 배열

## ISlideCollection::ToArray(int32_t, int32_t) method

지정된 범위의 모든 슬라이드가 포함된 배열을 만들고 반환합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startIndex | **int32_t** | 추가할 첫 번째 슬라이드의 인덱스입니다. |
| count | **int32_t** | 추가할 슬라이드 수입니다. |

### 반환값

[ISlide](../../islide/) 배열

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISlide](../../islide/)
* 클래스 [ISlideCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)