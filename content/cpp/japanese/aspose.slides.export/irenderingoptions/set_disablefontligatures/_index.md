---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ API リファレンス
description: テキストが合字を使用せずにレンダリングされるかどうかを示す値を設定します。true に設定すると、レンダリング出力で合字が無効になります。既定では、このプロパティは false に設定されています。
type: docs
weight: 53
url: /ja/aspose.slides.export/irenderingoptions/set_disablefontligatures/
---
## IRenderingOptions::set_DisableFontLigatures(bool) メソッド


テキストが合字を使用せずにレンダリングされるかどうかを示す値を設定します。**true** に設定すると、レンダリング結果で合字が無効になります。既定では、このプロパティは **false** に設定されています。

```cpp
virtual void Aspose::Slides::Export::IRenderingOptions::set_DisableFontLigatures(bool value)=0
```

## 備考


例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // テキストのレンダリングで合字を無効にする

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