---
title: CellInvalidFormulaException
second_title: Aspose.Slides för Java API-referens
description: Undantaget som kastas när en beräknad formel inte är korrekt eller inte kunde parsas.
type: docs
url: /sv/com.aspose.slides/cellinvalidformulaexception/
---
**Arv:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

Undantaget som kastas när en beräknad formel inte är korrekt eller inte kunde parsas.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | Initierar en ny instans av klassen [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception). |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | Initierar en ny instans av klassen [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) med ett specificerat felmeddelande. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | Initierar en ny instans av klassen [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) med ett specificerat felmeddelande och en referens till det inre undantaget som är orsaken till detta undantag. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | Initierar en ny instans av klassen [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) med ett specificerat felmeddelande och en cellreferens som innehåller den ogiltiga formeln. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getReference()](#getReference--) | Hämtar en cellreferens som innehåller den ogiltiga formeln. |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```


Initierar en ny instans av klassen [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception).

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```


Initierar en ny instans av klassen [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) med ett specificerat felmeddelande.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| message | java.lang.String | En sträng som beskriver felet. |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```


Initierar en ny instans av klassen [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) med ett specificerat felmeddelande och en referens till det inre undantaget som är orsaken till detta undantag.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| message | java.lang.String | En sträng som beskriver felet. |
| innerException | java.lang.RuntimeException | Undantaget som är orsaken till det aktuella undantaget. |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```


Initierar en ny instans av klassen [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) med ett specificerat felmeddelande och en cellreferens som innehåller den ogiltiga formeln.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| message | java.lang.String | En sträng som beskriver felet. |
| reference | java.lang.String | En sträng som beskriver en referens till det inre undantaget |

### getReference() {#getReference--}
```
public final String getReference()
```


Hämtar en cellreferens som innehåller den ogiltiga formeln.

**Returnerar:**
java.lang.String