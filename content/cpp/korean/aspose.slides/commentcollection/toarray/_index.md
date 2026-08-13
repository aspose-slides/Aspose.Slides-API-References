---
title: ToArray()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 모든 주석을 포함하는 배열을 생성하고 반환합니다.
type: docs
weight: 105
url: /ko/aspose.slides/commentcollection/toarray/
---
## CommentCollection::ToArray() 메서드

모든 주석을 포함하는 배열을 생성하고 반환합니다.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray() override
```

### 반환값

[Comment](../../comment/) 배열.

## CommentCollection::ToArray(int32_t, int32_t) 메서드

지정된 범위의 모든 주석을 포함하는 배열을 생성하고 반환합니다.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray(int32_t startIndex, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startIndex | **int32_t** | 반환할 첫 번째 주석의 인덱스입니다. |
| count | **int32_t** | 반환할 주석의 개수입니다. |

### 반환값

[Comment](../../comment/) 배열.

## 관련 항목

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IComment](../../icomment/)
* 클래스 [CommentCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)