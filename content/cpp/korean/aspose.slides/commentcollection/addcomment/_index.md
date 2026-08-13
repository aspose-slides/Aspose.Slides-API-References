---
title: AddComment()
second_title: C++용 Aspose.Slides API 참조
description: 컬렉션 끝에 새 주석을 추가합니다.
type: docs
weight: 53
url: /ko/aspose.slides/commentcollection/addcomment/
---
## CommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) 메서드

컬렉션 끝에 새 주석을 추가합니다.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 새 주석의 평문 텍스트. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | 새 주석을 추가할 프레젠테이션 내 [Slide](../../slide/). |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 새 주석을 추가할 슬라이드상의 위치. |
| creationTime | [System::DateTime](../../../system/datetime/) | 주석 생성 시간. |

### 반환값

추가된 주석.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [String](../../../system/string/)
* Class [ISlide](../../islide/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [DateTime](../../../system/datetime/)
* Class [CommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)