---
title: get_Zip64Mode()
second_title: Aspose.Slides for C++ API リファレンス
description: "Presentation ドキュメントに ZIP64 フォーマットが使用されるかどうかを指定します。デフォルト値は Zip64Mode::IfNecessary です。"
type: docs
weight: 27
url: /ja/aspose.slides.export/ipptxoptions/get_zip64mode/
---
## IPptxOptions::get_Zip64Mode() メソッド

ZIP64 フォーマットが [Presentation](../../../aspose.slides/presentation/) ドキュメントに使用されるかどうかを指定します。デフォルト値は [Zip64Mode::IfNecessary](../../zip64mode/) です。

```cpp
virtual Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::IPptxOptions::get_Zip64Mode()=0
```

## 備考

例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## 参照

* Enum [Zip64Mode](../../zip64mode/)
* クラス [IPptxOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)