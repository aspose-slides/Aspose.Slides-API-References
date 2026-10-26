---
title: set_TargetSection()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt das Abschnittsobjekt fest, auf das das Section Zoom-Objekt verweist. Schreiben Sie ISection.
type: docs
weight: 14
url: /de/aspose.slides/sectionzoomframe/set_targetsection/
---
## SectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) Methode

Legt das Abschnittsobjekt fest, auf das das [Section](../../section/) Zoom-Objekt verweist. Schreiben Sie [ISection](../../isection/).

```cpp
void Aspose::Slides::SectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value) override
```

## Anmerkungen

Das nächste Beispiel demonstriert das Ändern des Zielabschnitts und erstellt ein neues Bild für das Abschnitts-Zoom-Objekt:

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