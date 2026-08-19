---
title: Audio
second_title: Aspose.Slides för Java API-referens
description: Representerar en inbäddad ljudfil.
type: docs
url: /sv/com.aspose.slides/audio/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

Representerar en inbäddad ljudfil.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getContentType()](#getContentType--) | Returnerar en MIME-typ för ett ljud, kodad i (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | Returnerar en MIME-typ för ett ljud, kodad i (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Returnerar en kopia av ett ljuds data. |
| [getStream()](#getStream--) | Returnerar Stream stream för läsning. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Returnerar en MIME-typ för ett ljud, kodad i (\#getBinaryData.getBinaryData). Skrivskyddad String.

**Returnerar:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Returnerar en MIME-typ för ett ljud, kodad i (\#getBinaryData.getBinaryData). Skrivskyddad String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Returnerar en kopia av ett ljuds data. Vid stora mängder data bör du använda \#getStream.getStream-metoden för att undvika onödig inläsning av ljudets data i minnet eller till och med OutOfMemoryException. Skrivskyddad byte[].

**Returnerar:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Returnerar Stream stream för läsning. Använd 'using' eller stäng stream efter användning.

**Returnerar:**
java.io.InputStream - Stream för läsning.