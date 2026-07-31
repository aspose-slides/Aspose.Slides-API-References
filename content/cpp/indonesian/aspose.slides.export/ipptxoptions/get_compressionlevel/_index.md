---
title: get_CompressionLevel()
second_title: Aspose.Slides untuk C++ Referensi API
description: "Menentukan tingkat kompresi yang digunakan saat menyimpan dokumen presentasi. Nilai default adalah CompressionLevel::Level6."
type: docs
weight: 79
url: /id/aspose.slides.export/ipptxoptions/get_compressionlevel/
---
## IPptxOptions::get_CompressionLevel() metode


Menentukan tingkat kompresi yang digunakan saat menyimpan dokumen presentasi. Nilai default adalah [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::IPptxOptions::get_CompressionLevel()=0
```

## Catatan


Tingkat kompresi yang lebih tinggi menghasilkan file yang lebih kecil tetapi memerlukan waktu pemrosesan lebih lama. Rasio kompresi aktual tergantung pada konten presentasi. 

Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Lihat Juga

* Enum [CompressionLevel](../../compressionlevel/)
* Class [IPptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)