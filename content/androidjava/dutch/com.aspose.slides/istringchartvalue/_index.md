---
title: IStringChartValue
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stel een tekenreekswaarde voor die op twee manieren kan worden opgeslagen in een pptx-presentatiedocument: 1) in cel(len) van een werkmap die gerelateerd is aan een diagram; 2) als letterlijke waarde.
type: docs
url: /nl/com.aspose.slides/istringchartvalue/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

Stelt een tekenreekswaarde voor die kan worden opgeslagen in een pptx-presentatiedocument op twee manieren: 1) in cel(len) van een werkmap die gerelateerd is aan een diagram; 2) als letterlijke waarde.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Geeft de letterlijke tekenreeks terug of stelt deze in als de eigenschap DataSourceType gelijk is aan DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Geeft de letterlijke tekenreeks terug of stelt deze in als de eigenschap DataSourceType gelijk is aan DataSourceType.StringLiterals. |
| [toString()](#toString--) | Geeft de tekenreeksrepresentatie terug. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Stelt de waarde in vanuit de opgegeven cel. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Als de eigenschap DataSourceType gelijk is aan DataSourceType.Worksheet dan geeft deze methode het adres terug van de cellen in de werkmap die de tekenreeksgegevens vertegenwoordigen. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```


Geeft de letterlijke tekenreeks terug of stelt deze in als de eigenschap DataSourceType gelijk is aan DataSourceType.StringLiterals. Lezen/schrijven String.

**Retour:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```


Geeft de letterlijke tekenreeks terug of stelt deze in als de eigenschap DataSourceType gelijk is aan DataSourceType.StringLiterals. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```


Geeft de tekenreeksrepresentatie terug.

**Retour:**
java.lang.String - String representation of a value String
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


Als de eigenschap DataSourceType gelijk is aan DataSourceType.Worksheet dan geeft deze methode het adres terug van de cellen in de werkmap die de tekenreeksgegevens vertegenwoordigen. Anders wordt een lege tekenreeks geretourneerd.

**Retour:**
java.lang.String - String value String