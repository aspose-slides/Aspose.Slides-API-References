---
title: InsertComment()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 인덱스에 컬렉션에 새 댓글을 삽입합니다.
type: docs
weight: 40
url: /ko/aspose.slides/icommentcollection/insertcomment/
---
## ICommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) 메서드


지정된 인덱스에 컬렉션에 새 댓글을 삽입합니다.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 컬렉션에서 댓글을 삽입해야 하는 요소의 인덱스입니다. |
| text | [System::String](../../../system/string/) | 새 댓글의 일반 텍스트입니다. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 프레젠테이션에서 새 댓글을 추가할 슬라이드. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 새 댓글을 추가할 슬라이드상의 위치입니다. |
| creationTime | [System::DateTime](../../../system/datetime/) | 댓글이 생성된 시간입니다. |

### 반환값

삽입된 댓글.

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IComment](../../icomment/)
* 클래스 [String](../../../system/string/)
* 클래스 [ISlide](../../islide/)
* 클래스 [PointF](../../../system.drawing/pointf/)
* 클래스 [DateTime](../../../system/datetime/)
* 클래스 [ICommentCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)