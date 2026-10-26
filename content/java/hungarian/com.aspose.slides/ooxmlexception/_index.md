---
title: OOXMLException
second_title: Aspose.Slides Java API referencia
description: Egy szabványos belső kivételtípust képvisel, amely az Office Open XML fájlformátummal kapcsolatos.
type: docs
url: /hu/com.aspose.slides/ooxmlexception/
---
**Öröklés:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class OOXMLException extends System.Exception
```

Egy szabványos belső kivételtípust képvisel, amely az Office Open XML fájlformátummal kapcsolatos.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [OOXMLException()](#OOXMLException--) | Alapértelmezett konstruktor. |
| [OOXMLException(String message)](#OOXMLException-java.lang.String-) | Konstruktor, amely lehetővé teszi üzenet hozzáadását ehhez a kivételhez. |
| [OOXMLException(String message, RuntimeException exception)](#OOXMLException-java.lang.String-java.lang.RuntimeException-) | Konstruktor, amely üzenetet és egy beágyazott kivételt tartalmaz. |
### OOXMLException() {#OOXMLException--}
```
public OOXMLException()
```

Alapértelmezett konstruktor.

### OOXMLException(String message) {#OOXMLException-java.lang.String-}
```
public OOXMLException(String message)
```

Konstruktor, amely lehetővé teszi üzenet hozzáadását ehhez a kivételhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | üzenet |

### OOXMLException(String message, RuntimeException exception) {#OOXMLException-java.lang.String-java.lang.RuntimeException-}
```
public OOXMLException(String message, RuntimeException exception)
```

Konstruktor, amely üzenetet és egy beágyazott kivételt tartalmaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | üzenet |
| exception | java.lang.RuntimeException | eredeti kivétel |