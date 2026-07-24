---
title: get_TargetSection()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt das Abschnittsobjekt, auf das das Section Zoom-Objekt verweist. Lesen Sie ISection.
type: docs
weight: 1
url: /de/aspose.slides/sectionzoomframe/get_targetsection/
---
## SectionZoomFrame::get_TargetSection() Methode

Ermittelt das Abschnittsobjekt, auf das das [Section](../../section/) Zoom-Objekt verweist. Lesen Sie [ISection](../../isection/).

```cpp
System::SharedPtr<ISection> Aspose::Slides::SectionZoomFrame::get_TargetSection() override
```

## Hinweise

Das nächste Beispiel zeigt, wie man die Zielsektion ändert und ein neues Bild für das Section-Zoom-Objekt erstellt:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISection](../../isection/)
* Klasse [SectionZoomFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)