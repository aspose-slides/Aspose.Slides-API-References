---
title: set_Handout()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 페이지 HandoutType에 배치될 슬라이드 수와 순서를 지정합니다.
type: docs
weight: 14
url: /ko/aspose.slides.export/handoutlayoutingoptions/set_handout/
---
## HandoutLayoutingOptions::set_Handout(HandoutType) method


페이지 [HandoutType](../../handouttype/)에 배치될 슬라이드 수와 순서를 지정합니다.

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_Handout(HandoutType value)
```

## 비고


기본값은 **[HandoutType::Handouts6Horizontal](../../handouttype/)**. 

예시: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## 참고

* 열거형 [HandoutType](../../handouttype/)
* 클래스 [HandoutLayoutingOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)