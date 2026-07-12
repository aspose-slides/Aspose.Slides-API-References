---
title: CellCircularReferenceException
second_title: Aspose.Slides für Android über Java API Referenz
description: Die Ausnahme, die ausgelöst wird, wenn ein oder mehrere zirkuläre Verweise erkannt werden, bei denen eine Formel direkt oder indirekt auf ihre eigene Zelle verweist.
type: docs
url: /de/com.aspose.slides/cellcircularreferenceexception/
---
**Vererbung:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

Die Ausnahme, die ausgelöst wird, wenn ein oder mehrere zirkuläre Verweise erkannt werden, bei denen eine Formel direkt oder indirekt auf ihre eigene Zelle verweist.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | Initialisiert eine neue Instanz der [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) Klasse. |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | Initialisiert eine neue Instanz der [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) Klasse mit einer angegebenen Fehlermeldung. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | Initialisiert eine neue Instanz der [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die die Ursache dieser Ausnahme ist. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | Initialisiert eine neue Instanz der [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) Klasse mit einer angegebenen Fehlermeldung und einem zirkulären Zellverweis. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getReference()](#getReference--) | Gibt einen zirkulären Zellverweis zurück. |
### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

Initialisiert eine neue Instanz der [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) Klasse.

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

Initialisiert eine neue Instanz der [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) Klasse mit einer angegebenen Fehlermeldung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | java.lang.String | Ein String, der den Fehler beschreibt. |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

Initialisiert eine neue Instanz der [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die die Ursache dieser Ausnahme ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | java.lang.String | Ein String, der den Fehler beschreibt. |
| innerException | java.lang.RuntimeException | Die Ausnahme, die die Ursache der aktuellen Ausnahme ist. |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

Initialisiert eine neue Instanz der [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) Klasse mit einer angegebenen Fehlermeldung und einem zirkulären Zellverweis.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | java.lang.String | Ein String, der den Fehler beschreibt. |
| reference | java.lang.String | Ein zirkulärer Zellverweis. |

### getReference() {#getReference--}
```
public final String getReference()
```

Gibt einen zirkulären Zellverweis zurück.

**Rückgabe:**
java.lang.String