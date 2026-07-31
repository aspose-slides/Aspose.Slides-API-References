---
title: set_BwConversionMode()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menentukan algoritma untuk mengonversi gambar berwarna menjadi gambar hitam putih. Opsi ini hanya akan diterapkan jika ITiffOptions::get_CompressionType() diatur ke TiffCompressionTypes::CCITT4 atau TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode. Defaultnya adalah BlackWhiteConversionMode::Default."
type: docs
weight: 209
url: /id/aspose.slides.export/tiffoptions/set_bwconversionmode/
---
## TiffOptions::set_BwConversionMode(BlackWhiteConversionMode) metode

Menentukan algoritma untuk mengonversi gambar berwarna menjadi gambar hitam putih. Opsi ini hanya akan diterapkan jika [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) diatur ke [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) atau [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Defaultnya adalah [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
void Aspose::Slides::Export::TiffOptions::set_BwConversionMode(BlackWhiteConversionMode value) override
```

## Keterangan

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
* Perpustakaan [Aspose.Slides](../../../)