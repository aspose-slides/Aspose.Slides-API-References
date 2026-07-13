---
title: CellCircularReferenceException
second_title: Aspose.Slides voor Android via Java API-referentie
description: De uitzondering die wordt gegooid wanneer een of meer circulaire verwijzingen worden gedetecteerd waarbij een formule direct of indirect naar zijn eigen cel verwijst.
type: docs
url: /nl/com.aspose.slides/cellcircularreferenceexception/
---
**Erfenis:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

De uitzondering die wordt gegooid wanneer een of meer circulaire verwijzingen worden gedetecteerd waarbij een formule direct of indirect naar zijn eigen cel verwijst.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | Initialiseert een nieuw exemplaar van de [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klasse. |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | Initialiseert een nieuw exemplaar van de [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klasse met een opgegeven foutbericht. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | Initialiseert een nieuw exemplaar van de [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klasse met een opgegeven foutbericht en een verwijzing naar de binnenste uitzondering die de oorzaak van deze uitzondering is. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | Initialiseert een nieuw exemplaar van de [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klasse met een opgegeven foutbericht en een circulaire celverwijzing. |
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getReference()](#getReference--) | Haalt een circulaire celverwijzing op. |
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

Initialiseert een nieuw exemplaar van de [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klasse met een opgegeven foutbericht en een verwijzing naar de binnenste uitzondering die de oorzaak van deze uitzondering is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | java.lang.String | Een string die de fout beschrijft. |
| innerException | java.lang.RuntimeException | De uitzondering die de oorzaak is van de huidige uitzondering. |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

Initialiseert een nieuw exemplaar van de [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klasse met een opgegeven foutbericht en een circulaire celverwijzing.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | java.lang.String | Een string die de fout beschrijft. |
| reference | java.lang.String | Een circulaire celverwijzing. |

### getReference() {#getReference--}
```
public final String getReference()
```

Haalt een circulaire celverwijzing op.

**Retourwaarde:**
java.lang.String