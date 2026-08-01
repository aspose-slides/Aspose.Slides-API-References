---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw Summary Zoom frame en voegt het toe aan de shape collectie op de opgegeven index.
type: docs
weight: 170
url: /nl/aspose.slides/shapecollection/insertsummaryzoomframe/
---
## ShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) methode

Maakt een nieuw Summary Zoom-frame en voegt het toe aan de shape-collectie op de opgegeven index.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop het Summary Zoom-frame moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe Summary Zoom-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe Summary Zoom-frame, in punten. |
| width | **float** | De breedte van het nieuwe Summary Zoom-frame, in punten. |
| height | **float** | De hoogte van het nieuwe Summary Zoom-frame, in punten. |

### Retourwaarde

De nieuw aangemaakte [ISummaryZoomFrame](../../isummaryzoomframe/).

## Opmerkingen

Deze methode maakt een Summary Zoom-frame dat samenvattingskoppelingen voor alle secties in de presentatie aggregeert. 

Dit voorbeeld toont het creëren en invoegen van een Summary Zoom-object op de opgegeven index van een collectie (neem aan dat er minstens twee secties in de "Presentation.pptx"-presentatie zijn):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISummaryZoomFrame](../../isummaryzoomframe/)
* Klasse [ShapeCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)