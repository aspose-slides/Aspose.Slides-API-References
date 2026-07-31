---
title: get_PrintComments()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah komentar akan ditampilkan pada slide atau tidak
type: docs
weight: 79
url: /id/aspose.slides.export/handoutlayoutingoptions/get_printcomments/
---
## HandoutLayoutingOptions::get_PrintComments() const metode


Menentukan apakah menampilkan komentar pada slide atau tidak

```cpp
bool Aspose::Slides::Export::HandoutLayoutingOptions::get_PrintComments() const
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
* RuangNama [Aspose::Slides::Export](../../)
* Pustaka [Aspose.Slides](../../../)