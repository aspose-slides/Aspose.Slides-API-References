---
title: CellInvalidFormulaException
second_title: Aspose.Slides für Android über Java API Referenz
description: Die Ausnahme, die ausgelöst wird, wenn eine berechnete Formel nicht korrekt ist oder nicht geparst werden konnte.
type: docs
url: /de/com.aspose.slides/cellinvalidformulaexception/
---
**Vererbung:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

Die Ausnahme, die ausgelöst wird, wenn eine berechnete Formel nicht korrekt ist oder nicht geparst werden konnte.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | Initialisiert eine neue Instanz der [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) Klasse. |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | Initialisiert eine neue Instanz der [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) Klasse mit einer angegebenen Fehlermeldung. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | Initialisiert eine neue Instanz der [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die die Ursache dieser Ausnahme ist. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | Initialisiert eine neue Instanz der [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) Klasse mit einer angegebenen Fehlermeldung und einer Zellreferenz, die die ungültige Formel enthält. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getReference()](#getReference--) | Ermittelt eine Zellreferenz, die die ungültige Formel enthält. |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```


Initialisiert eine neue Instanz der [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) Klasse.

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```


Initialisiert eine neue Instanz der [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) Klasse mit einer angegebenen Fehlermeldung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | java.lang.String | Ein String, der den Fehler beschreibt. |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```


Initialisiert eine neue Instanz der [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die die Ursache dieser Ausnahme ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | java.lang.String | Ein String, der den Fehler beschreibt. |
| innerException | java.lang.RuntimeException | Die Ausnahme, die die Ursache der aktuellen Ausnahme ist. |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```


Initialisiert eine neue Instanz der [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) Klasse mit einer angegebenen Fehlermeldung und einer Zellreferenz, die die ungültige Formel enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | java.lang.String | Ein String, der den Fehler beschreibt. |
| reference | java.lang.String | Ein String, der eine Referenz auf die innere Ausnahme beschreibt. |

### getReference() {#getReference--}
```
public final String getReference()
```


Ermittelt eine Zellreferenz, die die ungültige Formel enthält.

**Rückgabe:**
java.lang.String