---
title: Video
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une image incorporée dans une présentation.
type: docs
url: /fr/com.aspose.slides/video/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject  
```
public class Video implements IVideo, IDOMObject
```

Représente une image incorporée dans une présentation.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Renvoie un type MIME d'une vidéo, encodé dans (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Renvoie une copie des données audio. |
| [getStream()](#getStream--) | Renvoie le Stream stream pour la lecture. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

Renvoie un type MIME d'une vidéo, encodé dans (\#getBinaryData.getBinaryData).  
Lecture seule String.

**Retourne:**  
java.lang.String

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Renvoie une copie des données audio. En cas de grande quantité de données, envisagez d'utiliser la méthode \#getStream.getStream pour éviter le chargement inutile des données vidéo en mémoire ou même une OutOfMemoryException. Lecture seule byte[].

**Retourne:**  
byte[]

### getStream() {#getStream--}
```
public final InputStream getStream()
```

Renvoie le Stream stream pour la lecture. Utilisez 'using' ou fermez le flux après utilisation.

**Retourne:**  
java.io.InputStream - Stream pour la lecture.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Retourne:**  
com.aspose.slides.IDOMObject