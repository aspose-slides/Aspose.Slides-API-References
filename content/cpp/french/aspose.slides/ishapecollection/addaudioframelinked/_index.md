---
title: AddAudioFrameLinked()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une nouvelle trame audio liée à un fichier audio externe et l'ajoute à la fin de la collection de formes.
type: docs
weight: 222
url: /fr/aspose.slides/ishapecollection/addaudioframelinked/
---
## IShapeCollection::AddAudioFrameLinked(float, float, float, float, System::String) method


Crée une nouvelle trame audio liée à un fichier audio externe et l'ajoute à la fin de la collection de formes.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameLinked(float x, float y, float width, float height, System::String fname)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x de la nouvelle trame audio, en points. |
| y | **float** | La coordonnée y de la nouvelle trame audio, en points. |
| width | **float** | La largeur de la nouvelle trame audio, en points. |
| height | **float** | La hauteur de la nouvelle trame audio, en points. |
| fname | [System::String](../../../system/string/) | Le chemin ou le nom du fichier audio externe à lier. |

### Return Value

Le [IAudioFrame](../../iaudioframe/) nouvellement créé.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAudioFrame](../../iaudioframe/)
* Classe [String](../../../system/string/)
* Classe [IShapeCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)