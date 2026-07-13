---
title: OOXMLException
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili tipe pengecualian internal standar yang terkait dengan format file Office Open XML.
type: docs
url: /id/com.aspose.slides/ooxmlexception/
---
**Pewarisan:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class OOXMLException extends System.Exception
```

Mewakili tipe pengecualian internal standar yang terkait dengan format file Office Open XML.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [OOXMLException()](#OOXMLException--) | Konstruktor default. |
| [OOXMLException(String message)](#OOXMLException-java.lang.String-) | Konstruktor yang memungkinkan pesan ditambahkan ke pengecualian ini. |
| [OOXMLException(String message, RuntimeException exception)](#OOXMLException-java.lang.String-java.lang.RuntimeException-) | Konstruktor untuk pengecualian yang berisi pesan dan pengecualian yang tertanam. |
### OOXMLException() {#OOXMLException--}
```
public OOXMLException()
```


Konstruktor default.

### OOXMLException(String message) {#OOXMLException-java.lang.String-}
```
public OOXMLException(String message)
```


Konstruktor yang memungkinkan pesan ditambahkan ke pengecualian ini.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| message | java.lang.String | message |

### OOXMLException(String message, RuntimeException exception) {#OOXMLException-java.lang.String-java.lang.RuntimeException-}
```
public OOXMLException(String message, RuntimeException exception)
```


Konstruktor untuk pengecualian yang berisi pesan dan pengecualian yang tertanam.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| message | java.lang.String | message |
| exception | java.lang.RuntimeException | pengecualian asli |