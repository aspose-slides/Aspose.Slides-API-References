---
title: GetSummarySection()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt das Summary Zoom Section-Element für den angegebenen Abschnitt zurück.
type: docs
weight: 27
url: /de/aspose.slides/isummaryzoomsectioncollection/getsummarysection/
---
## ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) Methode


Gibt das Summary Zoom [Section](../../section/)-Element für den angegebenen Abschnitt zurück.

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) um [ISection](../../isection/) zu finden |

### Rückgabewert

[ISummaryZoomSection](../../isummaryzoomsection/) oder null, falls die Sammlung kein Element für den Abschnitt enthält.
## Anmerkungen



Das Beispiel zeigt das Abrufen des Summary Zoom [Section](../../section/)-Elements nach Index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISummaryZoomSection](../../isummaryzoomsection/)
* Klasse [ISection](../../isection/)
* Klasse [ISummaryZoomSectionCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)