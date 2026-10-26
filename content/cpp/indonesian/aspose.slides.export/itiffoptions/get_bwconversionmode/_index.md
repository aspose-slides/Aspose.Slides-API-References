---
title: get_BwConversionMode()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menentukan algoritma untuk mengubah gambar berwarna menjadi gambar hitam putih. Opsi ini hanya akan diterapkan jika ITiffOptions::get_CompressionType() diatur ke TiffCompressionTypes::CCITT4 atau TiffCompressionTypes::CCITT3 Baca BlackWhiteConversionMode. Defaultnya adalah BlackWhiteConversionMode::Default."
type: docs
weight: 183
url: /id/aspose.slides.export/itiffoptions/get_bwconversionmode/
---
## ITiffOptions::get_BwConversionMode() metode

Menentukan algoritma untuk mengubah gambar berwarna menjadi gambar hitam putih. Opsi ini hanya akan diterapkan jika [ITiffOptions::get_CompressionType()](../get_compressiontype/) diatur ke [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) atau [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Baca [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Defaultnya adalah [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual BlackWhiteConversionMode Aspose::Slides::Export::ITiffOptions::get_BwConversionMode()=0
```

## Catatan

Contoh berikut menunjukkan cara mengatur algoritma konversi ke Dithering.
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## Lihat Juga

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Class [ITiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)