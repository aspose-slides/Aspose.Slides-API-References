---
title: IVideo
second_title: Aspose.Slides for Java API Reference
description: Representerar en video som är inbäddad i en presentation.
type: docs
url: /sv/com.aspose.slides/ivideo/
---```
public interface IVideo
```


Representerar en video som är inbäddad i en presentation.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getContentType()](#getContentType--) | Returnerar en MIME-typ för en video, kodad i (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Returnerar en kopia av ljuddata. |
| [getStream()](#getStream--) | Returnerar Stream stream för läsning. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Returnerar en MIME-typ för en video, kodad i (\#getBinaryData.getBinaryData). Skrivskyddad String.

**Returnerar:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Returnerar en kopia av ljuddata. Vid stora mängder data bör du överväga att använda \#getStream.getStream method för att förhindra onödig laddning av videons data i minnet eller till och med OutOfMemoryException. Skrivskyddad byte[].

**Returnerar:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Returnerar Stream stream för läsning. Använd 'using' eller stäng strömmen efter användning.

**Returnerar:**
java.io.InputStream - Stream för läsning.