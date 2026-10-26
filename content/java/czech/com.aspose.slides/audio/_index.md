---
title: Audio
second_title: Aspose.Slides pro Java – reference API
description: Reprezentuje vložený zvukový soubor.
type: docs
url: /cs/com.aspose.slides/audio/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

Reprezentuje vložený zvukový soubor.
## Metody

| Metoda | Popis |
| --- | --- |
| [getContentType()](#getContentType--) | Vrací MIME typ zvuku, kódovaný v (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | Vrací MIME typ zvuku, kódovaný v (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Vrací kopii dat zvuku. |
| [getStream()](#getStream--) | Vrací proud Stream pro čtení. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Vrací MIME typ zvuku, kódovaný v (\#getBinaryData.getBinaryData). Pouze pro čtení String.

**Vrací:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Vrací MIME typ zvuku, kódovaný v (\#getBinaryData.getBinaryData). Pouze pro čtení String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Vrací kopii dat zvuku. V případě velkého množství dat zvažte použití metody \#getStream.getStream, aby se zabránilo zbytečnému načítání dat zvuku do paměti nebo dokonce výjimce OutOfMemoryException. Pouze pro čtení byte[].

**Vrací:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Vrací proud Stream pro čtení. Použijte 'using' nebo po použití zavřete proud.

**Vrací:**
java.io.InputStream - Proud pro čtení.