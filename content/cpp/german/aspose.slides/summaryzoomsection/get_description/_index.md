---
title: get_Description()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Textbeschreibung des Summary Zoom Section-Objekts zurück.
type: docs
weight: 27
url: /de/aspose.slides/summaryzoomsection/get_description/
---
## SummaryZoomSection::get_Description() Methode

Gibt die Textbeschreibung des Summary Zoom [Section](../../section/) Objekts zurück.

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Description() override
```

## Hinweise

Beispiel: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [SummaryZoomSection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)