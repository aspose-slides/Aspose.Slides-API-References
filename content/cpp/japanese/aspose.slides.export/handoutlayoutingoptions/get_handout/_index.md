---
title: get_Handout()
second_title: Aspose.Slides for C++ API リファレンス
description: ページ HandoutType に配置されるスライドの枚数と順序を指定します。
type: docs
weight: 1
url: /ja/aspose.slides.export/handoutlayoutingoptions/get_handout/
---
## HandoutLayoutingOptions::get_Handout() const メソッド


ページ [HandoutType](../../handouttype/) に配置されるスライドの枚数と順序を指定します。

```cpp
HandoutType Aspose::Slides::Export::HandoutLayoutingOptions::get_Handout() const
```

## 備考


既定値は **[HandoutType::Handouts6Horizontal](../../handouttype/)** です。

例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## 参照

* 列挙型 [HandoutType](../../handouttype/)
* クラス [HandoutLayoutingOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)