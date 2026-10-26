---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ API リファレンス
description: テキストがリガチャを使用せずにレンダリングされるかどうかを示す値を設定します。true に設定すると、レンダリングされた出力でリガチャが無効になります。既定では、このプロパティは false に設定されています。
type: docs
weight: 339
url: /ja/aspose.slides.export/svgoptions/set_disablefontligatures/
---
## SVGOptions::set_DisableFontLigatures(bool) メソッド

テキストがリガチャを使用せずにレンダリングされるかどうかを示す値を設定します。**true** に設定すると、レンダリングされた出力でリガチャが無効になります。既定では、このプロパティは **false** に設定されています。

```cpp
void Aspose::Slides::Export::SVGOptions::set_DisableFontLigatures(bool value) override
```

## 備考

例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // テキストのレンダリングでリガチャを無効にする

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## 参照

* クラス [SVGOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)