---
title: IAudio
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an embedded audio file.
type: docs
url: /nl/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Stelt een ingesloten audiobestand voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getContentType()](#getContentType--) | Retourneert een MIME-type van een audio, gecodeerd in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Retourneert een kopie van de gegevens van een audio. |
| [getStream()](#getStream--) | Retourneert Stream stream voor lezen. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Retourneert een MIME-type van een audio, gecodeerd in (\#getBinaryData.getBinaryData). Alleen-lezen String.

**Retourneert:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Retourneert een kopie van de gegevens van een audio. In het geval van een grote hoeveelheid data overweeg het gebruik van \#getStream.getStream methode om onnodig laden van audio-gegevens in het geheugen of zelfs OutOfMemoryException te voorkomen. Alleen-lezen byte[].

**Retourneert:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Retourneert Stream stream voor lezen. Gebruik 'using' of sluit de stream na gebruik.

**Retourneert:**
java.io.InputStream - Stream voor lezen.