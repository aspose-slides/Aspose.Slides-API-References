---
title: AddSmartArt()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein SmartArt-Diagramm und fügt es am Ende der Formensammlung hinzu.
type: docs
weight: 40
url: /de/aspose.slides/ishapecollection/addsmartart/
---
## IShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) method


Erstellt ein [SmartArt](../../../aspose.slides.smartart/) Diagramm und fügt es am Ende der shape collection hinzu.

```cpp
virtual System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::IShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType)=0
```


### Argumente

| Parameter | Type | Description |
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
* Klasse [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Klasse [IShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)