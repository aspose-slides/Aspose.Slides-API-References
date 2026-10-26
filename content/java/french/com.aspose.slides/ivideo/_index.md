---
title: IVideo
second_title: Aspose.Slides for Java API Reference
description: Représente une vidéo intégrée à une présentation.
type: docs
url: /fr/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Représente une vidéo intégrée à une présentation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Renvoie un type MIME d'une vidéo, encodé dans (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Renvoie une copie des données audio. |
| [getStream()](#getStream--) | Renvoie un flux Stream pour la lecture. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Renvoie un type MIME d'une vidéo, encodé dans (\#getBinaryData.getBinaryData). Lecture seule String.

**Retourne :**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Renvoie une copie des données audio. En cas de grande quantité de données, envisagez d'utiliser la méthode \#getStream.getStream pour éviter de charger inutilement les données de la vidéo en mémoire ou même de provoquer une OutOfMemoryException. Lecture seule byte[].

**Retourne :**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Renvoie un flux Stream pour la lecture. Utilisez 'using' ou fermez le flux après utilisation.

**Retourne :**
java.io.InputStream - Stream pour la lecture.