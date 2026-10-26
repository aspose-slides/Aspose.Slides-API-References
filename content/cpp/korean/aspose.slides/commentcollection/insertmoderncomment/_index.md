---
title: InsertModernComment()
second_title: Aspose.Slides C++ API 레퍼런스
description: 지정된 인덱스에 새로운 현대 주석을 컬렉션에 삽입합니다.
type: docs
weight: 92
url: /ko/aspose.slides/commentcollection/insertmoderncomment/
---
## CommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) method


지정된 인덱스에 새 현대 주석을 컬렉션에 삽입합니다.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 컬렉션에서 현대 주석을 삽입할 요소의 인덱스. |
| text | [System::String](../../../system/string/) | 새 현대 주석의 일반 텍스트. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | 프레젠테이션에서 새 현대 주석을 추가할 [Slide](../../slide/). |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 새 현대 주석이 연결된 슬라이드상의 [Shape](../../shape/). |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 새 현대 주석을 추가할 슬라이드상의 위치. |
| creationTime | [System::DateTime](../../../system/datetime/) | 현대 주석이 생성된 시간. |

### 반환값

삽입된 현대 주석.

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IModernComment](../../imoderncomment/)
* 클래스 [String](../../../system/string/)
* 클래스 [ISlide](../../islide/)
* 클래스 [IShape](../../ishape/)
* 클래스 [PointF](../../../system.drawing/pointf/)
* 클래스 [DateTime](../../../system/datetime/)
* 클래스 [CommentCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)