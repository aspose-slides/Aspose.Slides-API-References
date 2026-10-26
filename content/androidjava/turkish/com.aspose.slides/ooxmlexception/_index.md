---
title: OOXMLException
second_title: Aspose.Slides for Android via Java API Referansı
description: Office Open XML dosya biçimiyle ilgili standart bir iç istisna tipini temsil eder.
type: docs
url: /tr/com.aspose.slides/ooxmlexception/
---
**Kalıtım:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class OOXMLException extends System.Exception
```

Office Open XML dosya biçimiyle ilgili standart bir iç istisna tipini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OOXMLException()](#OOXMLException--) | Varsayılan yapıcı. |
| [OOXMLException(String message)](#OOXMLException-java.lang.String-) | Bu istisna için bir mesaj eklenmesine izin veren yapıcı. |
| [OOXMLException(String message, RuntimeException exception)](#OOXMLException-java.lang.String-java.lang.RuntimeException-) | Bir mesaj ve gömülü bir istisna içeren bir istisna için yapıcı. |
### OOXMLException() {#OOXMLException--}
```
public OOXMLException()
```

Varsayılan yapıcı.

### OOXMLException(String message) {#OOXMLException-java.lang.String-}
```
public OOXMLException(String message)
```

Bu istisna için bir mesaj eklenmesine izin veren yapıcı.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | java.lang.String | mesaj |

### OOXMLException(String message, RuntimeException exception) {#OOXMLException-java.lang.String-java.lang.RuntimeException-}
```
public OOXMLException(String message, RuntimeException exception)
```

Bir mesaj ve gömülü bir istisna içeren bir istisna için yapıcı.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | java.lang.String | mesaj |
| exception | java.lang.RuntimeException | orijinal istisna |