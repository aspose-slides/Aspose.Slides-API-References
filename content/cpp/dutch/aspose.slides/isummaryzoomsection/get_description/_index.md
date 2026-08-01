---
title: get_Description()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de tekstbeschrijving van het Summary Zoom Section object.
type: docs
weight: 27
url: /nl/aspose.slides/isummaryzoomsection/get_description/
---
## ISummaryZoomSection::get_Description() methode


Retourneert de tekstbeschrijving van het Summary Zoom [Section](../../section/) object.

```cpp
virtual System::String Aspose::Slides::ISummaryZoomSection::get_Description()=0
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
* Klasse [ISummaryZoomSection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)