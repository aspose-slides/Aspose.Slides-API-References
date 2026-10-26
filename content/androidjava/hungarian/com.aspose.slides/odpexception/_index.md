---
title: OdpException
second_title: Aspose.Slides for Android a Java API hivatkozáson keresztül
description: Egy szabványos belső kivételtípust reprezentál.
type: docs
url: /hu/com.aspose.slides/odpexception/
---
**Öröklés:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class OdpException extends System.Exception
```

Egy szabványos belső kivételtípust reprezentál.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [OdpException()](#OdpException--) | Alapértelmezett konstruktor |
| [OdpException(String message)](#OdpException-java.lang.String-) | Konstruktor, amely lehetővé teszi, hogy üzenetet adjunk hozzá ehhez a kivételhez. |
| [OdpException(String message, RuntimeException exception)](#OdpException-java.lang.String-java.lang.RuntimeException-) | Konstruktor egy olyan kivételhez, amely üzenetet és egy beágyazott kivételt tartalmaz. |
### OdpException() {#OdpException--}
```
public OdpException()
```

Alapértelmezett konstruktor

### OdpException(String message) {#OdpException-java.lang.String-}
```
public OdpException(String message)
```

Konstruktor, amely lehetővé teszi, hogy üzenetet adjunk hozzá ehhez a kivételhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | üzenet |

### OdpException(String message, RuntimeException exception) {#OdpException-java.lang.String-java.lang.RuntimeException-}
```
public OdpException(String message, RuntimeException exception)
```

Konstruktor egy olyan kivételhez, amely üzenetet és egy beágyazott kivételt tartalmaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | üzenet |
| exception | java.lang.RuntimeException | eredeti kivétel |