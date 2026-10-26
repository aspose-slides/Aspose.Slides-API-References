---
title: AddComment()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션 끝에 새 댓글을 추가합니다.
type: docs
weight: 14
url: /ko/aspose.slides/icommentcollection/addcomment/
---
## ICommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method

컬렉션 끝에 새 댓글을 추가합니다.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 새 댓글의 일반 텍스트입니다. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | 새 댓글을 추가할 프레젠테이션의 [Slide](../../slide/). |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 새 댓글을 추가할 슬라이드상의 위치입니다. |
| creationTime | [System::DateTime](../../../system/datetime/) | 댓글이 생성된 시간입니다. |

### 반환값

추가된 댓글.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [String](../../../system/string/)
* Class [ISlide](../../islide/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [DateTime](../../../system/datetime/)
* Class [ICommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)