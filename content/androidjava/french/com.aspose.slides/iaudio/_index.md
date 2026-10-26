---
title: IAudio
second_title: Aspose.Slides pour Android via la Référence de l'API Java
description: Représente un fichier audio intégré.
type: docs
url: /fr/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Représente un fichier audio intégré.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Renvoie un type MIME d'un audio, encodé dans (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Renvoie la copie des données d'un audio. |
| [getStream()](#getStream--) | Renvoie Stream stream pour la lecture. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Renvoie un type MIME d'un audio, encodé dans (\#getBinaryData.getBinaryData). String en lecture seule.

**Renvoie :**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Renvoie la copie des données d'un audio. En cas de grande quantité de données, envisagez d'utiliser la méthode \#getStream.getStream pour éviter le chargement inutile des données de l'audio en mémoire ou même une OutOfMemoryException. Lecture seule byte[].

**Renvoie :**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Renvoie Stream stream pour la lecture. Utilisez 'using' ou fermez le flux après utilisation.

**Renvoie :**
java.io.InputStream - Flux pour la lecture.