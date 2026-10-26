---
title: IVideo
second_title: Aspose.Slides for Android via Java API Reference
description: Représente une vidéo intégrée dans une présentation.
type: docs
url: /fr/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Représente une vidéo intégrée dans une présentation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Renvoie le type MIME d'une vidéo, encodé dans (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Renvoie une copie des données d'un audio. |
| [getStream()](#getStream--) | Renvoie le flux Stream pour la lecture. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Renvoie le type MIME d'une vidéo, encodé dans (\#getBinaryData.getBinaryData). String en lecture seule.

**Retourne :**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Renvoie une copie des données d'un audio. En cas de grande quantité de données, envisagez d'utiliser la méthode \#getStream.getStream pour éviter le chargement inutile des données de la vidéo en mémoire ou même une OutOfMemoryException. byte[] en lecture seule.

**Retourne :**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Renvoie le flux Stream pour la lecture. Utilisez 'using' ou fermez le flux après utilisation.

**Retourne :**
java.io.InputStream - Flux pour la lecture.