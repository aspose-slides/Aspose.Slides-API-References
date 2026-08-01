---
title: AddSmartArt()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een SmartArt-diagram en voegt het toe aan het einde van de vormverzameling.
type: docs
weight: 79
url: /nl/aspose.slides/shapecollection/addsmartart/
---
## ShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) methode

Maakt een [SmartArt](../../../aspose.slides.smartart/) diagram en voegt het toe aan het einde van de vormverzameling.

```cpp
System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::ShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De x-coördinaat van het diagramframe, in punten. |
| y | **float** | De y-coördinaat van het diagramframe, in punten. |
| width | **float** | De breedte van het diagramframe, in punten. |
| height | **float** | De hoogte van het diagramframe, in punten. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | Het [SmartArt](../../../aspose.slides.smartart/) lay-outtype. |

### Retourwaarde

Het nieuw aangemaakte [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/).

## Opmerkingen



```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```

## Zie ook

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Klasse [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)