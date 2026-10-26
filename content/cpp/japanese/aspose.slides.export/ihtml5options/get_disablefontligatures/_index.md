---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API リファレンス
description: テキストがリガチャを使用せずに描画されるかどうかを示す値を取得します。true に設定すると、描画出力でリガチャが無効になります。デフォルトでは、このプロパティは false に設定されています。
type: docs
weight: 131
url: /ja/aspose.slides.export/ihtml5options/get_disablefontligatures/
---
## IHtml5Options::get_DisableFontLigatures() メソッド


テキストがリガチャを使用せずに描画されるかどうかを示す値を取得します。**true** に設定すると、描画出力でリガチャが無効になります。デフォルトでは、このプロパティは **false** に設定されています。

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_DisableFontLigatures()=0
```

## 備考


例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // テキスト描画時にリガチャを無効化する

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## 参照

* クラス [IHtml5Options](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)