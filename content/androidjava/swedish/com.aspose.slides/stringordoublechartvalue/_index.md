---
title: StringOrDoubleChartValue
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en sträng- eller dubbelvärde som kan lagras i pptx-presentationsdokument på två sätt: 1) i cell/celler i arbetsbok relaterad till diagram 2) som ett bokstavligt värde.
type: docs
url: /sv/com.aspose.slides/stringordoublechartvalue/
---
**Arv:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
```
public class StringOrDoubleChartValue extends BaseChartValue implements IStringOrDoubleChartValue
```

Representerar en sträng- eller dubbelvärde som kan lagras i pptx-presentationsdokument på två sätt: 1) i cell/celler i arbetsbok relaterad till diagram; 2) som ett bokstavligt värde.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAsCell()](#getAsCell--) | Returnerar eller anger diagramdata cell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Returnerar eller anger diagramdata cell. |
| [getAsLiteralString()](#getAsLiteralString--) | Returnerar eller anger värde som bokstavlig sträng. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Returnerar eller anger värde som bokstavlig sträng. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Returnerar eller anger värde som bokstavligt double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Returnerar eller anger värde som bokstavligt double. |
| [getData()](#getData--) | Returnerar eller anger Data-objekt. |
| [setData(Object value)](#setData-java.lang.Object-) | Returnerar eller anger Data-objekt. |
| [toDouble()](#toDouble--) | Konverterar till double. |
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
### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Returnerar eller anger värde som bokstavlig sträng. Läs/skriv String.

**Returnerar:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Returnerar eller anger värde som bokstavlig sträng. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

Returnerar eller anger värde som bokstavligt double. Läs/skriv double.

**Returnerar:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

Returnerar eller anger värde som bokstavligt double. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getData() {#getData--}
```
public Object getData()
```

Returnerar eller anger Data-objekt. Läs/skriv Object.

**Returnerar:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Returnerar eller anger Data-objekt. Läs/skriv Object.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.Object |  |
### toDouble() {#toDouble--}
```
public final double toDouble()
```

Konverterar till double.

**Returnerar:**
double - Dubbelvärde.