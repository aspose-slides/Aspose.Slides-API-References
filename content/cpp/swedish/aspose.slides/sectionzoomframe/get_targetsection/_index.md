---
title: get_TargetSection()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar sektionobjektet som Section Zoom-objektet länkar till. Läs ISection.
type: docs
weight: 1
url: /sv/aspose.slides/sectionzoomframe/get_targetsection/
---
## SectionZoomFrame::get_TargetSection() metod

Hämtar sektionobjektet som [Section](../../section/) Zoom-objektet länkar till. Läs [ISection](../../isection/).

```cpp
System::SharedPtr<ISection> Aspose::Slides::SectionZoomFrame::get_TargetSection() override
```

## Anmärkningar

Nästa exempel visar hur man ändrar målsektionen och skapar en ny bild för sektionzoom-objektet:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [ISection](../../isection/)
* Klass [SectionZoomFrame](../)
* Namnområde [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)