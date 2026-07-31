---
title: get_Handout()
second_title: Aspose.Slides untuk Referensi API C++
description: Menentukan berapa banyak slide dan dalam urutan apa yang akan ditempatkan pada halaman HandoutType.
type: docs
weight: 1
url: /id/aspose.slides.export/handoutlayoutingoptions/get_handout/
---
## HandoutLayoutingOptions::get_Handout() const metode

Menentukan berapa banyak slide dan dalam urutan apa yang akan ditempatkan pada halaman [HandoutType](../../handouttype/).

```cpp
HandoutType Aspose::Slides::Export::HandoutLayoutingOptions::get_Handout() const
```

## Catatan

Nilai default adalah **[HandoutType::Handouts6Horizontal](../../handouttype/)**. 

Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Lihat Juga

* Enum [HandoutType](../../handouttype/)
* Kelas [HandoutLayoutingOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)