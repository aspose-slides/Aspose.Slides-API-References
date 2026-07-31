---
title: set_PrintComments()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah menampilkan komentar pada slide atau tidak
type: docs
weight: 92
url: /id/aspose.slides.export/handoutlayoutingoptions/set_printcomments/
---
## HandoutLayoutingOptions::set_PrintComments(bool) metode

Menentukan apakah menampilkan komentar pada slide atau tidak

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintComments(bool value)
```

## Catatan

Nilai default adalah **false**. 

Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintComments(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Lihat Juga

* Kelas [HandoutLayoutingOptions](../)
* Ruang nama [Aspose::Slides::Export](../../)
* Pustaka [Aspose.Slides](../../../)