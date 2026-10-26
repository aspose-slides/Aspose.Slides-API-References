---
title: InsertComment()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 인덱스에 컬렉션에 새 댓글을 삽입합니다.
type: docs
weight: 79
url: /ko/aspose.slides/commentcollection/insertcomment/
---
## CommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method


지정된 인덱스에 새 댓글을 컬렉션에 삽입합니다.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 컬렉션에서 댓글을 삽입해야 하는 요소의 인덱스. |
| text | [System::String](../../../system/string/) | 새 댓글의 일반 텍스트. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/)에서 새 댓글을 추가할 프레젠테이션. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 새 댓글을 추가할 슬라이드의 위치. |
| creationTime | [System::DateTime](../../../system/datetime/) | 댓글 생성 시간. |

### 반환값

삽입된 댓글.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [String](../../../system/string/)
* Class [ISlide](../../islide/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [DateTime](../../../system/datetime/)
* Class [CommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)