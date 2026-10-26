---
title: CellInvalidReferenceException
second_title: Aspose.Slides voor Android via Java API-referentie
description: De exceptie die wordt gegooid wanneer een ongeldige celreferentie wordt aangetroffen.
type: docs
url: /nl/com.aspose.slides/cellinvalidreferenceexception/
---
**Erfenis:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

De exceptie die wordt gegooid wanneer een ongeldige celreferentie wordt aangetroffen.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | Initialiseert een nieuw exemplaar van de [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) klasse. |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | Initialiseert een nieuw exemplaar van de [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) klasse met een opgegeven foutmelding. |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | Initialiseert een nieuw exemplaar van de [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) klasse met een opgegeven foutmelding en een verwijzing naar de binnenste exceptie die de oorzaak van deze exceptie is. |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | Initialiseert een nieuw exemplaar van de [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klasse met een opgegeven foutmelding en een ongeldige celreferentie. |
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getReference()](#getReference--) | Haalt een ongeldige celreferentie op. |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```


Initialiseert een nieuw exemplaar van de [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) klasse.

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```


Initialiseert een nieuw exemplaar van de [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) klasse met een opgegeven foutmelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | java.lang.String | Een string die de fout beschrijft. |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```


Initialiseert een nieuw exemplaar van de [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) klasse met een opgegeven foutmelding en een verwijzing naar de binnenste exceptie die de oorzaak van deze exceptie is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | java.lang.String | Een string die de fout beschrijft. |
| innerException | java.lang.RuntimeException | De exceptie die de oorzaak is van de huidige exceptie. |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```


Initialiseert een nieuw exemplaar van de [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) klasse met een opgegeven foutmelding en een ongeldige celreferentie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | java.lang.String | Een string die de fout beschrijft. |
| reference | java.lang.String | Een ongeldige celreferentie. |

### getReference() {#getReference--}
```
public final String getReference()
```


Haalt een ongeldige celreferentie op.

**Retourwaarde:**
java.lang.String