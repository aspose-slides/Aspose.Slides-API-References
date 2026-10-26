---
title: AddVideoFrame()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une nouvelle trame vidéo et l'ajoute à la fin de la collection de formes.
type: docs
weight: 170
url: /fr/aspose.slides/ishapecollection/addvideoframe/
---
## IShapeCollection::AddVideoFrame(float, float, float, float, System::String) méthode

Crée une nouvelle trame vidéo et l’ajoute à la fin de la collection de formes.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x de la nouvelle trame vidéo, en points. |
| y | **float** | La coordonnée y de la nouvelle trame vidéo, en points. |
| width | **float** | La largeur de la nouvelle trame vidéo, en points. |
| height | **float** | La hauteur de la nouvelle trame vidéo, en points. |
| fname | [System::String](../../../system/string/) | Le chemin ou le nom du fichier vidéo à incorporer. |

### Valeur de retour

Le [IVideoFrame](../../ivideoframe/) nouvellement créé.

## IShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) méthode

Crée une nouvelle trame vidéo et l’ajoute à la fin de la collection de formes.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x de la nouvelle trame vidéo, en points. |
| y | **float** | La coordonnée y de la nouvelle trame vidéo, en points. |
| width | **float** | La largeur de la nouvelle trame vidéo, en points. |
| height | **float** | La hauteur de la nouvelle trame vidéo, en points. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Le [IVideo](../../ivideo/) à incorporer dans la trame vidéo. |

### Valeur de retour

Le [IVideoFrame](../../ivideoframe/) nouvellement créé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IVideoFrame](../../ivideoframe/)
* Classe [String](../../../system/string/)
* Classe [IShapeCollection](../)
* Classe [IVideo](../../ivideo/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)