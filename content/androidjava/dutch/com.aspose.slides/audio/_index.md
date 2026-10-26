---
title: Audio
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een ingesloten audiobestand voor.
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

Stelt een ingesloten audiobestand voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getContentType()](#getContentType--) | Geeft een MIME-type van een audio terug, gecodeerd in (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | Geeft een MIME-type van een audio terug, gecodeerd in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Geeft een kopie van de gegevens van een audio terug. |
| [getStream()](#getStream--) | Geeft een Stream terug voor lezen. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Geeft een MIME-type van een audio terug, gecodeerd in (\#getBinaryData.getBinaryData). Alleen-lezen String.

**Retourneert:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```


Geeft een MIME-type van een audio terug, gecodeerd in (\#getBinaryData.getBinaryData). Alleen-lezen String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Geeft een kopie van de gegevens van een audio terug. In het geval van een grote hoeveelheid data, overweeg het gebruik van de \#getStream.getStream methode om te voorkomen dat de gegevens van de audio onnodig in het geheugen worden geladen of zelfs een OutOfMemoryException veroorzaken. Alleen-lezen byte[].

**Retourneert:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Geeft een Stream terug voor lezen. Gebruik 'using' of sluit de stream na gebruik.

**Retourneert:**
java.io.InputStream - Stream voor lezen.