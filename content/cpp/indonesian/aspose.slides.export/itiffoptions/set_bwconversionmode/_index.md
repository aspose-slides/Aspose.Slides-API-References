---
title: set_BwConversionMode()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menentukan algoritma untuk mengonversi gambar berwarna menjadi gambar hitam putih. Opsi ini hanya akan diterapkan jika ITiffOptions::get_CompressionType() diatur ke TiffCompressionTypes::CCITT4 atau TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode. Defaultnya adalah BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /id/aspose.slides.export/itiffoptions/set_bwconversionmode/
---
## ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode) metode


Menentukan algoritma untuk mengonversi gambar berwarna menjadi gambar hitam putih. Opsi ini hanya akan diterapkan jika [ITiffOptions::get_CompressionType()](../get_compressiontype/) diatur ke [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) atau [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Defaultnya adalah [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode value)=0
```

## Keterangan


Contoh berikut menunjukkan cara mengatur algoritma konversi menjadi Dithering. 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## Lihat Juga

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Kelas [ITiffOptions](../)
* namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)