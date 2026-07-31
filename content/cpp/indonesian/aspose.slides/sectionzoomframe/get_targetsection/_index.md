---
title: get_TargetSection()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan objek bagian yang ditautkan oleh objek Section Zoom. Baca ISection.
type: docs
weight: 1
url: /id/aspose.slides/sectionzoomframe/get_targetsection/
---
## SectionZoomFrame::get_TargetSection() metode


Mendapatkan objek bagian yang ditautkan oleh objek Zoom [Section](../../section/). Baca [ISection](../../isection/).

```cpp
System::SharedPtr<ISection> Aspose::Slides::SectionZoomFrame::get_TargetSection() override
```

## Catatan


Contoh berikut menunjukkan cara mengubah bagian target dan membuat gambar baru untuk objek zoom bagian: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISection](../../isection/)
* Kelas [SectionZoomFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)