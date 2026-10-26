---
title: IVideo
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a video embedded into a presentation.
type: docs
url: /nl/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Representeert een video ingebed in een presentatie.
## Methods

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Retourneert een MIME-type van een video, gecodeerd in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Retourneert een kopie van de data van een audio. |
| [getStream()](#getStream--) | Retourneert een Stream voor lezen. |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Retourneert een MIME-type van een video, gecodeerd in (\#getBinaryData.getBinaryData). Alleen-lezen String.

**Returns:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Retourneert een kopie van de data van een audio. In het geval van een grote hoeveelheid data dient u de \#getStream.getStream-methode te gebruiken om onnodig laden van videodata in het geheugen of zelfs een OutOfMemoryException te voorkomen. Alleen-lezen byte[].

**Returns:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Retourneert een Stream voor lezen. Gebruik 'using' of sluit de stream na gebruik.

**Returns:**
java.io.InputStream - Stream voor lezen.