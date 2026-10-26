---
title: CellCircularReferenceException
second_title: Aspose.Slides för Android via Java API-referens
description: Undantaget som kastas när en eller flera cirkulära referenser upptäcks där en formel refererar till sin egen cell antingen direkt eller indirekt.
type: docs
url: /sv/com.aspose.slides/cellcircularreferenceexception/
---
**Arv:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

Undantaget som kastas när en eller flera cirkulära referenser upptäcks där en formel hänvisar till sin egen cell antingen direkt eller indirekt.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | Initierar en ny instans av [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klass. |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | Initierar en ny instans av [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klass med ett specificerat felmeddelande. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | Initierar en ny instans av [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klass med ett specificerat felmeddelande och en referens till det inre undantaget som är orsaken till detta undantag. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | Initierar en ny instans av [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klass med ett specificerat felmeddelande och en cirkulär cellreferens. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getReference()](#getReference--) | Hämtar en cirkulär cellreferens. |
### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

Initierar en ny instans av [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klass.

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

Initierar en ny instans av [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klass med ett specificerat felmeddelande.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| message | java.lang.String | En sträng som beskriver felet. |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

Initierar en ny instans av [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klass med ett specificerat felmeddelande och en referens till det inre undantaget som är orsaken till detta undantag.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| message | java.lang.String | En sträng som beskriver felet. |
| innerException | java.lang.RuntimeException | Undantaget som är orsaken till det aktuella undantaget. |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

Initierar en ny instans av [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klass med ett specificerat felmeddelande och en cirkulär cellreferens.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| message | java.lang.String | En sträng som beskriver felet. |
| reference | java.lang.String | En cirkulär cellreferens. |

### getReference() {#getReference--}
```
public final String getReference()
```

Hämtar en cirkulär cellreferens.

**Returnerar:**
java.lang.String