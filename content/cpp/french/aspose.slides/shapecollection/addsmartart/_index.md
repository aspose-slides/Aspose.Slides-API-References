---
title: AddSmartArt()
second_title: Référence API Aspose.Slides pour C++
description: Crée un diagramme SmartArt et l'ajoute à la fin de la collection de formes.
type: docs
weight: 79
url: /fr/aspose.slides/shapecollection/addsmartart/
---
## ShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) méthode


Crée un diagramme [SmartArt](../../../aspose.slides.smartart/) et l'ajoute à la fin de la collection de formes.

```cpp
System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::ShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x du cadre du diagramme, en points. |
| y | **float** | La coordonnée y du cadre du diagramme, en points. |
| width | **float** | La largeur du cadre du diagramme, en points. |
| height | **float** | La hauteur du cadre du diagramme, en points. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | Le type de mise en page [SmartArt](../../../aspose.slides.smartart/). |

### Valeur de retour

Le [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/) nouvellement créé.
## Remarques



```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```


## Voir aussi

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Classe [ShapeCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)