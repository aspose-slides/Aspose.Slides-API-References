---
title: IAudio
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an embedded audio file.
type: docs
url: /sv/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Representerar en inbäddad ljudfil.
## Metoder

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Returnerar en MIME-typ för ett ljud, kodad i (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Returnerar en kopia av ett ljuds data. |
| [getStream()](#getStream--) | Returnerar Stream för läsning. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Returnerar en MIME-typ för ett ljud, kodad i (\#getBinaryData.getBinaryData). Skrivskyddad String.

**Returns:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Returnerar en kopia av ett ljuds data. Vid stora datamängder överväg att använda \#getStream.getStream-metoden för att förhindra onödig inläsning av ljudfilens data i minnet eller till och med OutOfMemoryException. Skrivskyddad byte[].

**Returns:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Returnerar Stream för läsning. Använd 'using' eller stäng strömmen efter användning.

**Returns:**
java.io.InputStream - Stream för läsning.