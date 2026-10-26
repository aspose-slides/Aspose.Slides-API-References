---
title: Audio
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un fichier audio intégré.
type: docs
url: /fr/com.aspose.slides/audio/
---
**Héritage:**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

Représente un fichier audio intégré.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Returns a MIME type of an audio, encoded in (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | Returns a MIME type of an audio, encoded in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Returns the copy of an audio's data. |
| [getStream()](#getStream--) | Returns Stream stream for reading. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Renvoie un type MIME d'un audio, encodé dans (\#getBinaryData.getBinaryData). Lecture seule String.

**Retour**:
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Renvoie un type MIME d'un audio, encodé dans (\#getBinaryData.getBinaryData). Lecture seule String.

**Paramètres**:
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Renvoie une copie des données d'un audio. En cas de grande quantité de données, envisagez d'utiliser la méthode \#getStream.getStream pour éviter le chargement inutile des données audio en mémoire ou même une OutOfMemoryException. Lecture seule byte[].

**Retour**:
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Renvoie un flux Stream pour la lecture. Utilisez 'using' ou fermez le flux après utilisation.

**Retour**:
java.io.InputStream - Flux pour la lecture.