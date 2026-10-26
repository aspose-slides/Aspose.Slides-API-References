---
title: get_Zip64Mode()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menentukan apakah format ZIP64 digunakan untuk dokumen Presentation. Nilai default adalah Zip64Mode::IfNecessary"
type: docs
weight: 27
url: /id/aspose.slides.export/pptxoptions/get_zip64mode/
---
## PptxOptions::get_Zip64Mode() metode

Menentukan apakah format ZIP64 digunakan untuk dokumen [Presentation](../../../aspose.slides/presentation/). Nilai baku adalah [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::PptxOptions::get_Zip64Mode() override
```

## Catatan

Contoh:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## Lihat Juga

* Enum [Zip64Mode](../../zip64mode/)
* Kelas [PptxOptions](../)
* Ruang nama [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)