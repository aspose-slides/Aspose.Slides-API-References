---
title: AddSummaryZoomFrame()
second_title: Référence API Aspose.Slides pour C++
description: Crée un nouveau cadre Summary Zoom et l'ajoute à la fin de la collection de formes.
type: docs
weight: 144
url: /fr/aspose.slides/ishapecollection/addsummaryzoomframe/
---
## IShapeCollection::AddSummaryZoomFrame(float, float, float, float) méthode


Crée un nouveau cadre Summary Zoom et l’ajoute à la fin de la collection de formes.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x du nouveau cadre Summary Zoom, en points. |
| y | **float** | La coordonnée y du nouveau cadre Summary Zoom, en points. |
| width | **float** | La largeur du nouveau cadre Summary Zoom, en points. |
| height | **float** | La hauteur du nouveau cadre Summary Zoom, en points. |

### Valeur de retour

Le [ISummaryZoomFrame](../../isummaryzoomframe/) nouvellement créé.

## Remarques


Cette méthode crée un cadre Summary Zoom qui regroupe les liens de résumé pour toutes les sections de la présentation. 

Cet exemple montre comment ajouter un objet Summary Zoom à la fin d’une collection (en supposant qu’il y ait au moins deux sections dans la présentation "Presentation.pptx") : 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```


## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISummaryZoomFrame](../../isummaryzoomframe/)
* Classe [IShapeCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)