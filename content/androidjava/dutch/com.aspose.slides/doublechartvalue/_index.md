---
title: DoubleChartValue
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt dubbele waarde voor die in een pptx-presentatiedocument op twee manieren kan worden opgeslagen: 1) in cel/cellen van een werkmap gerelateerd aan een grafiek; 2) als letterlijke waarde.
type: docs
url: /nl/com.aspose.slides/doublechartvalue/
---
**Overerving:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

Stelt een double-waarde voor die in een pptx-presentatiedocument op twee manieren kan worden opgeslagen: 1) in cel/cellen van een werkmap gerelateerd aan een grafiek; 2) als letterlijke waarde.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAsCell()](#getAsCell--) | Geeft de chart-datacel terug of stelt deze in. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Geeft de chart-datacel terug of stelt deze in. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Geeft de waarde terug of stelt deze in als letterlijke double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Geeft de waarde terug of stelt deze in als letterlijke double. |
| [getData()](#getData--) | Geeft het Data-object terug of stelt dit in. |
| [setData(Object value)](#setData-java.lang.Object-) | Geeft het Data-object terug of stelt dit in. |
| [toDouble()](#toDouble--) | Converteert naar double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Geeft de chart-datacel terug of stelt deze in. Lezen/schrijven [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Retour:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Geeft de chart-datacel terug of stelt deze in. Lezen/schrijven [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

Geeft de waarde terug of stelt deze in als letterlijke double. Lezen/schrijven double.

**Retour:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

Geeft de waarde terug of stelt deze in als letterlijke double. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getData() {#getData--}
```
public Object getData()
```

Geeft het Data-object terug of stelt dit in. Lezen/schrijven Object.

**Retour:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Geeft het Data-object terug of stelt dit in. Lezen/schrijven Object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Object |  |
### toDouble() {#toDouble--}
```
public final double toDouble()
```

Converteert naar double.

**Retour:**
double - Retourneert LiteralDouble als DataSourceType gelijk is aan DoubleLiterals. Als DataSourceType gelijk is aan Worksheet wordt de met succes naar double geconverteerde celwaarde geretourneerd, anders wordt NaN geretourneerd.