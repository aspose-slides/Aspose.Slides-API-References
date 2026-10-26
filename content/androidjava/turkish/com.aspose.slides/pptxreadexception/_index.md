---
title: PptxReadException
second_title: Java API Referansı ile Android için Aspose.Slides
description: Sunum okuma hatalarında atılan bir istisnayı temsil eder.
type: docs
url: /tr/com.aspose.slides/pptxreadexception/
---
**Kalıtım:**  
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception)
```
public class PptxReadException extends PptxException
```

Sunum okuma hatalarında atılan bir istisnayı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PptxReadException()](#PptxReadException--) | Varsayılan yapıcı. |
| [PptxReadException(String message)](#PptxReadException-java.lang.String-) | Bu istisna için bir ileti eklenmesine izin veren yapıcı. |
| [PptxReadException(String message, RuntimeException exception)](#PptxReadException-java.lang.String-java.lang.RuntimeException-) | Bir ileti ve gömülü bir istisna içeren bir istisna için yapıcı. |

### PptxReadException() {#PptxReadException--}
```
public PptxReadException()
```

Varsayılan yapıcı.

### PptxReadException(String message) {#PptxReadException-java.lang.String-}
```
public PptxReadException(String message)
```

Bu istisna için bir ileti eklenmesine izin veren yapıcı.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | java.lang.String | mesaj |

### PptxReadException(String message, RuntimeException exception) {#PptxReadException-java.lang.String-java.lang.RuntimeException-}
```
public PptxReadException(String message, RuntimeException exception)
```

Bir ileti ve gömülü bir istisna içeren bir istisna için yapıcı.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | java.lang.String | mesaj |
| exception | java.lang.RuntimeException | orijinal istisna |