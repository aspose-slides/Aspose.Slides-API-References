---
title: IVideo
second_title: Aspose.Slides for Java API Reference
description: Stelt een video voor die in een presentatie is ingebed.
type: docs
url: /nl/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Stelt een video voor die in een presentatie is ingebed.
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getContentType()](#getContentType--) | Retourneert een MIME-type van een video, gecodeerd in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Retourneert de kopie van de gegevens van een audio. |
| [getStream()](#getStream--) | Retourneert Stream stream voor lezen. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Retourneert een MIME-type van een video, gecodeerd in (\#getBinaryData.getBinaryData). Alleen-lezen String.

**Retour:**  
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Retourneert de kopie van de gegevens van een audio. In het geval van een grote hoeveelheid gegevens overweeg het gebruik van de \#getStream.getStream-methode om onnodig laden van video-gegevens naar het geheugen of zelfs een OutOfMemoryException te voorkomen. Alleen-lezen byte[].

**Retour:**  
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Retourneert Stream stream voor lezen. Gebruik 'using' of sluit de stream na gebruik.

**Retour:**  
java.io.InputStream - Stream voor lezen.