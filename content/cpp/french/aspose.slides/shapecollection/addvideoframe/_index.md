---
title: AddVideoFrame()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une nouvelle image vidéo et l'ajoute à la fin de la collection de formes.
type: docs
weight: 209
url: /fr/aspose.slides/shapecollection/addvideoframe/
---
## ShapeCollection::AddVideoFrame(float, float, float, float, System::String) méthode

Crée une nouvelle image video et l'ajoute à la fin de la collection de formes.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x de la nouvelle image video, en points. |
| y | **float** | La coordonnée y de la nouvelle image video, en points. |
| width | **float** | La largeur de la nouvelle image video, en points. |
| height | **float** | La hauteur de la nouvelle image video, en points. |
| fname | [System::String](../../../system/string/) | Le chemin ou le nom du fichier video à intégrer. |

### Valeur de retour

Le [IVideoFrame](../../ivideoframe/) nouvellement créé.

## ShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) méthode

Crée une nouvelle image video et l'ajoute à la fin de la collection de formes.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x de la nouvelle image video, en points. |
| y | **float** | La coordonnée y de la nouvelle image video, en points. |
| width | **float** | La largeur de la nouvelle image video, en points. |
| height | **float** | La hauteur de la nouvelle image video, en points. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Le [IVideo](../../ivideo/) à intégrer dans l'image video. |

### Valeur de retour

Le [IVideoFrame](../../ivideoframe/) nouvellement créé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IVideoFrame](../../ivideoframe/)
* Classe [String](../../../system/string/)
* Classe [ShapeCollection](../)
* Classe [IVideo](../../ivideo/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)