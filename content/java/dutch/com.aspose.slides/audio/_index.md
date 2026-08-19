---
title: Audio
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een ingebed audiobestand voor.
type: docs
url: /nl/com.aspose.slides/audio/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

Stelt een ingebed audiobestand voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getContentType()](#getContentType--) | Retourneert een MIME-type van een audio, gecodeerd in (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | Retourneert een MIME-type van een audio, gecodeerd in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Retourneert een kopie van de gegevens van een audio. |
| [getStream()](#getStream--) | Retourneert Stream stream voor lezen. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Retourneert een MIME-type van een audio, gecodeerd in (\#getBinaryData.getBinaryData). Alleen-lezen String.

**Retourneert:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Retourneert een MIME-type van een audio, gecodeerd in (\#getBinaryData.getBinaryData). Alleen-lezen String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Retourneert een kopie van de gegevens van een audio. In geval van een grote hoeveelheid data overweeg het gebruik van \#getStream.getStream-methode om onnodig laden van audio-gegevens in het geheugen of zelfs OutOfMemoryException te voorkomen. Alleen-lezen byte[].

**Retourneert:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Retourneert Stream stream voor lezen. Gebruik 'using' of sluit de stream na gebruik.

**Retourneert:**
java.io.InputStream - Stream voor lezen.