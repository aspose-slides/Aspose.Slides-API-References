---
title: get_Handout()
second_title: Aspose.Slides for C++ API 참조
description: HandoutType 페이지에 배치될 슬라이드 수와 순서를 지정합니다.
type: docs
weight: 1
url: /ko/aspose.slides.export/handoutlayoutingoptions/get_handout/
---
## HandoutLayoutingOptions::get_Handout() const 메서드

Specifies how many slides and in what sequence will be placed on the page [HandoutType](../../handouttype/).

```cpp
HandoutType Aspose::Slides::Export::HandoutLayoutingOptions::get_Handout() const
```

## 비고

Default value is **[HandoutType::Handouts6Horizontal](../../handouttype/)**. 

Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## 또 보기

* 열거형 [HandoutType](../../handouttype/)
* 클래스 [HandoutLayoutingOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)