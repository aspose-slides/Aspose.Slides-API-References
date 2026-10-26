---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API リファレンス
description: テキストが合字を使用せずにレンダリングされるかどうかを示す値を取得します。true に設定すると、レンダリングされた出力で合字が無効になります。デフォルトでは、このプロパティは false に設定されています。
type: docs
weight: 183
url: /ja/aspose.slides.export/ihtmloptions/get_disablefontligatures/
---
## IHtmlOptions::get_DisableFontLigatures() メソッド

テキストが合字を使用せずにレンダリングされるかどうかを示す値を取得します。**true** に設定すると、レンダリングされた出力で合字が無効になります。デフォルトでは、このプロパティは **false** に設定されています。

```cpp
virtual bool Aspose::Slides::Export::IHtmlOptions::get_DisableFontLigatures()=0
```

## 備考

例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // テキストのレンダリングで合字を無効にする

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## 参照

* クラス [IHtmlOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)