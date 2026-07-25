---
title: get_BwConversionMode()
second_title: Aspose.Slides for C++ API リファレンス
description: "カラー画像を白黒画像に変換するアルゴリズムを指定します。このオプションは、ITiffOptions::get_CompressionType() が TiffCompressionTypes::CCITT4 または TiffCompressionTypes::CCITT3 に設定されている場合にのみ適用されます。参照 BlackWhiteConversionMode。デフォルトは BlackWhiteConversionMode::Default です。"
type: docs
weight: 196
url: /ja/aspose.slides.export/tiffoptions/get_bwconversionmode/
---
## TiffOptions::get_BwConversionMode() メソッド

カラー画像を白黒画像に変換するアルゴリズムを指定します。このオプションは、[ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) が [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) または [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) に設定されている場合にのみ適用されます。参照 [BlackWhiteConversionMode](../../blackwhiteconversionmode/)。デフォルトは [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/) です。

```cpp
BlackWhiteConversionMode Aspose::Slides::Export::TiffOptions::get_BwConversionMode() override
```

## 備考

以下の例は、変換アルゴリズムをディザリングに設定する方法を示します。
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