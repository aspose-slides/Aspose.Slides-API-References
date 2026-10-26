---
title: ToArray()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 모든 댓글을 포함하는 배열을 생성하고 반환합니다.
type: docs
weight: 66
url: /ko/aspose.slides/icommentcollection/toarray/
---
## ICommentCollection::ToArray() 메서드


모든 댓글을 포함하는 배열을 생성하고 반환합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray()=0
```


### 반환 값

[IComment](../../icomment/) 배열.

## ICommentCollection::ToArray(int32_t, int32_t) 메서드


지정된 범위의 모든 댓글을 포함하는 배열을 생성하고 반환합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray(int32_t startIndex, int32_t count)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startIndex | **int32_t** | 반환할 첫 번째 댓글의 인덱스입니다. |
| count | **int32_t** | 반환할 댓글 수입니다. |

### 반환 값

[IComment](../../icomment/) 배열.

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IComment](../../icomment/)
* 클래스 [ICommentCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)