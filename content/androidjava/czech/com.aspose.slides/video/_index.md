---
title: Video
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Představuje obrázek vložený do prezentace.
type: docs
url: /cs/com.aspose.slides/video/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

Představuje obrázek vložený do prezentace.
## Metody

| Metoda | Popis |
| --- | --- |
| [getContentType()](#getContentType--) | Vrací MIME typ videa, zakódovaný v (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Vrací kopii dat audia. |
| [getStream()](#getStream--) | Vrací Stream stream pro čtení. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Vrací MIME typ videa, zakódovaný v (\#getBinaryData.getBinaryData). Pouze pro čtení String.

**Vrací:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Vrací kopii dat audia. V případě velkého množství dat zvažte použití metody \#getStream.getStream, aby se zabránilo zbytečnému načítání dat videa do paměti nebo dokonce výjimce OutOfMemoryException. Pouze pro čtení byte[].

**Vrací:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Vrací Stream stream pro čtení. Použijte 'using' nebo po použití uzavřete stream.

**Vrací:**
java.io.InputStream - Stream pro čtení.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent\_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject