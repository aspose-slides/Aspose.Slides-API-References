---
title: set_SlidesLayoutOptions()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur mode penempatan slide pada halaman saat mengekspor presentasi ISlidesLayoutOptions. Properti ini tidak mendukung penugasan objek bertipe Aspose.Slides.Export.HandoutLayoutingOptions
type: docs
weight: 404
url: /id/aspose.slides.export/iswfoptions/set_slideslayoutoptions/
---
## ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) metode

Mengatur mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../islideslayoutoptions/). Properti ini tidak mendukung penugasan objek bertipe **[Aspose.Slides.Export.HandoutLayoutingOptions](../../handoutlayoutingoptions/)**

```cpp
virtual void Aspose::Slides::Export::ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
```

## Keterangan

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
* Kelas [ISwfOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)