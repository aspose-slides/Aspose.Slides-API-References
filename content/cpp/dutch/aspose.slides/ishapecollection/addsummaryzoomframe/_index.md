---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw Summary Zoom-frame en voegt het toe aan het einde van de shape-collectie.
type: docs
weight: 144
url: /nl/aspose.slides/ishapecollection/addsummaryzoomframe/
---
## IShapeCollection::AddSummaryZoomFrame(float, float, float, float) methode


Maakt een nieuw Summary Zoom frame en voegt het toe aan het einde van de shape collection.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De x-coördinaat van het nieuwe Summary Zoom frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe Summary Zoom frame, in punten. |
| width | **float** | De breedte van het nieuwe Summary Zoom frame, in punten. |
| height | **float** | De hoogte van het nieuwe Summary Zoom frame, in punten. |

### Retourwaarde

De nieuw aangemaakte [ISummaryZoomFrame](../../isummaryzoomframe/).
## Opmerkingen


Deze methode maakt een Summary Zoom frame dat samenvattingskoppelingen voor alle secties in de presentatie aggregeert. 

Dit voorbeeld demonstreert het toevoegen van een Summary Zoom object aan het einde van een verzameling (ga er vanuit dat er minstens twee secties in de "Presentation.pptx" presentatie zijn): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```


## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISummaryZoomFrame](../../isummaryzoomframe/)
* Klasse [IShapeCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)