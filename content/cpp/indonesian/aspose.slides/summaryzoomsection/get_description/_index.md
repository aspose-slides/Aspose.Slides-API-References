---
title: get_Description()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan deskripsi teks dari objek Summary Zoom Section.
type: docs
weight: 27
url: /id/aspose.slides/summaryzoomsection/get_description/
---
## SummaryZoomSection::get_Description() metode


Mengembalikan deskripsi teks dari objek Summary Zoom [Section](../../section/).

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Description() override
```

## Catatan


Contoh: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [SummaryZoomSection](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)