---
title: set_Description()
second_title: C++용 Aspose.Slides API 레퍼런스
description: Summary Zoom Section 객체의 텍스트 설명을 반환합니다.
type: docs
weight: 40
url: /ko/aspose.slides/isummaryzoomsection/set_description/
---
## ISummaryZoomSection::set_Description(System::String) 메서드


Summary Zoom [Section](../../section/) 객체의 텍스트 설명을 반환합니다.

```cpp
virtual void Aspose::Slides::ISummaryZoomSection::set_Description(System::String value)=0
```

## 비고


예: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [ISummaryZoomSection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)