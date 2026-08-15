---
title: get_Handout()
second_title: Aspose.Slides for C++ API 參考
description: 指定在 HandoutType 頁面上將放置多少張投影片以及其順序。
type: docs
weight: 1
url: /zh-hant/aspose.slides.export/handoutlayoutingoptions/get_handout/
---
## HandoutLayoutingOptions::get_Handout() const 方法


指定在頁面上將放置多少張投影片以及其順序 [HandoutType](../../handouttype/).

```cpp
HandoutType Aspose::Slides::Export::HandoutLayoutingOptions::get_Handout() const
```

## 備註


預設值為 **[HandoutType::Handouts6Horizontal](../../handouttype/)**。 

範例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## 另請參閱

* 列舉 [HandoutType](../../handouttype/)
* 類別 [HandoutLayoutingOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)