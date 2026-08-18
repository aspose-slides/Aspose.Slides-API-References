---
title: PptxException
second_title: Aspose.Slides için Java API Referansı
description: Standart bir dahili istisna tipini temsil eder.
type: docs
url: /tr/com.aspose.slides/pptxexception/
---
**Kalıtım:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception)
```
public class PptxException extends OOXMLException
```

Standart bir dahili istisna tipini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PptxException()](#PptxException--) | Varsayılan yapıcı. |
| [PptxException(String message)](#PptxException-java.lang.String-) | Bu istisna için bir mesaj eklenmesine izin veren yapıcı. |
| [PptxException(String message, RuntimeException exception)](#PptxException-java.lang.String-java.lang.RuntimeException-) | Bir mesaj ve gömülü bir istisna içeren istisna için yapıcı. |
### PptxException() {#PptxException--}
```
public PptxException()
```


Varsayılan yapıcı.

### PptxException(String message) {#PptxException-java.lang.String-}
```
public PptxException(String message)
```


Bu istisna için bir mesaj eklenmesine izin veren yapıcı.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| message | java.lang.String | mesaj |

### PptxException(String message, RuntimeException exception) {#PptxException-java.lang.String-java.lang.RuntimeException-}
```
public PptxException(String message, RuntimeException exception)
```


Bir mesaj ve gömülü bir istisna içeren istisna için yapıcı.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| message | java.lang.String | mesaj |
| exception | java.lang.RuntimeException | orijinal istisna |