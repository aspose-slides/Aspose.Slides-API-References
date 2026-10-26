---
title: PptCorruptFileException
second_title: Aspose.Slides for Android Java API Referansı
description: Sunum dosyası muhtemelen bozuk olduğunda fırlatılan istisna.
type: docs
url: /tr/com.aspose.slides/pptcorruptfileexception/
---
**Kalıtım:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.PptException](../../com.aspose.slides/pptexception), [com.aspose.slides.PptReadException](../../com.aspose.slides/pptreadexception)
```
public class PptCorruptFileException extends PptReadException
```

Sunum dosyasının muhtemelen bozuk olduğu durumlarda fırlatılan istisna.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PptCorruptFileException()](#PptCorruptFileException--) | Varsayılan yapıcı. |
| [PptCorruptFileException(String message)](#PptCorruptFileException-java.lang.String-) | Bu istisna için bir mesaj eklenmesine izin veren yapıcı. |
| [PptCorruptFileException(String message, RuntimeException exception)](#PptCorruptFileException-java.lang.String-java.lang.RuntimeException-) | Bir mesaj ve gömülü bir istisna içeren istisna için yapıcı. |
### PptCorruptFileException() {#PptCorruptFileException--}
```
public PptCorruptFileException()
```

Varsayılan yapıcı.

### PptCorruptFileException(String message) {#PptCorruptFileException-java.lang.String-}
```
public PptCorruptFileException(String message)
```

Bu istisna için bir mesaj eklenmesine izin veren yapıcı.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| message | java.lang.String | mesaj |

### PptCorruptFileException(String message, RuntimeException exception) {#PptCorruptFileException-java.lang.String-java.lang.RuntimeException-}
```
public PptCorruptFileException(String message, RuntimeException exception)
```

Bir mesaj ve gömülü bir istisna içeren istisna için yapıcı.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| message | java.lang.String | mesaj |
| exception | java.lang.RuntimeException | orijinal istisna |