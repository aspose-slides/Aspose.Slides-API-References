---
title: CellInvalidReferenceException
second_title: Aspose.Slides för Android via Java API-referens
description: Undantaget som kastas när en ogiltig cellreferens påträffas.
type: docs
url: /sv/com.aspose.slides/cellinvalidreferenceexception/
---
**Arv:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

Undantaget som kastas när en ogiltig cellreferens påträffas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | Skapar en ny instans av klassen [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception). |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | Skapar en ny instans av klassen [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) med ett angivet felmeddelande. |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | Skapar en ny instans av klassen [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) med ett angivet felmeddelande och en referens till det inre undantaget som är orsaken till detta undantag. |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | Skapar en ny instans av klassen [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) med ett angivet felmeddelande och en ogiltig cellreferens. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getReference()](#getReference--) | Hämtar en ogiltig cellreferens. |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```


Skapar en ny instans av klassen [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception).

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```


Skapar en ny instans av klassen [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) med ett angivet felmeddelande.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| message | java.lang.String | En sträng som beskriver felet. |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```


Skapar en ny instans av klassen [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) med ett angivet felmeddelande och en referens till det inre undantaget som är orsaken till detta undantag.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| message | java.lang.String | En sträng som beskriver felet. |
| innerException | java.lang.RuntimeException | Undantaget som är orsaken till det aktuella undantaget. |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```


Skapar en ny instans av klassen [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) med ett angivet felmeddelande och en ogiltig cellreferens.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| message | java.lang.String | En sträng som beskriver felet. |
| reference | java.lang.String | En ogiltig cellreferens. |

### getReference() {#getReference--}
```
public final String getReference()
```


Hämtar en ogiltig cellreferens.

**Returnerar:**
java.lang.String