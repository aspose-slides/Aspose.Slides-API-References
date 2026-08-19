---
title: IStringChartValue
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een stringwaarde voor die op twee manieren in een pptx-presentatiedocument kan worden opgeslagen: 1) in cel/cellen van de werkmap die gerelateerd is aan de grafiek 2) als letterlijke waarde.
type: docs
url: /nl/com.aspose.slides/istringchartvalue/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

Stelt een stringwaarde voor die op twee manieren in een pptx-presentatiedocument kan worden opgeslagen: 1) in cel/cellen van de werkmap die aan de grafiek gerelateerd is; 2) als letterlijke waarde.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Retourneert of stelt de letterlijke string in als de eigenschap DataSourceType gelijk is aan DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Retourneert of stelt de letterlijke string in als de eigenschap DataSourceType gelijk is aan DataSourceType.StringLiterals. |
| [toString()](#toString--) | Retourneert stringrepresentatie. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Stelt de waarde in vanuit de opgegeven cel. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Als de eigenschap DataSourceType gelijk is aan DataSourceType.Worksheet, retourneert deze methode het adres van de cellen in de werkmap die de stringgegevens vertegenwoordigen. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```


Retourneert of stelt de letterlijke string in als de eigenschap DataSourceType gelijk is aan DataSourceType.StringLiterals. Lezen/schrijven String.

**Retourneert:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```


Retourneert of stelt de letterlijke string in als de eigenschap DataSourceType gelijk is aan DataSourceType.StringLiterals. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```


Retourneert stringrepresentatie.

**Retourneert:**
java.lang.String - Stringrepresentatie van een waarde String
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```


Stelt de waarde in vanuit de opgegeven cel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cel. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```


Als de eigenschap DataSourceType gelijk is aan DataSourceType.Worksheet, retourneert deze methode het adres van de cellen in de werkmap die de stringgegevens vertegenwoordigen. Anders wordt een lege string geretourneerd.

**Retourneert:**
java.lang.String - Stringwaarde String