---
title: set_BwConversionMode()
second_title: Aspose.Slides for C++ API リファレンス
description: "カラー画像を白黒画像に変換するアルゴリズムを指定します。このオプションは ITiffOptions::get_CompressionType() が TiffCompressionTypes::CCITT4 または TiffCompressionTypes::CCITT3 に設定され、BlackWhiteConversionMode が書き込まれる場合にのみ適用されます。デフォルトは BlackWhiteConversionMode::Default です。"
type: docs
weight: 196
url: /ja/aspose.slides.export/itiffoptions/set_bwconversionmode/
---
## ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode) メソッド


カラー画像を黒白画像に変換するアルゴリズムを指定します。このオプションは [ITiffOptions::get_CompressionType()](../get_compressiontype/) が [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) または [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/) に設定されている場合にのみ適用されます。デフォルトは [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/) です。

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode value)=0
```

## 備考


次の例は、変換アルゴリズムを Dithering に設定する方法を示します。 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## 参照

* 列挙型 [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* クラス [ITiffOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)