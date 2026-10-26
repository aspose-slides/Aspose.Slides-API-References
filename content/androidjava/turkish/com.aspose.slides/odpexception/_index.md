---
title: OdpException
second_title: Aspose.Slides for Android için Java API Referansı
description: Standart bir iç istisna türünü temsil eder.
type: docs
url: /tr/com.aspose.slides/odpexception/
---
**Kalıtım:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class OdpException extends System.Exception
```

Standart bir iç istisna türünü temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OdpException()](#OdpException--) | Varsayılan yapıcı |
| [OdpException(String message)](#OdpException-java.lang.String-) | Bu istisnaya bir mesaj eklenmesine izin veren yapıcı. |
| [OdpException(String message, RuntimeException exception)](#OdpException-java.lang.String-java.lang.RuntimeException-) | Mesaj ve gömülü bir istisna içeren bir istisna için yapıcı. |
### OdpException() {#OdpException--}
```
public OdpException()
```


Varsayılan yapıcı

### OdpException(String message) {#OdpException-java.lang.String-}
```
public OdpException(String message)
```


Bu istisnaya bir mesaj eklenmesine izin veren yapıcı.

Parametreler:
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | java.lang.String | mesaj |

### OdpException(String message, RuntimeException exception) {#OdpException-java.lang.String-java.lang.RuntimeException-}
```
public OdpException(String message, RuntimeException exception)
```


Mesaj ve gömülü bir istisna içeren bir istisna için yapıcı.

Parametreler:
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | java.lang.String | mesaj |
| exception | java.lang.RuntimeException | orijinal istisna |