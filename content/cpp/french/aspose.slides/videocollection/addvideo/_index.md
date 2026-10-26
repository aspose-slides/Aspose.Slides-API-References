---
title: AddVideo()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute une copie d'un fichier vidéo depuis une autre présentation.
type: docs
weight: 53
url: /fr/aspose.slides/videocollection/addvideo/
---
## VideoCollection::AddVideo(System::SharedPtr\<IVideo\>) méthode

Ajoute une copie d'un fichier vidéo depuis une autre présentation.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<IVideo> video) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Vidéo source. |

### Valeur de retour

Vidéo ajoutée.

## VideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) méthode

Crée et ajoute une vidéo à une présentation depuis un flux.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux à partir duquel ajouter le fichier vidéo. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Le comportement qui sera appliqué au flux. |

### Valeur de retour

Ajouté [IVideo](../../ivideo/).

## VideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) méthode

Crée et ajoute une vidéo à une présentation depuis un tableau d'octets.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) octets. |

### Valeur de retour

Vidéo ajoutée.

## Voir aussi

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IVideo](../../ivideo/)
* Classe [VideoCollection](../)
* Classe [Stream](../../../system.io/stream/)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)