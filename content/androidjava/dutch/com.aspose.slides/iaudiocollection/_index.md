---
title: IAudioCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling van ingesloten audiobestanden voor.
type: docs
url: /nl/com.aspose.slides/iaudiocollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

Stelt een verzameling van ingesloten audiobestanden voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Voegt een kopie van een audiobestand toe vanuit een andere presentatie. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Maakt een audio aan en voegt deze toe aan een presentatie vanuit een stream. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Maakt een audio aan en voegt deze toe aan een presentatie vanuit een stream. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Maakt een audio aan en voegt deze toe aan een presentatie vanuit een byte-array. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
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
public abstract IAudio addAudio(IAudio audio)
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
public abstract IAudio addAudio(InputStream stream)
```

Maakt een audio aan en voegt deze toe aan een presentatie vanuit een stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Stream om audio uit toe te voegen. |

**Retour:**
[IAudio](../../com.aspose.slides/iaudio) - Toegevoegde audio.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Maakt een audio aan en voegt deze toe aan een presentatie vanuit een stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Stream om video-audio uit toe te voegen. |
| loadingStreamBehavior | int | Het [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior) dat op de stream wordt toegepast. |

**Retour:**
[IAudio](../../com.aspose.slides/iaudio) - Toegevoegde audio.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```

Maakt een audio aan en voegt deze toe aan een presentatie vanuit een byte-array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| audioData | byte[] | Audio-bytes. |

**Retour:**
[IAudio](../../com.aspose.slides/iaudio) - Toegevoegde audio.