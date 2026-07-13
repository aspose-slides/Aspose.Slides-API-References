---
title: IVideo
second_title: Aspose.Slides for Android via Java API Reference
description: Representerar en video inbäddad i en presentation.
type: docs
url: /sv/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Representerar en video inbäddad i en presentation.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getContentType()](#getContentType--) | Returnerar en MIME-typ för en video, kodad i (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Returnerar en kopia av ett ljuds data. |
| [getStream()](#getStream--) | Returnerar en Stream för läsning. |
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

Returnerar en kopia av ett ljuds data. Vid stora mängder data bör du överväga att använda \#getStream.getStream-metoden för att förhindra onödig laddning av videons data i minnet eller till och med OutOfMemoryException. Skrivskyddad byte[].

**Returnerar:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Returnerar en Stream för läsning. Använd 'using' eller stäng strömmen efter användning.

**Returnerar:**
java.io.InputStream - Stream för läsning.