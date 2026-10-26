---
title: AddAudio()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute une copie d'un fichier audio provenant d'une autre présentation.
type: docs
weight: 53
url: /fr/aspose.slides/audiocollection/addaudio/
---
## AudioCollection::AddAudio(System::SharedPtr\<IAudio\>) méthode


Ajoute une copie d’un fichier audio provenant d’une autre présentation.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<IAudio> audio) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Audio source. |

### Valeur de retour

Audio ajouté.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) méthode


Crée et ajoute un audio à une présentation depuis un flux.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux à partir duquel ajouter l’audio. |

### Valeur de retour

Audio ajouté.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) méthode


Crée et ajoute un audio à une présentation depuis un flux.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux à partir duquel ajouter l’audio vidéo. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Le comportement qui sera appliqué au flux. |

### Valeur de retour

Audio ajouté.

## AudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) méthode


Crée et ajoute un audio à une présentation depuis un tableau d’octets.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) octets. |

### Valeur de retour

Audio ajouté.

## Voir aussi

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IAudio](../../iaudio/)
* Classe [AudioCollection](../)
* Classe [Stream](../../../system.io/stream/)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)