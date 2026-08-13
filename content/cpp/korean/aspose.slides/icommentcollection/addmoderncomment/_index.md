---
title: AddModernComment()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션의 끝에 새로운 최신 주석을 추가합니다.
type: docs
weight: 27
url: /ko/aspose.slides/icommentcollection/addmoderncomment/
---
## ICommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) method

컬렉션의 끝에 새로운 최신 주석을 추가합니다.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 새로운 최신 주석의 일반 텍스트. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | 새로운 최신 주석을 추가할 프레젠테이션의 [Slide](../../slide/). |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 새로운 최신 주석이 연결된 슬라이드의 [Shape](../../shape/). |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 새로운 최신 주석을 추가할 슬라이드상의 위치. |
| creationTime | [System::DateTime](../../../system/datetime/) | 최신 주석이 생성된 시간. |

### 반환 값

추가된 최신 주석.

## 비고

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## 또 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IModernComment](../../imoderncomment/)
* 클래스 [String](../../../system/string/)
* 클래스 [ISlide](../../islide/)
* 클래스 [IShape](../../ishape/)
* 클래스 [PointF](../../../system.drawing/pointf/)
* 클래스 [DateTime](../../../system/datetime/)
* 클래스 [ICommentCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)