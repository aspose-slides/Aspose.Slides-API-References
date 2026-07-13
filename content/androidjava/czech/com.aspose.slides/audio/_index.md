---
title: Audio
second_title: Aspose.Slides pro Android pomocí odkazu na Java API
description: Reprezentuje vložený audio soubor.
type: docs
url: /cs/com.aspose.slides/audio/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

Reprezentuje vložený audio soubor.
## Metody

| Metoda | Popis |
| --- | --- |
| [getContentType()](#getContentType--) | Vrací MIME typ audio, zakódovaný v (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | Vrací MIME typ audio, zakódovaný v (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Vrací kopii dat audio. |
| [getStream()](#getStream--) | Vrací Stream stream pro čtení. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Vrací MIME typ audio, zakódovaný v (\#getBinaryData.getBinaryData). String pouze pro čtení.

**Vrací:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Vrací MIME typ audio, zakódovaný v (\#getBinaryData.getBinaryData). String pouze pro čtení.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Vrací kopii dat audio. V případě velkého množství dat zvažte použití metody \#getStream.getStream, aby se zabránilo zbytečnému načítání dat audio do paměti nebo dokonce OutOfMemoryException. byte[] pouze pro čtení.

**Vrací:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Vrací Stream stream pro čtení. Použijte 'using' nebo zavřete stream po použití.

**Vrací:**
java.io.InputStream - Stream pro čtení.