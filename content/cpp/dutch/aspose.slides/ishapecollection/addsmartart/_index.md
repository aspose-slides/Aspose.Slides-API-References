---
title: AddSmartArt()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een SmartArt-diagram en voegt het toe aan het einde van de vormverzameling.
type: docs
weight: 40
url: /nl/aspose.slides/ishapecollection/addsmartart/
---
## IShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) methode


Maakt een [SmartArt](../../../aspose.slides.smartart/) diagram en voegt deze toe aan het einde van de vormverzameling.

```cpp
virtual System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::IShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De x-coördinaat van het diagram\\u2019s frame, in punten. |
| y | **float** | De y-coördinaat van het diagram\\u2019s frame, in punten. |
| width | **float** | De breedte van het diagram\\u2019s frame, in punten. |
| height | **float** | De hoogte van het diagram\\u2019s frame, in punten. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | Het [SmartArt](../../../aspose.slides.smartart/) lay-outtype. |

### Retourwaarde

De nieuw aangemaakte [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/).
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
* Klasse [IShapeCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)