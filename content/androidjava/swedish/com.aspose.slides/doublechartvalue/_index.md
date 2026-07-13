---
title: DoubleChartValue
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett double-värde som kan lagras i ett pptx-presentationsdokument på två sätt 1 i cell/celler i arbetsbok relaterad till diagram 2 som ett bokstavligt värde.
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

Representerar ett double-värde som kan lagras i ett pptx-presentationsdokument på två sätt: 1) i cell/celler i arbetsbok relaterad till diagram; 2) som ett bokstavligt värde.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAsCell()](#getAsCell--) | Returnerar eller ställer in diagramdatacell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Returnerar eller ställer in diagramdatacell. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Returnerar eller ställer in värde som bokstavligt double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Returnerar eller ställer in värde som bokstavligt double. |
| [getData()](#getData--) | Returnerar eller ställer in Data object. |
| [setData(Object value)](#setData-java.lang.Object-) | Returnerar eller ställer in Data object. |
| [toDouble()](#toDouble--) | Konverterar till double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Returnerar eller ställer in diagramdatacell. Läsa/skriva [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Returnerar eller ställer in diagramdatacell. Läsa/skriva [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

Returnerar eller ställer in värde som bokstavligt double. Läsa/skriva double.

**Returnerar:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

Returnerar eller ställer in värde som bokstavligt double. Läsa/skriva double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```

Returnerar eller ställer in Data object. Läsa/skriva Object.

**Returnerar:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Returnerar eller ställer in Data object. Läsa/skriva Object.

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
double - Returnerar LiteralDouble om DataSourceType är lika med DoubleLiterals. Om DataSourceType är lika med Worksheet returneras framgångsrikt konverterat till double-cellvärde, annars returneras NaN.