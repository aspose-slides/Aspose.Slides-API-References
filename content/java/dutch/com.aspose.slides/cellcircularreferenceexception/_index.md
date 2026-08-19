---
title: CellCircularReferenceException
second_title: Aspose.Slides voor Java API-referentie
description: De uitzondering die wordt gegooid wanneer een of meer circulaire referenties worden gedetecteerd waarbij een formule direct of indirect naar zijn eigen cel verwijst.
type: docs
url: /nl/com.aspose.slides/cellcircularreferenceexception/
---
**Erfenis:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

De uitzondering die wordt gegooid wanneer één of meer cyclische referenties worden gedetecteerd waarbij een formule naar zijn eigen cel verwijst, direct of indirect.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | Initialiseert een nieuw exemplaar van de [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klasse. |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | Initialiseert een nieuw exemplaar van de [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klasse met een opgegeven foutbericht. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | Initialiseert een nieuw exemplaar van de [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klasse met een opgegeven foutbericht en een verwijzing naar de onderliggende uitzondering die de oorzaak is van deze uitzondering. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | Initialiseert een nieuw exemplaar van de [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klasse met een opgegeven foutbericht en een circulaire celreferentie. |
## Methods

| Methode | Beschrijving |
| --- | --- |
| [getReference()](#getReference--) | Haalt een circulaire celreferentie op. |
### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

Initialiseert een nieuw exemplaar van de [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klasse.

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

Initialiseert een nieuw exemplaar van de [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klasse met een opgegeven foutbericht.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | java.lang.String | Een string die de fout beschrijft. |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

Initialiseert een nieuw exemplaar van de [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klasse met een opgegeven foutbericht en een verwijzing naar de onderliggende uitzondering die de oorzaak is van deze uitzondering.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | java.lang.String | Een string die de fout beschrijft. |
| innerException | java.lang.RuntimeException | De uitzondering die de oorzaak is van de huidige uitzondering. |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

Initialiseert een nieuw exemplaar van de [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klasse met een opgegeven foutbericht en een circulaire celreferentie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | java.lang.String | Een string die de fout beschrijft. |
| reference | java.lang.String | Een circulaire celreferentie. |

### getReference() {#getReference--}
```
public final String getReference()
```

Haalt een circulaire celreferentie op.

**Retourwaarde:**
java.lang.String