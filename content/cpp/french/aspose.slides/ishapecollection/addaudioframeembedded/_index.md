---
title: AddAudioFrameEmbedded()
second_title: Référence API Aspose.Slides pour C++
description: Crée un nouveau cadre audio avec un fichier WAV intégré et l’ajoute à la fin de la collection de formes. L’audio intégré est ajouté à la collection Presentation.Audios.
type: docs
weight: 248
url: /fr/aspose.slides/ishapecollection/addaudioframeembedded/
---
## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) méthode


Crée un nouveau cadre audio avec un fichier WAV incorporé et l’ajoute à la fin de la collection de formes. L’audio incorporé est ajouté à la collection Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x du nouveau cadre audio, en points. |
| y | **float** | La coordonnée y du nouveau cadre audio, en points. |
| width | **float** | La largeur du nouveau cadre audio, en points. |
| height | **float** | La hauteur du nouveau cadre audio, en points. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un flux d’entrée contenant les données audio WAV à incorporer. |

### Valeur de retour

Le [IAudioFrame](../../iaudioframe/) nouvellement créé.

## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) méthode


Crée un nouveau cadre audio et l’ajoute à la fin de la collection de formes en utilisant un objet audio existant de la liste Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x du nouveau cadre audio, en points. |
| y | **float** | La coordonnée y du nouveau cadre audio, en points. |
| width | **float** | La largeur du nouveau cadre audio, en points. |
| height | **float** | La hauteur du nouveau cadre audio, en points. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Une instance [IAudio](../../iaudio/) provenant de la collection Presentation.Audios. |

### Valeur de retour

Le [IAudioFrame](../../iaudioframe/) nouvellement créé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAudioFrame](../../iaudioframe/)
* Classe [Stream](../../../system.io/stream/)
* Classe [IShapeCollection](../)
* Classe [IAudio](../../iaudio/)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)