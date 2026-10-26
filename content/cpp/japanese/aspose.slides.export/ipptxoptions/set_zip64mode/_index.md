---
title: set_Zip64Mode()
second_title: Aspose.Slides for C++ API リファレンス
description: "Presentation ドキュメントで ZIP64 形式を使用するかどうかを指定します。デフォルト値は Zip64Mode::IfNecessary です"
type: docs
weight: 40
url: /ja/aspose.slides.export/ipptxoptions/set_zip64mode/
---
## IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) メソッド


ZIP64 形式が [Presentation](../../../aspose.slides/presentation/) ドキュメントに使用されるかどうかを指定します。デフォルト値は [Zip64Mode::IfNecessary](../../zip64mode/) です。

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value)=0
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
* クラス [IPptxOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)