---
title: GetSlideComments()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 특정 작성자가 추가한 모든 슬라이드 주석을 반환합니다.
type: docs
weight: 209
url: /ko/aspose.slides/slide/getslidecomments/
---
## Slide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) 메서드


특정 작성자가 추가한 모든 슬라이드 주석을 반환합니다.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::Slide::GetSlideComments(System::SharedPtr<ICommentAuthor> author) override
```


### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | 찾을 주석의 작성자, 또는 모든 주석을 반환하려면 null. |

### Return Value

[Comment](../../comment/)의 배열.

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IComment](../../icomment/)
* 클래스 [ICommentAuthor](../../icommentauthor/)
* 클래스 [Slide](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)