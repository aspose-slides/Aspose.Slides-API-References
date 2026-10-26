---
title: AudioCollection
second_title: Référence API Java Aspose.Slides pour Android
description: Représente une collection de fichiers audio incorporés.
type: docs
url: /fr/com.aspose.slides/audiocollection/
---
**Héritage :**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées :**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

Représente une collection de fichiers audio intégrés.
## Méthodes

| Méthode | Description |
| --- | --- |
| [size()](#size--) | Renvoie le nombre de fichiers audio dans la collection. |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Ajoute une copie d'un fichier audio provenant d'une autre présentation. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Crée et ajoute un audio à une présentation depuis le flux. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Crée et ajoute un audio à une présentation depuis le flux. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Crée et ajoute un audio à une présentation depuis un tableau d'octets. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie les audios dans le tableau spécifié à partir de l'index spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie une racine de synchronisation. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour la collection entière. |
### size() {#size--}
```
public final int size()
```

Renvoie le nombre de fichiers audio dans la collection. Lecture seule int.

**Renvoie :**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```

Obtient l'élément à l'index spécifié. Lecture seule [IAudio](../../com.aspose.slides/iaudio).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```

Ajoute une copie d'un fichier audio provenant d'une autre présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Audio source. |

**Renvoie :**
[IAudio](../../com.aspose.slides/iaudio) - Audio ajouté.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```

Crée et ajoute un audio à une présentation depuis le flux.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux depuis lequel ajouter l'audio. |

**Renvoie :**
[IAudio](../../com.aspose.slides/iaudio) - Audio ajouté.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Crée et ajoute un audio à une présentation depuis le flux.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux depuis lequel ajouter le audio vidéo. |
| loadingStreamBehavior | int | Le comportement qui sera appliqué au flux. |

**Renvoie :**
[IAudio](../../com.aspose.slides/iaudio) - Audio ajouté.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```

Crée et ajoute un audio à une présentation depuis un tableau d'octets.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| audioData | byte[] | Octets audio. |

**Renvoie :**
[IAudio](../../com.aspose.slides/iaudio) - Audio ajouté.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copie les audios dans le tableau spécifié à partir de l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tableau. |
| index | int | Index. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule boolean.

**Renvoie :**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Renvoie une racine de synchronisation. Lecture seule Object.

**Renvoie :**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Un IGenericEnumerator qui peut être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```

Renvoie un itérateur java pour la collection entière.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Un java.util.Iterator pour la collection entière.