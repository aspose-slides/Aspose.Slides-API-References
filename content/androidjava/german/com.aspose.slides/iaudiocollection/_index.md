---
title: IAudioCollection
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Sammlung eingebetteter Audiodateien dar.
type: docs
url: /de/com.aspose.slides/iaudiocollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

Stellt eine Sammlung eingebetteter Audiodateien dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ruft das Element am angegebenen Index ab. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Fügt eine Kopie einer Audiodatei aus einer anderen Präsentation hinzu. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Erstellt und fügt ein Audio zu einer Präsentation aus einem Stream hinzu. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Erstellt und fügt ein Audio zu einer Präsentation aus einem Stream hinzu. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Erstellt und fügt ein Audio zu einer Präsentation aus einem Byte-Array hinzu. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```

Ruft das Element am angegebenen Index ab. Schreibgeschützt [IAudio](../../com.aspose.slides/iaudio).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```

Fügt eine Kopie einer Audiodatei aus einer anderen Präsentation hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Quell-Audio. |

**Rückgabe:**
[IAudio](../../com.aspose.slides/iaudio) - Hinzugefügtes Audio.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```

Erstellt und fügt ein Audio zu einer Präsentation aus dem Stream hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, aus dem Audio hinzugefügt wird. |

**Rückgabe:**
[IAudio](../../com.aspose.slides/iaudio) - Hinzugefügtes Audio.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Erstellt und fügt ein Audio zu einer Präsentation aus dem Stream hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, aus dem Video-Audio hinzugefügt wird. |
| loadingStreamBehavior | int | Der [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior), der auf den Stream angewendet wird. |

**Rückgabe:**
[IAudio](../../com.aspose.slides/iaudio) - Hinzugefügtes Audio.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```

Erstellt und fügt ein Audio zu einer Präsentation aus einem Byte-Array hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| audioData | byte[] | Audio-Bytes. |

**Rückgabe:**
[IAudio](../../com.aspose.slides/iaudio) - Hinzugefügtes Audio.