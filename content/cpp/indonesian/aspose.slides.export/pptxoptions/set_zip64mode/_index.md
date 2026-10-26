---
title: set_Zip64Mode()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menentukan apakah format ZIP64 digunakan untuk dokumen Presentasi. Nilai default adalah Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /id/aspose.slides.export/pptxoptions/set_zip64mode/
---
## PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) metode

Menentukan apakah format ZIP64 digunakan untuk dokumen [Presentation](../../../aspose.slides/presentation/). Nilai default adalah [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
void Aspose::Slides::Export::PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value) override
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
* Ruang Nama [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)