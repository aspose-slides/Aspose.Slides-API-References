---
title: set_Zip64Mode()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menentukan apakah format ZIP64 digunakan untuk dokumen Presentation. Nilai defaultnya adalah Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /id/aspose.slides.export/ipptxoptions/set_zip64mode/
---
## IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) metode

Menentukan apakah format ZIP64 digunakan untuk dokumen [Presentation](../../../aspose.slides/presentation/). Nilai defaultnya adalah [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value)=0
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
* Kelas [IPptxOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)