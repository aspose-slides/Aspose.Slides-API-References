---
title: get_Title()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan judul teks dari objek Summary Zoom Section.
type: docs
weight: 1
url: /id/aspose.slides/summaryzoomsection/get_title/
---
## SummaryZoomSection::get_Title() metode


Mengembalikan judul teks dari objek Summary Zoom [Section](../../section/).

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Title() override
```

## Keterangan


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
* Kelas [SummaryZoomSection](../)
* Ruang nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)