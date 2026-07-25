---
title: get_BwConversionMode()
second_title: Aspose.Slides for C++ API リファレンス
description: "カラー画像を白黒画像に変換するアルゴリズムを指定します。このオプションは ITiffOptions::get_CompressionType() が TiffCompressionTypes::CCITT4 または TiffCompressionTypes::CCITT3 に設定されている場合にのみ適用されます。Read BlackWhiteConversionMode。デフォルトは BlackWhiteConversionMode::Defaultです。"
type: docs
weight: 183
url: /ja/aspose.slides.export/itiffoptions/get_bwconversionmode/
---
## ITiffOptions::get_BwConversionMode() メソッド


カラー画像を白黒画像に変換するアルゴリズムを指定します。このオプションは [ITiffOptions::get_CompressionType()](../get_compressiontype/) が [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) または [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) に設定されている場合にのみ適用されます。[BlackWhiteConversionMode](../../blackwhiteconversionmode/) を参照してください。デフォルトは [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/) です。

```cpp
virtual BlackWhiteConversionMode Aspose::Slides::Export::ITiffOptions::get_BwConversionMode()=0
```

## 備考


次の例は、変換アルゴリズムをディザリングに設定する方法を示しています。 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## 参照

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* クラス [ITiffOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)