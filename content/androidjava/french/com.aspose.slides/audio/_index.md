---
title: Audio
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente un fichier audio intégré.
type: docs
url: /fr/com.aspose.slides/audio/
---
**Héritage :**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées :**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

Représente un fichier audio intégré.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Renvoie un type MIME d'un audio, encodé dans (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | Renvoie un type MIME d'un audio, encodé dans (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Renvoie une copie des données d'un audio. |
| [getStream()](#getStream--) | Renvoie le flux Stream pour la lecture. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Renvoie un type MIME d'un audio, encodé dans (\#getBinaryData.getBinaryData). Lecture seule String.

**Renvoie :**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Renvoie un type MIME d'un audio, encodé dans (\#getBinaryData.getBinaryData). Lecture seule String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Renvoie une copie des données d'un audio. En cas de grande quantité de données, envisagez d'utiliser la méthode \#getStream.getStream afin d'éviter le chargement inutile des données audio en mémoire ou même une OutOfMemoryException. Lecture seule byte[].

**Renvoie :**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Renvoie le flux Stream pour la lecture. Utilisez 'using' ou fermez le flux après utilisation.

**Renvoie :**
java.io.InputStream - Stream pour la lecture.