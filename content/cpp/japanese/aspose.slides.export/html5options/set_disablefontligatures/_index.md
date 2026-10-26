---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ API リファレンス
description: テキストが合字を使用せずにレンダリングされるかどうかを示す値を設定します。true に設定すると、レンダリングされた出力で合字が無効になります。既定では、このプロパティは false に設定されています。
type: docs
weight: 144
url: /ja/aspose.slides.export/html5options/set_disablefontligatures/
---
## Html5Options::set_DisableFontLigatures(bool) メソッド


テキストが合字を使用せずにレンダリングされるかどうかを示す値を設定します。**true** に設定すると、レンダリングされた出力で合字が無効になります。既定では、このプロパティは **false** に設定されています。

```cpp
void Aspose::Slides::Export::Html5Options::set_DisableFontLigatures(bool value) override
```

## 備考


例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // テキストレンダリングでの合字を無効にする

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## 参照

* クラス [Html5Options](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)