---
title: AddSmartArt()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un diagramme SmartArt et l'ajoute à la fin de la collection de formes.
type: docs
weight: 40
url: /fr/aspose.slides/ishapecollection/addsmartart/
---
## IShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) méthode

Crée un diagramme [SmartArt](../../../aspose.slides.smartart/) et l'ajoute à la fin de la collection de formes.

```cpp
virtual System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::IShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x du cadre du diagramme, en points. |
| y | **float** | La coordonnée y du cadre du diagramme, en points. |
| width | **float** | La largeur du cadre du diagramme, en points. |
| height | **float** | La hauteur du cadre du diagramme, en points. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | Le type de mise en page [SmartArt](../../../aspose.slides.smartart/). |

### Return Value

Le [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/) nouvellement créé.

## Remarks

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```

## See Also

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)