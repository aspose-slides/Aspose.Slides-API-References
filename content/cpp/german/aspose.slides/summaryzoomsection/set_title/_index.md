---
title: set_Title()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Texttitel des Summary Zoom Section-Objekts zurück.
type: docs
weight: 14
url: /de/aspose.slides/summaryzoomsection/set_title/
---
## SummaryZoomSection::set_Title(System::String) Methode


Gibt den Texttitel des Summary Zoom [Section](../../section/) Objekts zurück.

```cpp
void Aspose::Slides::SummaryZoomSection::set_Title(System::String value) override
```

## Hinweise


Beispiel:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [SummaryZoomSection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)