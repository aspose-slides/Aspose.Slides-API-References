---
title: CellInvalidReferenceException
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Die Ausnahme, die ausgelöst wird, wenn eine ungültige Zellreferenz gefunden wird.
type: docs
url: /de/com.aspose.slides/cellinvalidreferenceexception/
---
**Vererbung:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

Die Ausnahme, die ausgelöst wird, wenn eine ungültige Zellreferenz gefunden wird.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | Initialisiert eine neue Instanz der [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) Klasse. |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | Initialisiert eine neue Instanz der [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) Klasse mit einer angegebenen Fehlermeldung. |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | Initialisiert eine neue Instanz der [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die die Ursache dieser Ausnahme ist. |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | Initialisiert eine neue Instanz der [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) Klasse mit einer angegebenen Fehlermeldung und einer ungültigen Zellreferenz. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getReference()](#getReference--) | Gibt eine ungültige Zellreferenz zurück. |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```


Initialisiert eine neue Instanz der [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) Klasse.

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```


Initialisiert eine neue Instanz der [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) Klasse mit einer angegebenen Fehlermeldung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | java.lang.String | Eine Zeichenkette, die den Fehler beschreibt. |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```


Initialisiert eine neue Instanz der [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die die Ursache dieser Ausnahme ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | java.lang.String | Eine Zeichenkette, die den Fehler beschreibt. |
| innerException | java.lang.RuntimeException | Die Ausnahme, die die Ursache der aktuellen Ausnahme ist. |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```


Initialisiert eine neue Instanz der [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) Klasse mit einer angegebenen Fehlermeldung und einer ungültigen Zellreferenz.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | java.lang.String | Eine Zeichenkette, die den Fehler beschreibt. |
| reference | java.lang.String | Eine ungültige Zellreferenz. |

### getReference() {#getReference--}
```
public final String getReference()
```


Gibt eine ungültige Zellreferenz zurück.

**Rückgabe:**
java.lang.String