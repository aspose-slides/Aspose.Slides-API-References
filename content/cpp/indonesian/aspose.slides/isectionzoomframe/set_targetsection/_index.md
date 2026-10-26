---
title: set_TargetSection()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur objek bagian yang terhubung dengan objek Section Zoom. Tulis ISection.
type: docs
weight: 14
url: /id/aspose.slides/isectionzoomframe/set_targetsection/
---
## ISectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) metode

Mengatur objek bagian yang dihubungkan dengan objek Zoom [Section](../../section/). Tulis [ISection](../../isection/).

```cpp
virtual void Aspose::Slides::ISectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value)=0
```

## Keterangan

Contoh ini menunjukkan perubahan bagian target dan membuat gambar baru untuk objek zoom bagian:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISection](../../isection/)
* Kelas [ISectionZoomFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)