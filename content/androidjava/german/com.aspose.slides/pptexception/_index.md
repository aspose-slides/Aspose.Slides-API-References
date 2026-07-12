---
title: PptException
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt einen standardmäßigen internen Ausnahmetyp dar.
type: docs
url: /de/com.aspose.slides/pptexception/
---
**Vererbung:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class PptException extends System.Exception
```

Stellt einen standardmäßigen internen Ausnahme-Typ dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PptException()](#PptException--) | Standardkonstruktor. |
| [PptException(String message)](#PptException-java.lang.String-) | Konstruktor, der das Hinzufügen einer Nachricht zu dieser Ausnahme ermöglicht. |
| [PptException(String message, Exception exception)](#PptException-java.lang.String-java.lang.Exception-) | Konstruktor für eine Ausnahme, die eine Nachricht und eine eingebettete Ausnahme enthält. |
### PptException() {#PptException--}
```
public PptException()
```

Standardkonstruktor.

### PptException(String message) {#PptException-java.lang.String-}
```
public PptException(String message)
```

Konstruktor, der das Hinzufügen einer Nachricht zu dieser Ausnahme ermöglicht.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | java.lang.String | message |

### PptException(String message, Exception exception) {#PptException-java.lang.String-java.lang.Exception-}
```
public PptException(String message, Exception exception)
```

Konstruktor für eine Ausnahme, die eine Nachricht und eine eingebettete Ausnahme enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | java.lang.String | message |
| exception | java.lang.Exception | original exception |