---
title: IAudio
second_title: Aspose.Slides pour Java Référence de l'API
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
| [getContentType()](#getContentType--) | Renvoie le type MIME d'un audio, encodé dans (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Renvoie une copie des données d'un audio. |
| [getStream()](#getStream--) | Renvoie un flux Stream pour la lecture. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Renvoie le type MIME d'un audio, encodé dans (\#getBinaryData.getBinaryData). Chaîne en lecture seule.

**Renvoie :**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Renvoie une copie des données d'un audio. En cas de grande quantité de données, envisagez d'utiliser la méthode \#getStream.getStream pour éviter le chargement inutile des données audio en mémoire ou même une OutOfMemoryException. Byte[] en lecture seule.

**Renvoie :**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Renvoie un flux Stream pour la lecture. Utilisez 'using' ou fermez le flux après utilisation.

**Renvoie :**
java.io.InputStream - Flux pour la lecture.