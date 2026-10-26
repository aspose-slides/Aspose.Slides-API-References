---
title: set_Title()
second_title: Aspose.Slides for C++ API 참조
description: Summary Zoom Section 객체의 텍스트 제목을 반환합니다.
type: docs
weight: 14
url: /ko/aspose.slides/summaryzoomsection/set_title/
---
## SummaryZoomSection::set_Title(System::String) 메서드


Summary Zoom [Section](../../section/) 객체의 텍스트 제목을 반환합니다.

```cpp
void Aspose::Slides::SummaryZoomSection::set_Title(System::String value) override
```

## 비고


예제: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## 관련

* 클래스 [String](../../../system/string/)
* 클래스 [SummaryZoomSection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)