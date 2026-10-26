---
title: set_Description()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengembalikan deskripsi teks dari objek Summary Zoom Section.
type: docs
weight: 40
url: /id/aspose.slides/summaryzoomsection/set_description/
---
## SummaryZoomSection::set_Description(System::String) metode

Mengembalikan deskripsi teks dari objek Summary Zoom [Section](../../section/).

```cpp
void Aspose::Slides::SummaryZoomSection::set_Description(System::String value) override
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
* Pustaka [Aspose.Slides](../../../)