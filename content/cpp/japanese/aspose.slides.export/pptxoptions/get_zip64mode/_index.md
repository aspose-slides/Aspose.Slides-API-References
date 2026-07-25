---
title: get_Zip64Mode()
second_title: Aspose.Slides for C++ API リファレンス
description: "Presentation ドキュメントで ZIP64 形式が使用されるかどうかを指定します。デフォルト値は Zip64Mode::IfNecessary です"
type: docs
weight: 27
url: /ja/aspose.slides.export/pptxoptions/get_zip64mode/
---
## PptxOptions::get_Zip64Mode() メソッド

ZIP64 形式が [Presentation](../../../aspose.slides/presentation/) ドキュメントで使用されるかどうかを指定します。デフォルト値は [Zip64Mode::IfNecessary](../../zip64mode/) です。

```cpp
Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::PptxOptions::get_Zip64Mode() override
```

## 備考

例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## 参照

* 列挙型 [Zip64Mode](../../zip64mode/)
* クラス [PptxOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)