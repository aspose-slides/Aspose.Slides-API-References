---
title: AudioCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling ingebedde audiobestanden voor.
type: docs
url: /nl/com.aspose.slides/audiocollection/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

Stelt een verzameling ingebedde audiobestanden voor.
## Methodes

| Methode | Omschrijving |
| --- | --- |
| [size()](#size--) | Retourneert het aantal audiobestanden in de collectie. |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Voegt een kopie van een audiobestand toe vanuit een andere presentatie. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Maakt een audio aan en voegt deze toe aan een presentatie vanuit een stream. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Maakt een audio aan en voegt deze toe aan een presentatie vanuit een stream. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Maakt een audio aan en voegt deze toe aan een presentatie vanuit een byte-array. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert audio's naar de opgegeven array beginnend bij de opgegeven index. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
### size() {#size--}
```
public final int size()
```

Retourneert het aantal audiobestanden in de collectie. Alleen-lezen int.

**Retour:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```

Haalt het element op op de opgegeven index. Alleen-lezen [IAudio](../../com.aspose.slides/iaudio).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```

Voegt een kopie van een audiobestand toe vanuit een andere presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Bron-audio. |

**Retour:**
[IAudio](../../com.aspose.slides/iaudio) - Toegevoegde audio.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```

Maakt een audio aan en voegt deze toe aan een presentatie vanuit een stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Stream om audio vanuit toe te voegen. |

**Retour:**
[IAudio](../../com.aspose.slides/iaudio) - Toegevoegde audio.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Maakt een audio aan en voegt deze toe aan een presentatie vanuit een stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Stream om video-audio vanuit toe te voegen. |
| loadingStreamBehavior | int | Het gedrag dat op de stream zal worden toegepast. |

**Retour:**
[IAudio](../../com.aspose.slides/iaudio) - Toegevoegde audio.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```

Maakt een audio aan en voegt deze toe aan een presentatie vanuit een byte-array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| audioData | byte[] | Audiobytes. |

**Retour:**
[IAudio](../../com.aspose.slides/iaudio) - Toegevoegde audio.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopieert audio's naar de opgegeven array beginnend bij de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array. |
| index | int | Index. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). Alleen-lezen boolean.

**Retour:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retourneert een synchronisatiewortel. Alleen-lezen Object.

**Retour:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```

Retourneert een enumerator die door de collectie itereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```

Retourneert een java-iterator voor de volledige collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Een java.util.Iterator voor de volledige collectie.