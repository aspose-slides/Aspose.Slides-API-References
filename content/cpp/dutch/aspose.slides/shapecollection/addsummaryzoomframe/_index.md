---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw Summary Zoom-frame en voegt het toe aan het einde van de shape-collectie.
type: docs
weight: 157
url: /nl/aspose.slides/shapecollection/addsummaryzoomframe/
---
## ShapeCollection::AddSummaryZoomFrame(float, float, float, float) methode

Maakt een nieuw Summary Zoom-frame en voegt het toe aan het einde van de shape-collectie.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De x-coördinaat van het nieuwe Summary Zoom-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe Summary Zoom-frame, in punten. |
| width | **float** | De breedte van het nieuwe Summary Zoom-frame, in punten. |
| height | **float** | De hoogte van het nieuwe Summary Zoom-frame, in punten. |

### Retourwaarde

De nieuw aangemaakte [ISummaryZoomFrame](../../isummaryzoomframe/).

## Opmerkingen

Deze methode maakt een nieuwe Summary Zoom aan en plaatst er een verzameling objecten in voor alle secties in deze presentatie. 

Dit voorbeeld toont het toevoegen van een Summary Zoom-object aan het einde van een collectie (ga uit van ten minste twee secties in de presentatie "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISummaryZoomFrame](../../isummaryzoomframe/)
* Klasse [ShapeCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)