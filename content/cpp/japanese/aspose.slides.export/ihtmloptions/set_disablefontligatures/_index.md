---
title: set_DisableFontLigatures()
second_title: Aspose.Slides の C++ API リファレンス
description: テキストがリガチャを使用せずにレンダリングされるかどうかを示す値を設定します。true に設定すると、レンダリングされた出力でリガチャが無効になります。デフォルトでは、このプロパティは false に設定されています。
type: docs
weight: 196
url: /ja/aspose.slides.export/ihtmloptions/set_disablefontligatures/
---
## IHtmlOptions::set_DisableFontLigatures(bool) メソッド

テキストがリガチャを使用せずにレンダリングされるかどうかを示す値を設定します。**true** に設定すると、レンダリングされた出力でリガチャが無効になります。デフォルトでは、このプロパティは **false** に設定されています。

```cpp
virtual void Aspose::Slides::Export::IHtmlOptions::set_DisableFontLigatures(bool value)=0
```

## 備考


例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // テキストのレンダリングでリガチャを無効にする

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## 参照

* クラス [IHtmlOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)