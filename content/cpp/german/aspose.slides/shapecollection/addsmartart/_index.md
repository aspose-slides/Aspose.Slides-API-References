---
title: AddSmartArt()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein SmartArt-Diagramm und fügt es am Ende der Shape Collection hinzu.
type: docs
weight: 79
url: /de/aspose.slides/shapecollection/addsmartart/
---
## ShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) method


Erstellt ein [SmartArt](../../../aspose.slides.smartart/) Diagramm und fügt es am Ende der Shape Collection hinzu.

```cpp
System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::ShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die x-Koordinate des Diagrammrahmens, in Punkten. |
| y | **float** | Die y-Koordinate des Diagrammrahmens, in Punkten. |
| width | **float** | Die Breite des Diagrammrahmens, in Punkten. |
| height | **float** | Die Höhe des Diagrammrahmens, in Punkten. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | Der [SmartArt](../../../aspose.slides.smartart/) Layouttyp. |

### Rückgabewert

Das neu erstellte [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/).
## Bemerkungen



```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```


## Siehe auch

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)