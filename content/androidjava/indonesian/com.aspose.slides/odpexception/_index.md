---
title: OdpException
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili jenis pengecualian internal standar.
type: docs
url: /id/com.aspose.slides/odpexception/
---
**Pewarisan:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class OdpException extends System.Exception
```

Mewakili jenis pengecualian internal standar.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [OdpException()](#OdpException--) | Konstruktor default |
| [OdpException(String message)](#OdpException-java.lang.String-) | Konstruktor yang memungkinkan pesan ditambahkan ke pengecualian ini. |
| [OdpException(String message, RuntimeException exception)](#OdpException-java.lang.String-java.lang.RuntimeException-) | Konstruktor untuk pengecualian yang berisi pesan dan pengecualian terbenam. |
### OdpException() {#OdpException--}
```
public OdpException()
```


Konstruktor default

### OdpException(String message) {#OdpException-java.lang.String-}
```
public OdpException(String message)
```


Konstruktor yang memungkinkan pesan ditambahkan ke pengecualian ini.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| message | java.lang.String | pesan |

### OdpException(String message, RuntimeException exception) {#OdpException-java.lang.String-java.lang.RuntimeException-}
```
public OdpException(String message, RuntimeException exception)
```


Konstruktor untuk pengecualian yang berisi pesan dan pengecualian terbenam.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| message | java.lang.String | pesan |
| exception | java.lang.RuntimeException | pengecualian asli |