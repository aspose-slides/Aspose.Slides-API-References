---
title: get_TargetSection()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan objek bagian yang terhubung ke objek Section Zoom. Baca ISection.
type: docs
weight: 1
url: /id/aspose.slides/isectionzoomframe/get_targetsection/
---
## ISectionZoomFrame::get_TargetSection() method


Mendapatkan objek bagian yang terhubung ke objek Zoom [Section](../../section/). Baca [ISection](../../isection/).

```cpp
virtual System::SharedPtr<ISection> Aspose::Slides::ISectionZoomFrame::get_TargetSection()=0
```

## Remarks


Contoh ini memperlihatkan perubahan bagian target dan membuat gambar baru untuk objek zoom bagian:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISection](../../isection/)
* Class [ISectionZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)