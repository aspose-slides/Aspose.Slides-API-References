---
title: get_SlidesLayoutOptions()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengambil mode di mana slide ditempatkan pada halaman saat mengekspor presentasi ISlidesLayoutOptions.
type: docs
weight: 1
url: /id/aspose.slides.export/pdfoptions/get_slideslayoutoptions/
---
## PdfOptions::get_SlidesLayoutOptions() metode


Mengambil mode di mana slide ditempatkan pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::PdfOptions::get_SlidesLayoutOptions() override
```

## Catatan


Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Kelas [PdfOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Pustaka [Aspose.Slides](../../../)