---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API リファレンス
description: テキストがリガチャを使用せずにレンダリングされるかどうかを示す値を取得します。true に設定すると、レンダリングされた出力でリガチャが無効になります。既定では、このプロパティは false に設定されています。
type: docs
weight: 40
url: /ja/aspose.slides.export/irenderingoptions/get_disablefontligatures/
---
## IRenderingOptions::get_DisableFontLigatures() メソッド


テキストがリガチャを使用せずにレンダリングされるかどうかを示す値を取得します。**true** に設定すると、レンダリングされた出力でリガチャが無効になります。既定では、このプロパティは **false** に設定されています。

```cpp
virtual bool Aspose::Slides::Export::IRenderingOptions::get_DisableFontLigatures()=0
```

## 備考


例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // テキストのレンダリングでリガチャを無効にする

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## 参照

* クラス [IRenderingOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)