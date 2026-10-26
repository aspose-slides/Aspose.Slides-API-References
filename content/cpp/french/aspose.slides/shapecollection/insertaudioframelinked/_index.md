---
title: InsertAudioFrameLinked()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un nouveau cadre audio lié à un fichier audio externe et l'insère dans la collection de formes à l'index spécifié.
type: docs
weight: 274
url: /fr/aspose.slides/shapecollection/insertaudioframelinked/
---
## ShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) méthode

Crée un nouveau cadre audio lié à un fichier audio externe et l'insère dans la collection de formes à l'index spécifié.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'index basé sur zéro où insérer le cadre audio. |
| x | **float** | La coordonnée x du nouveau cadre audio, en points. |
| y | **float** | La coordonnée y du nouveau cadre audio, en points. |
| width | **float** | La largeur du nouveau cadre audio, en points. |
| height | **float** | La hauteur du nouveau cadre audio, en points. |
| fname | [System::String](../../../system/string/) | Le chemin ou le nom du fichier audio externe à lier. |

### Valeur de retour

Le [IAudioFrame](../../iaudioframe/) nouvellement créé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAudioFrame](../../iaudioframe/)
* Classe [String](../../../system/string/)
* Classe [ShapeCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)