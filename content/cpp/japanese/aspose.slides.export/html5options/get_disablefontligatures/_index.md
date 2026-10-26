---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API リファレンス
description: テキストが合字を使用せずにレンダリングされるかどうかを示す値を取得します。true に設定すると、レンダリングされた出力で合字が無効になります。既定では、このプロパティは false に設定されています。
type: docs
weight: 131
url: /ja/aspose.slides.export/html5options/get_disablefontligatures/
---
## Html5Options::get_DisableFontLigatures() メソッド


テキストが合字を使用せずにレンダリングされるかどうかを示す値を取得します。**true** に設定すると、レンダリングされた出力で合字が無効になります。既定では、このプロパティは **false** に設定されています。

```cpp
bool Aspose::Slides::Export::Html5Options::get_DisableFontLigatures() override
```

## 備考


例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // テキストレンダリングで合字を無効にする

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## 参照

* クラス [Html5Options](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)