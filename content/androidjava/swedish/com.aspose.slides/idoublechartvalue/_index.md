---
title: IDoubleChartValue
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett double-värde som kan lagras i ett pptx-presentationsdokument på två sätt: 1) i cell/celler i arbetsbok relaterad till diagram; 2) som ett bokstavligt värde.
type: docs
url: /sv/com.aspose.slides/idoublechartvalue/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

Representerar ett double-värde som kan lagras i ett pptx-presentationsdokument på två sätt: 1) i cell/celler i arbetsbok relaterad till diagram; 2) som ett bokstavligt värde.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Returnerar eller anger ett bokstavligt double-värde om DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Returnerar eller anger ett bokstavligt double-värde om DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Konverterar till double. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


Returnerar eller anger ett bokstavligt double-värde om DataSourceType = Charts.DataSourceType.DoubleLiterals. Läs/skriv double.

**Returnerar:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


Returnerar eller anger ett bokstavligt double-värde om DataSourceType = Charts.DataSourceType.DoubleLiterals. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Konverterar till double.

**Returnerar:**
double - Double-värde.