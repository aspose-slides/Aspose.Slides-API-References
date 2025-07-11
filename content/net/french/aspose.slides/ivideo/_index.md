---
title: IVideo
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente une vidéo intégrée dans une présentation.
type: docs
weight: 7140
url: /fr/aspose.slides/ivideo/
---

## Interface IVideo

Représente une vidéo intégrée dans une présentation.

```csharp
public interface IVideo
```

## Propriétés

| Nom | Description |
| --- | --- |
| [BinaryData](../../aspose.slides/ivideo/binarydata) { get; } | Retourne une copie des données audio. En cas de grande quantité de données, envisagez d'utiliser la méthode [`GetStream`](./getstream) pour éviter de charger inutilement les données de la vidéo en mémoire ou même de provoquer une OutOfMemoryException. Lecture seule Byte[]. |
| [ContentType](../../aspose.slides/ivideo/contenttype) { get; } | Retourne un type MIME d'une vidéo, encodé dans [`BinaryData`](./binarydata). Lecture seule String. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetStream](../../aspose.slides/ivideo/getstream)() | Retourne un flux Stream pour la lecture. Utilisez 'using' ou fermez le flux après utilisation. |

### Voir aussi

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->