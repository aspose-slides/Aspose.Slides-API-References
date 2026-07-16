---
title: AddAudio()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute une copie d'un fichier audio d'une autre présentation.
type: docs
weight: 14
url: /fr/aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio(System::SharedPtr\<IAudio\>) méthode

Ajoute une copie d’un fichier audio d’une autre présentation.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<IAudio> audio)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Audio source. |

### Valeur de retour

Audio ajouté.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) méthode

Crée et ajoute un audio à une présentation depuis un flux.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux à partir duquel ajouter l’audio. |

### Valeur de retour

Audio ajouté.

Obsolète
:   Utilisez AddAudio(Stream stream, LoadingStreamBehavior loadingStreamBehavior). La méthode sera supprimée dans la version 17.10.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) méthode

Crée et ajoute un audio à une présentation depuis un flux.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux à partir duquel ajouter l’audio vidéo. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Le comportement qui sera appliqué au flux. |

### Valeur de retour

Audio ajouté.

## IAudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) méthode

Crée et ajoute un audio à une présentation depuis un tableau d’octets.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) octets. |

### Valeur de retour

Audio ajouté.

## Voir aussi

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IAudio](../../iaudio/)
* Class [IAudioCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)