---
title: Video
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente une image intégrée à une présentation.
type: docs
url: /fr/com.aspose.slides/video/
---
**Héritage :**  
java.lang.Object

**Toutes les interfaces implémentées :**  
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject  
```
public class Video implements IVideo, IDOMObject
```

Représente une image intégrée à une présentation.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Renvoie un type MIME d'une vidéo, encodé dans (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Renvoie une copie des données d'un audio. |
| [getStream()](#getStream--) | Renvoie le flux Stream pour la lecture. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

Renvoie un type MIME d'une vidéo, encodé dans (\#getBinaryData.getBinaryData). Lecture seule String.

**Renvoie :**  
java.lang.String

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Renvoie une copie des données d'un audio. En cas de grande quantité de données, envisagez d'utiliser la méthode \#getStream.getStream pour éviter le chargement inutile des données de la vidéo en mémoire ou même une OutOfMemoryException. Lecture seule byte[].

**Renvoie :**  
byte[]

### getStream() {#getStream--}
```
public final InputStream getStream()
```

Renvoie le flux Stream pour la lecture. Utilisez 'using' ou fermez le flux après utilisation.

**Renvoie :**  
java.io.InputStream - Stream for reading.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**  
com.aspose.slides.IDOMObject