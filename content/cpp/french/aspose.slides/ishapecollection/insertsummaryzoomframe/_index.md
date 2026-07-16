---
title: InsertSummaryZoomFrame()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un nouveau cadre Summary Zoom et l'insère dans la collection de formes à l'indice spécifié.
type: docs
weight: 157
url: /fr/aspose.slides/ishapecollection/insertsummaryzoomframe/
---
## IShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) method

Crée un nouveau cadre Summary Zoom et l’insère dans la collection de formes à l’indice spécifié.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L’indice basé sur zéro à laquelle insérer le cadre Summary Zoom. |
| x | **float** | La coordonnée x du nouveau cadre Summary Zoom, en points. |
| y | **float** | La coordonnée y du nouveau cadre Summary Zoom, en points. |
| width | **float** | La largeur du nouveau cadre Summary Zoom, en points. |
| height | **float** | La hauteur du nouveau cadre Summary Zoom, en points. |

### Valeur de retour

Le [ISummaryZoomFrame](../../isummaryzoomframe/) nouvellement créé.

## Remarques

Cette méthode crée un cadre Summary Zoom qui agrège les liens de résumé pour toutes les sections de la présentation. 

Cet exemple montre la création et l’insertion d’un objet Summary Zoom à l’indice spécifié d’une collection (en supposant qu’il y ait au moins deux sections dans la présentation "Presentation.pptx") : 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISummaryZoomFrame](../../isummaryzoomframe/)
* Classe [IShapeCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)