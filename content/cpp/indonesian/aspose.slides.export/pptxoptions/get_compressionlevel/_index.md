---
title: get_CompressionLevel()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menentukan tingkat kompresi yang digunakan saat menyimpan dokumen presentasi. Nilai defaultnya adalah CompressionLevel::Level6."
type: docs
weight: 79
url: /id/aspose.slides.export/pptxoptions/get_compressionlevel/
---
## PptxOptions::get_CompressionLevel() metode


Menentukan tingkat kompresi yang digunakan saat menyimpan dokumen presentasi. Nilai defaultnya adalah [CompressionLevel::Level6](../../compressionlevel/).

```cpp
Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::PptxOptions::get_CompressionLevel() override
```

## Catatan


Tingkat kompresi yang lebih tinggi menghasilkan file yang lebih kecil tetapi memerlukan waktu pemrosesan lebih lama. Rasio kompresi sebenarnya tergantung pada konten presentasi. 

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
* Perpustakaan [Aspose.Slides](../../../)