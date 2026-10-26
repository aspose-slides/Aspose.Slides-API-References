---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API リファレンス
description: テキストが合字を使用せずにレンダリングされるかどうかを示す値を取得します。true に設定すると、レンダリングされた出力で合字が無効になります。既定では、このプロパティは false に設定されています。
type: docs
weight: 326
url: /ja/aspose.slides.export/isvgoptions/get_disablefontligatures/
---
## ISVGOptions::get_DisableFontLigatures() メソッド


テキストが合字を使用せずにレンダリングされるかどうかを示す値を取得します。**true** に設定すると、レンダリングされた出力で合字が無効になります。既定では、このプロパティは **false** に設定されています。

```cpp
virtual bool Aspose::Slides::Export::ISVGOptions::get_DisableFontLigatures()=0
```

## 備考


例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // テキスト描画で合字を無効にする

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## 参照

* クラス [ISVGOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)