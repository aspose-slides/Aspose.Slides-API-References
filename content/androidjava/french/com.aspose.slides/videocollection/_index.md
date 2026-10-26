---
title: VideoCollection
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une collection d'objets Video.
type: docs
url: /fr/com.aspose.slides/videocollection/
---
**Héritage:**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

Représente une collection d'objets Video.
## Méthodes

| Méthode | Description |
| --- | --- |
| [size()](#size--) | Renvoie le nombre de fichiers vidéo dans la collection. |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Ajoute une copie d'un fichier vidéo provenant d'une autre présentation. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Crée et ajoute une vidéo à une présentation à partir d'un flux. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Crée et ajoute une vidéo à une présentation à partir d'un tableau d'octets. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie les vidéos dans le tableau spécifié à partir de l'index indiqué. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie la racine de synchronisation. |
| [iterator()](#iterator--) | Renvoie un itérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
### size() {#size--}
```
public final int size()
```

Renvoie le nombre de fichiers vidéo dans la collection. Lecture seule int.

**Renvoie:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```

Obtient l'élément à l'index spécifié. Lecture seule [IVideo](../../com.aspose.slides/ivideo).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```

Ajoute une copie d'un fichier vidéo provenant d'une autre présentation.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Vidéo source. |

**Renvoie:**
[IVideo](../../com.aspose.slides/ivideo) - Vidéo ajoutée.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

Crée et ajoute une vidéo à une présentation à partir d'un flux.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux à partir duquel ajouter le fichier vidéo. |
| loadingStreamBehavior | int | Le comportement qui sera appliqué au flux. |

**Renvoie:**
[IVideo](../../com.aspose.slides/ivideo) - Ajouté [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

Crée et ajoute une vidéo à une présentation à partir d'un tableau d'octets.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| videoData | byte[] | Octets vidéo. |

**Renvoie:**
[IVideo](../../com.aspose.slides/ivideo) - Vidéo ajoutée.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copie les vidéos dans le tableau spécifié à partir de l'index indiqué.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tableau. |
| index | int | Index. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule boolean.

**Renvoie:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Renvoie la racine de synchronisation. Lecture seule Object.

**Renvoie:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```

Renvoie un itérateur qui parcourt la collection.

**Renvoie:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Un IGenericEnumerator qui peut être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```

Renvoie un itérateur java pour l'ensemble de la collection.

**Renvoie:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Un java.util.Iterator pour l'ensemble de la collection.