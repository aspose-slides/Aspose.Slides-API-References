---
title: set_TargetSection()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur objek section yang ditautkan oleh objek Section Zoom. Tulis ISection.
type: docs
weight: 14
url: /id/aspose.slides/sectionzoomframe/set_targetsection/
---
## SectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) metode


Mengatur objek section yang ditautkan oleh objek [Section](../../section/) Zoom. Tulis [ISection](../../isection/).

```cpp
void Aspose::Slides::SectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value) override
```

## Keterangan


Contoh berikut mendemonstrasikan mengubah section target dan membuat gambar baru untuk objek zoom section: 
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