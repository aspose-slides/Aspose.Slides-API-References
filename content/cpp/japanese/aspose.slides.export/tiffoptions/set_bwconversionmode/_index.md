---
title: set_BwConversionMode()
second_title: Aspose.Slides for C++ API リファレンス
description: "カラー画像を白黒画像に変換するアルゴリズムを指定します。このオプションは、ITiffOptions::get_CompressionType() が TiffCompressionTypes::CCITT4 または TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode に設定されている場合にのみ適用されます。デフォルトは BlackWhiteConversionMode::Default です。"
type: docs
weight: 209
url: /ja/aspose.slides.export/tiffoptions/set_bwconversionmode/
---
## TiffOptions::set_BwConversionMode(BlackWhiteConversionMode) メソッド


カラー画像を白黒画像に変換するアルゴリズムを指定します。このオプションは、[ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) が [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) または [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/) に設定されている場合にのみ適用されます。デフォルトは [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/) です。

```cpp
void Aspose::Slides::Export::TiffOptions::set_BwConversionMode(BlackWhiteConversionMode value) override
```

## 備考


次の例は、変換アルゴリズムをディザリングに設定する方法を示します。 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## 参照

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* クラス [TiffOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)