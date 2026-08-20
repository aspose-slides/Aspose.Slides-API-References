---
title: OdpException
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثّل نوع استثناء داخلي قياسي.
type: docs
url: /ar/com.aspose.slides/odpexception/
---
**الوراثة:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class OdpException extends System.Exception
```

يمثّل نوع استثناء داخلي قياسي.
## المنشئات

| Constructor | Description |
| --- | --- |
| [OdpException()](#OdpException--) | Default constructor |
| [OdpException(String message)](#OdpException-java.lang.String-) | Constructor allowing a message to be added to this exception. |
| [OdpException(String message, RuntimeException exception)](#OdpException-java.lang.String-java.lang.RuntimeException-) | Constructor for an exception containing a message and an embedded exception. |
### OdpException() {#OdpException--}
```
public OdpException()
```


المنشئ الافتراضي

### OdpException(String message) {#OdpException-java.lang.String-}
```
public OdpException(String message)
```


منشئ يسمح بإضافة رسالة إلى هذا الاستثناء.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | message |

### OdpException(String message, RuntimeException exception) {#OdpException-java.lang.String-java.lang.RuntimeException-}
```
public OdpException(String message, RuntimeException exception)
```


منشئ لاستثناء يحتوي على رسالة واستثناء مدمج.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | message |
| exception | java.lang.RuntimeException | original exception |