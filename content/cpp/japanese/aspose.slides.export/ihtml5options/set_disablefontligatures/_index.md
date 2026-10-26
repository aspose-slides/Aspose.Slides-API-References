---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ API リファレンス
description: テキストがリガチャを使用せずにレンダリングされるかどうかを示す値を設定します。true に設定すると、レンダリング出力でリガチャが無効になります。既定では、このプロパティは false に設定されています。
type: docs
weight: 144
url: /ja/aspose.slides.export/ihtml5options/set_disablefontligatures/
---
## IHtml5Options::set_DisableFontLigatures(bool) メソッド

文字列がリガチャを使用せずにレンダリングされるかどうかを示す値を設定します。**true** に設定すると、レンダリング出力でリガチャが無効になります。既定では、このプロパティは **false** に設定されています。

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_DisableFontLigatures(bool value)=0
```

## 備考

例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // テキストレンダリングでリガチャを無効にする

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## 参照

* クラス [IHtml5Options](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)