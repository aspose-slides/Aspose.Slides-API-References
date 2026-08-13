---
title: get_PrintComments()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 슬라이드에 주석을 표시할지 여부를 지정합니다
type: docs
weight: 79
url: /ko/aspose.slides.export/handoutlayoutingoptions/get_printcomments/
---
## HandoutLayoutingOptions::get_PrintComments() const 메서드


슬라이드에 주석을 표시할지 여부를 지정합니다.

```cpp
bool Aspose::Slides::Export::HandoutLayoutingOptions::get_PrintComments() const
```

## 비고


기본값은 **false**. 

예: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintComments(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## 참고

* 클래스 [HandoutLayoutingOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)