---
title: get_SlidesLayoutOptions()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan mode di mana slide ditempatkan pada halaman saat mengekspor presentasi ISlidesLayoutOptions. Properti ini tidak mendukung penugasan objek bertipe HandoutLayoutingOptions
type: docs
weight: 391
url: /id/aspose.slides.export/swfoptions/get_slideslayoutoptions/
---
## SwfOptions::get_SlidesLayoutOptions() metode

Mendapatkan mode di mana slide ditempatkan pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../islideslayoutoptions/). Properti ini tidak mendukung penugasan objek bertipe [HandoutLayoutingOptions](../../handoutlayoutingoptions/)

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::SwfOptions::get_SlidesLayoutOptions() override
```

## Catatan

Contoh:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_CommentsPosition(CommentsPositions::Right);

System::SharedPtr<SwfOptions> options = System::MakeObject<SwfOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.swf", SaveFormat::Swf, options);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Kelas [SwfOptions](../)
* RuangNama [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)