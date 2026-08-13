---
title: set_PrintFrameSlide()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 표시된 슬라이드 주위에 프레임을 그릴지 여부를 지정합니다.
type: docs
weight: 66
url: /ko/aspose.slides.export/handoutlayoutingoptions/set_printframeslide/
---
## HandoutLayoutingOptions::set_PrintFrameSlide(bool) 메서드


표시된 슬라이드 주위에 프레임을 그릴지 여부를 지정합니다.

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintFrameSlide(bool value)
```

## 비고


기본값은 **true**입니다. 

예: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintFrameSlide(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## 참고

* 클래스 [HandoutLayoutingOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)