---
title: InsertAudioFrameLinked()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une nouvelle trame audio liée à un fichier audio externe et l'insère dans la collection de formes à l'index spécifié.
type: docs
weight: 235
url: /fr/aspose.slides/ishapecollection/insertaudioframelinked/
---
## IShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) méthode

Crée une nouvelle trame audio liée à un fichier audio externe et l'insère dans la collection de formes à l'indice spécifié.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'indice zéro basé où insérer la trame audio. |
| x | **float** | La coordonnée x de la nouvelle trame audio, en points. |
| y | **float** | La coordonnée y de la nouvelle trame audio, en points. |
| width | **float** | La largeur de la nouvelle trame audio, en points. |
| height | **float** | La hauteur de la nouvelle trame audio, en points. |
| fname | [System::String](../../../system/string/) | Le chemin ou le nom du fichier audio externe à lier. |

### Valeur de retour

Le [IAudioFrame](../../iaudioframe/) nouvellement créé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAudioFrame](../../iaudioframe/)
* Classe [String](../../../system/string/)
* Classe [IShapeCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)