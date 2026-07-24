---
title: set_TargetSection()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt das Abschnittsobjekt fest, mit dem das Section Zoom-Objekt verknüpft ist. Schreiben Sie ISection.
type: docs
weight: 14
url: /de/aspose.slides/isectionzoomframe/set_targetsection/
---
## ISectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) Methode

Legt das Abschnittsobjekt fest, mit dem das [Section](../../section/) Zoom-Objekt verknüpft ist. Schreiben Sie [ISection](../../isection/).

```cpp
virtual void Aspose::Slides::ISectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value)=0
```

## Hinweise

Dieses Beispiel zeigt, wie das Zielabschnitt geändert wird und erstellt ein neues Bild für das Abschnittszoom-Objekt: ```cpp
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
* Library [Aspose.Slides](../../../)