---
title: OOXMLException
second_title: Aspose.Slides for Android Java API hivatkozás
description: Szabványos belső kivételtípust képvisel, amely az Office Open XML fájlformátumhoz kapcsolódik.
type: docs
url: /hu/com.aspose.slides/ooxmlexception/
---
**Öröklődés:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class OOXMLException extends System.Exception
```

Egy szabványos belső kivételtípust képvisel, amely az Office Open XML fájlformátumhoz kapcsolódik.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [OOXMLException()](#OOXMLException--) | Alapértelmezett konstruktor. |
| [OOXMLException(String message)](#OOXMLException-java.lang.String-) | Konstruktor, amely lehetővé teszi egy üzenet hozzáadását ehhez a kivételhez. |
| [OOXMLException(String message, RuntimeException exception)](#OOXMLException-java.lang.String-java.lang.RuntimeException-) | Konstruktor, amely egy üzenetet és egy beágyazott kivételt tartalmaz. |
### OOXMLException() {#OOXMLException--}
```
public OOXMLException()
```

Alapértelmezett konstruktor.

### OOXMLException(String message) {#OOXMLException-java.lang.String-}
```
public OOXMLException(String message)
```

Konstruktor, amely lehetővé teszi egy üzenet hozzáadását ehhez a kivételhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | üzenet |

### OOXMLException(String message, RuntimeException exception) {#OOXMLException-java.lang.String-java.lang.RuntimeException-}
```
public OOXMLException(String message, RuntimeException exception)
```

Konstruktor, amely egy üzenetet és egy beágyazott kivételt tartalmaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | üzenet |
| exception | java.lang.RuntimeException | eredeti kivétel |