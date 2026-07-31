---
title: set_CompressionLevel()
second_title: Aspose.Slides untuk Referensi API C++
description: "Menentukan tingkat kompresi yang digunakan saat menyimpan dokumen presentasi. Nilai default adalah CompressionLevel::Level6."
type: docs
weight: 92
url: /id/aspose.slides.export/pptxoptions/set_compressionlevel/
---
## PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) metode

Menentukan tingkat kompresi yang digunakan saat menyimpan dokumen presentasi. Nilai default adalah [CompressionLevel::Level6](../../compressionlevel/).

```cpp
void Aspose::Slides::Export::PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value) override
```

## Keterangan

Tingkat kompresi yang lebih tinggi menghasilkan file yang lebih kecil tetapi memerlukan lebih banyak waktu pemrosesan. Rasio kompresi aktual tergantung pada konten presentasi. 

Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Lihat Juga

* Enum [CompressionLevel](../../compressionlevel/)
* Kelas [PptxOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)