---
title: IAudio
second_title: Aspose.Slides för Java API-referens
description: Representerar en inbäddad ljudfil.
type: docs
url: /sv/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Representerar en inbäddad ljudfil.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getContentType()](#getContentType--) | Returnerar en MIME-typ för ett ljud, kodad i (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Returnerar en kopia av ett ljuds data. |
| [getStream()](#getStream--) | Returnerar Stream stream för läsning. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Returnerar en MIME-typ för ett ljud, kodad i (\#getBinaryData.getBinaryData). Skrivskyddad String.

**Returnerar:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Returnerar en kopia av ljudets data. Vid stora mängder data bör du överväga att använda \#getStream.getStream metod för att förhindra onödig inläsning av ljudets data i minnet eller till och med OutOfMemoryException. Skrivskyddad byte[].

**Returnerar:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Returnerar Stream stream för läsning. Använd 'using' eller stäng strömmen efter användning.

**Returnerar:**
java.io.InputStream - Stream för läsning.