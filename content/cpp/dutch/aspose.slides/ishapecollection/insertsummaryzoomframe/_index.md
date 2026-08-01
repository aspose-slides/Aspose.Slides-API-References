---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw Summary Zoom-frame en voegt het toe aan de vormverzameling op de opgegeven index.
type: docs
weight: 157
url: /nl/aspose.slides/ishapecollection/insertsummaryzoomframe/
---
## IShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) methode

Maakt een nieuw Summary Zoom-frame en voegt het toe aan de vormverzameling op de opgegeven index.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height)=0
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

Het nieuw aangemaakte [ISummaryZoomFrame](../../isummaryzoomframe/).

## Opmerkingen

Deze methode maakt een Summary Zoom-frame dat samenvattingskoppelingen voor alle secties in de presentatie verzamelt. 

Dit voorbeeld laat zien hoe een Summary Zoom-object wordt gemaakt en ingevoegd op de opgegeven index van een verzameling (veronderstel dat er ten minste twee secties zijn in de presentatie "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISummaryZoomFrame](../../isummaryzoomframe/)
* Klasse [IShapeCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)