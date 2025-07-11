---
title: AudioCollection
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente une collection de fichiers audio intégrés.
type: docs
weight: 780
url: /fr/aspose.slides/audiocollection/
---

## AudioCollection class

Représente une collection de fichiers audio intégrés.

```csharp
public class AudioCollection : DomObject<Presentation>, IAudioCollection
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Count](../../aspose.slides/audiocollection/count) { get; } | Retourne le nombre de fichiers audio dans la collection. Lecture seule Int32. |
| [IsSynchronized](../../aspose.slides/audiocollection/issynchronized) { get; } | Retourne une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule Boolean. |
| [Item](../../aspose.slides/audiocollection/item) { get; } | Obtient l'élément à l'index spécifié. Lecture seule [`IAudio`](../iaudio). |
| [SyncRoot](../../aspose.slides/audiocollection/syncroot) { get; } | Retourne une racine de synchronisation. Lecture seule Object. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddAudio](../../aspose.slides/audiocollection/addaudio#addaudio_1)(byte[]) | Crée et ajoute un audio à une présentation à partir d'un tableau d'octets. |
| [AddAudio](../../aspose.slides/audiocollection/addaudio#addaudio)(IAudio) | Ajoute une copie d'un fichier audio d'une autre présentation. |
| [AddAudio](../../aspose.slides/audiocollection/addaudio#addaudio_2)(Stream) | Crée et ajoute un audio à une présentation à partir d'un flux. |
| [AddAudio](../../aspose.slides/audiocollection/addaudio#addaudio_3)(Stream, LoadingStreamBehavior) | Crée et ajoute un audio à une présentation à partir d'un flux. |
| [CopyTo](../../aspose.slides/audiocollection/copyto)(Array, int) | Copie des audios dans le tableau spécifié en commençant à partir de l'index spécifié. |
| [GetEnumerator](../../aspose.slides/audiocollection/getenumerator)() | Retourne un énumérateur qui itère à travers la collection. |

### Voir Aussi

* classe [DomObject&lt;TParent&gt;](../domobject-1)
* classe [Presentation](../presentation)
* interface [IAudioCollection](../iaudiocollection)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->