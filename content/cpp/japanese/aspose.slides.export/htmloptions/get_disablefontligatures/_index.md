---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API リファレンス
description: テキストがリガチャを使用せずに描画されるかどうかを示す値を取得します。true に設定すると、描画出力でリガチャが無効になります。既定では、このプロパティは false に設定されています。
type: docs
weight: 92
url: /ja/aspose.slides.export/htmloptions/get_disablefontligatures/
---
## HtmlOptions::get_DisableFontLigatures() メソッド


テキストがリガチャを使用せずに描画されるかどうかを示す値を取得します。**true** に設定すると、描画出力でリガチャが無効になります。既定では、このプロパティは **false** に設定されています。

```cpp
bool Aspose::Slides::Export::HtmlOptions::get_DisableFontLigatures() override
```

## 備考


例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // テキストの描画でリガチャを無効にする

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## 関連項目

* クラス [HtmlOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)