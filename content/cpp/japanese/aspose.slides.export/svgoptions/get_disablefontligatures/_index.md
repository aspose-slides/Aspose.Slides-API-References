---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API リファレンス
description: テキストがリガチャを使用せずにレンダリングされるかどうかを示す値を取得します。true に設定すると、レンダリングされた出力でリガチャが無効になります。デフォルトでは、このプロパティは false に設定されています。
type: docs
weight: 326
url: /ja/aspose.slides.export/svgoptions/get_disablefontligatures/
---
## SVGOptions::get_DisableFontLigatures() メソッド

テキストがリガチャを使用せずにレンダリングされるかどうかを示す値を取得します。**true** に設定すると、レンダリングされた出力でリガチャが無効になります。デフォルトでは、このプロパティは **false** に設定されています。

```cpp
bool Aspose::Slides::Export::SVGOptions::get_DisableFontLigatures() override
```

## 備考

例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // テキストレンダリングでリガチャを無効にする

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## 参照

* クラス [SVGOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)