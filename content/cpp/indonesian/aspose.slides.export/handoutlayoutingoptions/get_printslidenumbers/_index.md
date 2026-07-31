---
title: get_PrintSlideNumbers()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah nomor slide yang ditampilkan akan dicetak atau tidak.
type: docs
weight: 27
url: /id/aspose.slides.export/handoutlayoutingoptions/get_printslidenumbers/
---
## HandoutLayoutingOptions::get_PrintSlideNumbers() const method


Menentukan apakah nomor slide yang ditampilkan akan dicetak atau tidak.

```cpp
bool Aspose::Slides::Export::HandoutLayoutingOptions::get_PrintSlideNumbers() const
```

## Catatan


Nilai default adalah **true**. 

Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintSlideNumbers(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Lihat Juga

* Kelas [HandoutLayoutingOptions](../)
* Ruang nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)