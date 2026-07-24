---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt das Summary Zoom Section-Objekt aus der Sammlung.
type: docs
weight: 40
url: /de/aspose.slides/isummaryzoomsectioncollection/removesummaryzoomsection/
---
## ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) Methode

Entfernt das Summary Zoom [Section](../../section/) Objekt aus der Sammlung.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) für das das Summary Zoom [Section](../../section/) Element entfernt werden soll [ISection](../../isection/). |
## Bemerkungen



Das Beispiel zeigt das Abrufen des Summary Zoom [Section](../../section/) Elements nach Index:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISection](../../isection/)
* Klasse [ISummaryZoomSectionCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)