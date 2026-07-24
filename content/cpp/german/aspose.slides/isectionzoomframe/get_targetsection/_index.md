---
title: get_TargetSection()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt das Abschnittsobjekt, mit dem das Section Zoom-Objekt verknüpft ist. Lesen Sie ISection.
type: docs
weight: 1
url: /de/aspose.slides/isectionzoomframe/get_targetsection/
---
## ISectionZoomFrame::get_TargetSection() Methode

Ermittelt das Abschnittsobjekt, mit dem das [Section](../../section/) Zoom-Objekt verknüpft ist. Lesen Sie [ISection](../../isection/).

```cpp
virtual System::SharedPtr<ISection> Aspose::Slides::ISectionZoomFrame::get_TargetSection()=0
```

## Hinweise

Dieses Beispiel demonstriert das Ändern des Zielabschnitts und erstellt ein neues Bild für das Abschnitts-Zoom-Objekt: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISection](../../isection/)
* Klasse [ISectionZoomFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)