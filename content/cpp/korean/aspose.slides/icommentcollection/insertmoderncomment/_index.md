---
title: InsertModernComment()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 인덱스에 컬렉션에 새 현대 주석을 삽입합니다.
type: docs
weight: 53
url: /ko/aspose.slides/icommentcollection/insertmoderncomment/
---
## ICommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) 메서드


지정된 인덱스에 컬렉션에 새 현대 주석을 삽입합니다.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 컬렉션에서 현대 주석을 삽입해야 하는 요소의 인덱스입니다. |
| text | [System::String](../../../system/string/) | 새 현대 주석의 일반 텍스트입니다. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 프레젠테이션에서 새 현대 주석을 추가할 위치. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) 새 현대 주석이 연결된 슬라이드의 형태. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 새 현대 주석을 추가할 슬라이드상의 위치. |
| creationTime | [System::DateTime](../../../system/datetime/) | 현대 주석이 생성된 시간. |

### 반환 값

삽입된 현대 주석.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IModernComment](../../imoderncomment/)
* 클래스 [String](../../../system/string/)
* 클래스 [ISlide](../../islide/)
* 클래스 [IShape](../../ishape/)
* 클래스 [PointF](../../../system.drawing/pointf/)
* 클래스 [DateTime](../../../system/datetime/)
* 클래스 [ICommentCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)