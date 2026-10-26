---
title: get_BwConversionMode()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menentukan algoritma untuk mengubah gambar berwarna menjadi gambar hitam putih. Opsi ini hanya akan diterapkan jika ITiffOptions::get_CompressionType() diatur ke TiffCompressionTypes::CCITT4 atau TiffCompressionTypes::CCITT3 Baca BlackWhiteConversionMode. Defaultnya adalah BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /id/aspose.slides.export/tiffoptions/get_bwconversionmode/
---
## TiffOptions::get_BwConversionMode() metode

Menentukan algoritma untuk mengubah gambar berwarna menjadi gambar hitam putih. Opsi ini hanya akan diterapkan jika [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) diatur ke [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) atau [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Baca [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Defaultnya adalah [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
BlackWhiteConversionMode Aspose::Slides::Export::TiffOptions::get_BwConversionMode() override
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
* Kelas [TiffOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Pustaka [Aspose.Slides](../../../)