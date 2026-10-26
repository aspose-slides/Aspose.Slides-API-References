---
title: set_Zip64Mode()
second_title: Aspose.Slides for C++ API リファレンス
description: "Presentation ドキュメントに ZIP64 形式が使用されているかどうかを指定します。デフォルト値は Zip64Mode::IfNecessary です"
type: docs
weight: 40
url: /ja/aspose.slides.export/pptxoptions/set_zip64mode/
---
## PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) メソッド

ZIP64 形式が [Presentation](../../../aspose.slides/presentation/) ドキュメントに使用されるかどうかを指定します。デフォルト値は [Zip64Mode::IfNecessary](../../zip64mode/) です。

```cpp
void Aspose::Slides::Export::PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value) override
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

* 列挙体 [Zip64Mode](../../zip64mode/)
* クラス [PptxOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)