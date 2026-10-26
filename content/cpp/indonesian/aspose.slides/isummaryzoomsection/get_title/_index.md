---
title: get_Title()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengembalikan judul teks dari objek Summary Zoom Section.
type: docs
weight: 1
url: /id/aspose.slides/isummaryzoomsection/get_title/
---
## ISummaryZoomSection::get_Title() method


Mengembalikan judul teks dari objek Summary Zoom [Section](../../section/).

```cpp
virtual System::String Aspose::Slides::ISummaryZoomSection::get_Title()=0
```

## Catatan


Contoh: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [ISummaryZoomSection](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)