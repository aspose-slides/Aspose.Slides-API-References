---
title: IAudioCollection
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente une collection de fichiers audio intégrés.
type: docs
url: /fr/com.aspose.slides/iaudiocollection/
---
**Toutes les interfaces implémentées :**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

Représente une collection de fichiers audio intégrés.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Ajoute une copie d'un fichier audio provenant d'une autre présentation. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Crée et ajoute un audio à une présentation depuis un flux. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Crée et ajoute un audio à une présentation depuis un flux. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Crée et ajoute un audio à une présentation depuis un tableau d'octets. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```

Obtient l'élément à l'index spécifié. Lecture seule [IAudio](../../com.aspose.slides/iaudio).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour :**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```

Ajoute une copie d'un fichier audio provenant d'une autre présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Audio source. |

**Retour :**
[IAudio](../../com.aspose.slides/iaudio) - Audio ajouté.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```

Crée et ajoute un audio à une présentation depuis un flux.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux depuis lequel ajouter l'audio. |

**Retour :**
[IAudio](../../com.aspose.slides/iaudio) - Audio ajouté.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Crée et ajoute un audio à une présentation depuis un flux.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux depuis lequel ajouter l'audio vidéo. |
| loadingStreamBehavior | int | Le [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior) qui sera appliqué au flux. |

**Retour :**
[IAudio](../../com.aspose.slides/iaudio) - Audio ajouté.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```

Crée et ajoute un audio à une présentation depuis un tableau d'octets.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| audioData | byte[] | Octets audio. |

**Retour :**
[IAudio](../../com.aspose.slides/iaudio) - Audio ajouté.