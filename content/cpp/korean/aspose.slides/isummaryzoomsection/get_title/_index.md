---
title: get_Title()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Summary Zoom Section 객체의 텍스트 제목을 반환합니다.
type: docs
weight: 1
url: /ko/aspose.slides/isummaryzoomsection/get_title/
---
## ISummaryZoomSection::get_Title() 메서드


Summary Zoom [Section](../../section/) 객체의 텍스트 제목을 반환합니다.

```cpp
virtual System::String Aspose::Slides::ISummaryZoomSection::get_Title()=0
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

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [ISummaryZoomSection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)