---
title: AddSummaryZoomSection()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein neues Summary Zoom Section-Objekt und fügt es zur Sammlung hinzu
type: docs
weight: 53
url: /de/aspose.slides/summaryzoomsectioncollection/addsummaryzoomsection/
---
## SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) Methode

Erstellt ein neues Summary Zoom [Section](../../section/)-Objekt und fügt es zur Sammlung hinzu

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) für ein neues Summary Zoom [Section](../../section/)-Element [ISection](../../isection/) |

### Rückgabewert

Hinzugefügtes [ISummaryZoomFrame](../../isummaryzoomframe/)-Element

## Bemerkungen

Wenn für diesen Abschnitt bereits ein Element in der Sammlung existiert, wird das vorhandene Element zurückgegeben.

Das Beispiel zeigt, wie man das Summary Zoom [Section](../../section/)-Element über den Index erhält:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISummaryZoomSection](../../isummaryzoomsection/)
* Klasse [ISection](../../isection/)
* Klasse [SummaryZoomSectionCollection](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)