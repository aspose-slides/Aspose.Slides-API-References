---
title: IVideoCollection
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une collection d'objets Video.
type: docs
url: /fr/com.aspose.slides/ivideocollection/
---
**Toutes les interfaces implémentées :**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

Représente une collection d'objets Video.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Ajoute une copie d'un fichier vidéo d'une autre présentation. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Crée et ajoute une vidéo à une présentation à partir d'un flux. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Crée et ajoute une vidéo à une présentation à partir d'un tableau d'octets. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```


Obtient l'élément à l'index spécifié. Lecture seule [IVideo](../../com.aspose.slides/ivideo).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour :**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```


Ajoute une copie d'un fichier vidéo d'une autre présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Vidéo source. |

**Retour :**
[IVideo](../../com.aspose.slides/ivideo) - Vidéo ajoutée.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


Crée et ajoute une vidéo à une présentation à partir d'un flux.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux à partir duquel ajouter le fichier vidéo. |
| loadingStreamBehavior | int | Le comportement qui sera appliqué au flux. |

**Retour :**
[IVideo](../../com.aspose.slides/ivideo) - Ajouté [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```


Crée et ajoute une vidéo à une présentation à partir d'un tableau d'octets.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| videoData | byte[] | Octets vidéo. |

**Retour :**
[IVideo](../../com.aspose.slides/ivideo) - Vidéo ajoutée.