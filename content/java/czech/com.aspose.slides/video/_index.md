---
title: Video
second_title: Aspose.Slides pro Java – reference API
description: Představuje obrázek vložený do prezentace.
type: docs
url: /cs/com.aspose.slides/video/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

Představuje obrázek vložený do prezentace.
## Metody

| Metoda | Popis |
| --- | --- |
| [getContentType()](#getContentType--) | Vrací MIME typ videa, kódovaný v (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Vrací kopii dat zvuku. |
| [getStream()](#getStream--) | Vrací Stream stream pro čtení. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Vrací MIME typ videa, kódovaný v (\#getBinaryData.getBinaryData). Pouze pro čtení String.

**Vrací:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Vrací kopii dat zvuku. V případě velkého množství dat zvažte použití metody \#getStream.getStream, aby se zabránilo zbytečnému načítání dat videa do paměti nebo dokonce výjimce OutOfMemoryException. Pouze pro čtení byte[].

**Vrací:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Vrací Stream stream pro čtení. Použijte 'using' nebo po použití zavřete proud.

**Vrací:**
java.io.InputStream - Stream pro čtení.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject