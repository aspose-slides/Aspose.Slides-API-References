---
title: AddModernComment()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션의 끝에 새로운 최신 주석을 추가합니다.
type: docs
weight: 66
url: /ko/aspose.slides/commentcollection/addmoderncomment/
---
## CommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) method

컬렉션의 끝에 새로운 최신 주석을 추가합니다.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 새로운 최신 주석의 일반 텍스트. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 프레젠테이션에서 새로운 최신 주석을 추가할 위치. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) 슬라이드에 연결된 새로운 최신 주석. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 새로운 최신 주석을 추가할 슬라이드상의 위치. |
| creationTime | [System::DateTime](../../../system/datetime/) | 최신 주석 생성 시간. |

### 반환값

추가된 최신 주석.

## 비고

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IModernComment](../../imoderncomment/)
* 클래스 [String](../../../system/string/)
* 클래스 [ISlide](../../islide/)
* 클래스 [IShape](../../ishape/)
* 클래스 [PointF](../../../system.drawing/pointf/)
* 클래스 [DateTime](../../../system/datetime/)
* 클래스 [CommentCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)