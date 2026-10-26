---
title: set_Description()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de tekstbeschrijving van het Summary Zoom Section-object.
type: docs
weight: 40
url: /nl/aspose.slides/summaryzoomsection/set_description/
---
## SummaryZoomSection::set_Description(System::String) methode


Retourneert de tekstbeschrijving van het Summary Zoom [Section](../../section/) object.

```cpp
void Aspose::Slides::SummaryZoomSection::set_Description(System::String value) override
```

## Opmerkingen


Voorbeeld:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [SummaryZoomSection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)