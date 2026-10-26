---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides pour C++ Référence API
description: Crée un nouveau cadre audio avec un fichier WAV intégré et l'insère dans la collection de formes à l'index spécifié. L'audio intégré est ajouté à la collection Presentation.Audios.
type: docs
weight: 261
url: /fr/aspose.slides/ishapecollection/insertaudioframeembedded/
---
## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) méthode


Crée un nouveau cadre audio avec un fichier WAV incorporé et l’insère dans la collection de formes à l’index spécifié. L’audio incorporé est ajouté à la collection Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L’index basé sur zéro à l’endroit où insérer le cadre audio. |
| x | **float** | La coordonnée x du nouveau cadre audio, en points. |
| y | **float** | La coordonnée y du nouveau cadre audio, en points. |
| width | **float** | La largeur du nouveau cadre audio, en points. |
| height | **float** | La hauteur du nouveau cadre audio, en points. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un flux d’entrée contenant les données audio WAV à incorporer. |

### Valeur de retour

Le [IAudioFrame](../../iaudioframe/) nouvellement créé.

## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) méthode


Crée un nouveau cadre audio et l’insère dans la collection de formes à l’index spécifié en utilisant un objet audio existant de la liste Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L’index basé sur zéro à l’endroit où insérer le cadre audio. |
| x | **float** | La coordonnée x du nouveau cadre audio, en points. |
| y | **float** | La coordonnée y du nouveau cadre audio, en points. |
| width | **float** | La largeur du nouveau cadre audio, en points. |
| height | **float** | La hauteur du nouveau cadre audio, en points. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Une instance [IAudio](../../iaudio/) de la collection Presentation.Audios à incorporer. |

### Valeur de retour

Le [IAudioFrame](../../iaudioframe/) nouvellement créé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAudioFrame](../../iaudioframe/)
* Classe [Stream](../../../system.io/stream/)
* Classe [IShapeCollection](../)
* Classe [IAudio](../../iaudio/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)