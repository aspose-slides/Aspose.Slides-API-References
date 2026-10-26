---
title: CellInvalidFormulaException
second_title: Aspose.Slides voor Android via Java API-referentie
description: De uitzondering die wordt gegooid wanneer een berekende formule niet correct is of niet kon worden geparseerd.
type: docs
url: /nl/com.aspose.slides/cellinvalidformulaexception/
---
**Erfenis:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

De uitzondering die wordt gegooid wanneer een berekende formule niet correct is of niet kon worden geparseerd.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | Initialiseert een nieuw exemplaar van de [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) klasse. |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | Initialiseert een nieuw exemplaar van de [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) klasse met een opgegeven foutbericht. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | Initialiseert een nieuw exemplaar van de [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) klasse met een opgegeven foutbericht en een verwijzing naar de binnenste uitzondering die de oorzaak van deze uitzondering is. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | Initialiseert een nieuw exemplaar van de [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) klasse met een opgegeven foutbericht en een celreferentie die de ongeldige formule bevat. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getReference()](#getReference--) | Haalt een celreferentie op die de ongeldige formule bevat. |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

Initialiseert een nieuw exemplaar van de [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) klasse.

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

Initialiseert een nieuw exemplaar van de [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) klasse met een opgegeven foutbericht.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | java.lang.String | Een string die de fout beschrijft. |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

Initialiseert een nieuw exemplaar van de [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) klasse met een opgegeven foutbericht en een verwijzing naar de binnenste uitzondering die de oorzaak van deze uitzondering is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | java.lang.String | Een string die de fout beschrijft. |
| innerException | java.lang.RuntimeException | De uitzondering die de oorzaak is van de huidige uitzondering. |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

Initialiseert een nieuw exemplaar van de [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) klasse met een opgegeven foutbericht en een celreferentie die de ongeldige formule bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | java.lang.String | Een string die de fout beschrijft. |
| reference | java.lang.String | Een string die een verwijzing naar de binnenste uitzondering beschrijft |

### getReference() {#getReference--}
```
public final String getReference()
```

Haalt een celreferentie op die de ongeldige formule bevat.

**Retourneert:**
java.lang.String