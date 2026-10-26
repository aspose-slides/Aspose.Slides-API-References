---
title: StringChartValue
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een tekenreekswaarde voor die kan worden opgeslagen in een pptx-presentatiedocument op twee manieren: 1) in cel/cellen van een werkmap die gerelateerd is aan een diagram; 2) als letterlijke waarde.
type: docs
url: /nl/com.aspose.slides/stringchartvalue/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

Stelt een tekenreekswaarde voor die kan worden opgeslagen in een pptx-presentatiedocument op twee manieren: 1) in cel/cellen van een werkmap die gerelateerd is aan een diagram; 2) als letterlijke waarde.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAsCells()](#getAsCells--) | Toewijzing van een nulwaarde is niet toegestaan. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | Toewijzing van een nulwaarde is niet toegestaan. |
| [getAsLiteralString()](#getAsLiteralString--) | Retourneert of stelt de waarde in als letterlijke tekenreeks. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Retourneert of stelt de waarde in als letterlijke tekenreeks. |
| [getData()](#getData--) | Retourneert of stelt het Data-object in. |
| [setData(Object value)](#setData-java.lang.Object-) | Retourneert of stelt het Data-object in. |
| [toString()](#toString--) | Retourneert tekenreekswaardegegevens. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Stelt de waarde in vanuit de opgegeven cel. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Als de eigenschap DataSourceType gelijk is aan DataSourceType.Worksheet, retourneert deze methode het adres van de cellen in de werkmap die de tekenreeksgegevens vertegenwoordigen. |
### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```


Toewijzing van een nulwaarde is niet toegestaan. De geretourneerde waarde is altijd niet nul. Lezen/Schrijven [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Retourwaarde:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```


Toewijzing van een nulwaarde is niet toegestaan. De geretourneerde waarde is altijd niet nul. Lezen/Schrijven [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```


Retourneert of stelt de waarde in als letterlijke tekenreeks. Lezen/Schrijven String.

**Retourwaarde:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```


Retourneert of stelt de waarde in als letterlijke tekenreeks. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```


Retourneert of stelt het Data-object in. Lezen/Schrijven Object.

**Retourwaarde:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```


Retourneert of stelt het Data-object in. Lezen/Schrijven Object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```


Retourneert tekenreekswaardegegevens. Retourneert null als DataSourceType false is en er geen tekenreekswaarde is toegewezen.

**Retourwaarde:**
java.lang.String
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```


Stelt de waarde in vanuit de opgegeven cel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cel. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```


Als de eigenschap DataSourceType gelijk is aan DataSourceType.Worksheet, retourneert deze methode het adres van de cellen in de werkmap die de tekenreeksgegevens vertegenwoordigen. Anders wordt een lege tekenreeks geretourneerd.

**Retourwaarde:**
java.lang.String