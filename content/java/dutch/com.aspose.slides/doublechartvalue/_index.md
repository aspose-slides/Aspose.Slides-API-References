---
title: DoubleChartValue
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een double-waarde voor die kan worden opgeslagen in een pptx-presentatiedocument op twee manieren: 1 in cel/cellen van een werkmap gerelateerd aan grafiek 2 als letterlijke waarde.
type: docs
url: /nl/com.aspose.slides/doublechartvalue/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**All Implemented Interfaces:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

Stelt een double-waarde voor die kan worden opgeslagen in een pptx-presentatiedocument op twee manieren: 1) in cel/cellen van een werkmap gerelateerd aan een grafiek; 2) als letterlijke waarde.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAsCell()](#getAsCell--) | Retourneert of stelt chart-data-cel in. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Retourneert of stelt chart-data-cel in. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Retourneert of stelt waarde in als letterlijke double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Retourneert of stelt waarde in als letterlijke double. |
| [getData()](#getData--) | Retourneert of stelt Data-object in. |
| [setData(Object value)](#setData-java.lang.Object-) | Retourneert of stelt Data-object in. |
| [toDouble()](#toDouble--) | Converteert naar double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Retourneert of stelt chart-data-cel in. Lezen/Schrijven [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Retourneert:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Retourneert of stelt chart-data-cel in. Lezen/Schrijven [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

Retourneert of stelt waarde in als letterlijke double. Lezen/Schrijven double.

**Retourneert:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

Retourneert of stelt waarde in als letterlijke double. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```

Retourneert of stelt Data-object in. Lezen/Schrijven Object.

**Retourneert:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Retourneert of stelt Data-object in. Lezen/Schrijven Object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Object |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```

Converteert naar double.

**Retourneert:**
double - Retourneert LiteralDouble als DataSourceType gelijk is aan DoubleLiterals. Als DataSourceType gelijk is aan Worksheet, retourneert het met succes geconverteerde double-celwaarde, anders retourneert het NaN.