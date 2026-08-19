---
title: DoubleChartValue
second_title: Aspose.Slides för Java API-referens
description: Representerar ett dubbelvärde som kan lagras i pptx-presentationsdokument på två sätt: 1) i cell/celler i arbetsbok relaterad till diagram; 2) som ett bokstavligt värde.
type: docs
url: /sv/com.aspose.slides/doublechartvalue/
---
**Arv:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

Representerar ett dubbelvärde som kan lagras i pptx-presentationsdokument på två sätt: 1) i cell/celler i arbetsbok relaterad till diagram; 2) som ett bokstavligt värde.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAsCell()](#getAsCell--) | Returnerar eller anger diagramdata cell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Returnerar eller anger diagramdata cell. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Returnerar eller anger värde som bokstavlig dubbel. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Returnerar eller anger värde som bokstavlig dubbel. |
| [getData()](#getData--) | Returnerar eller anger Data-objekt. |
| [setData(Object value)](#setData-java.lang.Object-) | Returnerar eller anger Data-objekt. |
| [toDouble()](#toDouble--) | Konverterar till dubbel. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```


Returnerar eller anger diagramdata cell. Läs/skriv [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```


Returnerar eller anger diagramdata cell. Läs/skriv [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```


Returnerar eller anger värde som bokstavlig dubbel. Läs/skriv dubbel.

**Returnerar:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```


Returnerar eller anger värde som bokstavlig dubbel. Läs/skriv dubbel.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getData() {#getData--}
```
public Object getData()
```


Returnerar eller anger Data-objekt. Läs/skriv Objekt.

**Returnerar:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```


Returnerar eller anger Data-objekt. Läs/skriv Objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.Object |  |
### toDouble() {#toDouble--}
```
public final double toDouble()
```


Konverterar till dubbel.

**Returnerar:**
double - Returnerar LiteralDouble om DataSourceType är lika med DoubleLiterals. Om DataSourceType är lika med Worksheet returneras det framgångsrikt konverterade cellvärdet som dubbel, annars returneras NaN.