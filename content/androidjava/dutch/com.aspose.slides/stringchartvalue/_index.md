---
title: StringChartValue
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een tekenreekswaarde voor die op twee manieren in een pptx-presentatiedocument kan worden opgeslagen: 1) in cel/cellen van de werkmap die aan een diagram gerelateerd zijn 2) als letterlijke waarde.
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

Representeert een tekenreekswaarde die op twee manieren kan worden opgeslagen in een pptx-presentatiedocument: 1) in cel/cellen van de werkmap die gerelateerd is aan een diagram; 2) als letterlijke waarde.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAsCells()](#getAsCells--) | Het toewijzen van een null-waarde is niet toegestaan. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | Het toewijzen van een null-waarde is niet toegestaan. |
| [getAsLiteralString()](#getAsLiteralString--) | Retourneert of stelt de waarde in als letterlijke tekenreeks. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Retourneert of stelt de waarde in als letterlijke tekenreeks. |
| [getData()](#getData--) | Retourneert of stelt een Data-object in. |
| [setData(Object value)](#setData-java.lang.Object-) | Retourneert of stelt een Data-object in. |
| [toString()](#toString--) | Retourneert tekenreekswaarde-data. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Stelt de waarde in vanuit opgegeven cel. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Als de eigenschap DataSourceType gelijk is aan DataSourceType.Worksheet, retourneert deze methode het adres van de cellen in de werkmap die de tekenreeksgegevens vertegenwoordigen. |
### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

Het toewijzen van een null-waarde is niet toegestaan. De geretourneerde waarde is altijd niet null. Lezen/schrijven [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Retour:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

Het toewijzen van een null-waarde is niet toegestaan. De geretourneerde waarde is altijd niet null. Lezen/schrijven [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Retourneert of stelt de waarde in als letterlijke tekenreeks. Lezen/schrijven String.

**Retour:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Retourneert of stelt de waarde in als letterlijke tekenreeks. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```

Retourneert of stelt een Data-object in. Lezen/schrijven Object.

**Retour:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Retourneert of stelt een Data-object in. Lezen/schrijven Object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```

Retourneert tekenreekswaarde-data. Retourneer null als DataSourceType onwaar is en er geen tekenreekswaarde is toegewezen.

**Retour:**
java.lang.String
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

Stelt de waarde in vanuit opgegeven cel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cel. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

Als de eigenschap DataSourceType gelijk is aan DataSourceType.Worksheet, retourneert deze methode het adres van de cellen in de werkmap die de tekenreeksgegevens vertegenwoordigen. Anders wordt een lege tekenreeks geretourneerd.

**Retour:**
java.lang.String