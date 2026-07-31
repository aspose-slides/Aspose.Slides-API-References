---
title: set_CompressionLevel()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menentukan tingkat kompresi yang digunakan saat menyimpan dokumen presentasi. Nilai default adalah CompressionLevel::Level6."
type: docs
weight: 92
url: /id/aspose.slides.export/ipptxoptions/set_compressionlevel/
---
## IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) metode

Menetapkan tingkat kompresi yang digunakan saat menyimpan dokumen presentasi. Nilai default adalah [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value)=0
```

## Keterangan

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
* Kelas [IPptxOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)