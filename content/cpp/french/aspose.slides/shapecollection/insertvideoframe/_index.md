---
title: InsertVideoFrame()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un nouveau cadre vidéo et l'insère dans la collection de formes à l'index spécifié.
type: docs
weight: 222
url: /fr/aspose.slides/shapecollection/insertvideoframe/
---
## ShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) méthode


Crée un nouveau cadre vidéo et l'insère dans la collection de formes à l'index spécifié.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'index basé à zéro où insérer le cadre vidéo. |
| x | **float** | La coordonnée x du nouveau cadre vidéo, en points. |
| y | **float** | La coordonnée y du nouveau cadre vidéo, en points. |
| width | **float** | La largeur du nouveau cadre vidéo, en points. |
| height | **float** | La hauteur du nouveau cadre vidéo, en points. |
| fname | [System::String](../../../system/string/) | Le chemin ou le nom du fichier vidéo à incorporer. |

### Valeur retournée

Le [IVideoFrame](../../ivideoframe/) nouvellement créé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IVideoFrame](../../ivideoframe/)
* Classe [String](../../../system/string/)
* Classe [ShapeCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)