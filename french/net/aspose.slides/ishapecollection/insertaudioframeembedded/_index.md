---
title: InsertAudioFrameEmbedded
second_title: Référence de l'API Aspose.Slides pour .NET
description: Insérez un AudioFrame avec un fichier audio intégré. Le son du fichier audio intégré ne peut être quun WAV. Il ajoute un nouvel audio dans la liste Presentation.Audios.
type: docs
weight: 230
url: /fr/net/aspose.slides/ishapecollection/insertaudioframeembedded/
---
## InsertAudioFrameEmbedded(int, float, float, float, float, Stream) {#insertaudioframeembedded_1}

Insérez un AudioFrame avec un fichier audio intégré. Le son du fichier audio intégré ne peut être qu'un WAV. Il ajoute un nouvel audio dans la liste Presentation.Audios.

```csharp
public IAudioFrame InsertAudioFrameEmbedded(int index, float x, float y, float width, float height, 
    Stream audio_stream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| index | Int32 | Index de base zéro auquel la valeur doit être insérée. |
| x | Single | Coordonnée X d'une nouvelle image audio. |
| y | Single | Coordonnée Y d'une nouvelle trame audio. |
| width | Single | Largeur d'une nouvelle trame audio. |
| height | Single | Hauteur d'une nouvelle trame audio. |
| audio_stream | Stream | Flux audio. |

### Return_Value

Objet AudioFrame créé.

### Voir également

* interface [IAudioFrame](../../iaudioframe)
* interface [IShapeCollection](../../ishapecollection)
* espace de noms [Aspose.Slides](../../ishapecollection)
* Assemblée [Aspose.Slides](../../../)

---

## InsertAudioFrameEmbedded(int, float, float, float, float, IAudio) {#insertaudioframeembedded}

Insérez un AudioFrame avec un fichier audio intégré. Il utilise un fichier audio de Presentation.Audios list.

```csharp
public IAudioFrame InsertAudioFrameEmbedded(int index, float x, float y, float width, float height, 
    IAudio audio)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| index | Int32 | Index de base zéro auquel la valeur doit être insérée. |
| x | Single | Coordonnée X d'une nouvelle image audio. |
| y | Single | Coordonnée Y d'une nouvelle trame audio. |
| width | Single | Largeur d'une nouvelle trame audio. |
| height | Single | Hauteur d'une nouvelle trame audio. |
| audio | IAudio | Audio de la liste Presentation.Audios. |

### Return_Value

Objet AudioFrame créé.

### Voir également

* interface [IAudioFrame](../../iaudioframe)
* interface [IAudio](../../iaudio)
* interface [IShapeCollection](../../ishapecollection)
* espace de noms [Aspose.Slides](../../ishapecollection)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->