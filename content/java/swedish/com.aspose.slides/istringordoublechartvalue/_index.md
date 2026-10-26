---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides för Java API-referens
description: Representerar en sträng- eller dubbelvärde som kan lagras i ett pptx-presentationsdokument på två sätt 1 i cell/celler i en arbetsbok relaterad till diagram 2 som ett bokstavligt värde.
type: docs
url: /sv/com.aspose.slides/istringordoublechartvalue/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

Representerar en sträng- eller dubbelvärde som kan lagras i ett pptx-presentationsdokument på två sätt: 1) i cell/celler i en arbetsbok relaterad till diagram; 2) som ett bokstavligt värde.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Returnerar eller anger den bokstavliga strängen om egenskapen DataSourceType är DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Returnerar eller anger den bokstavliga strängen om egenskapen DataSourceType är DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Returnerar eller anger den bokstavliga dubblen om egenskapen DataSourceType är DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Returnerar eller anger den bokstavliga dubblen om egenskapen DataSourceType är DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Konverterar värdet till double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Returnerar eller anger den bokstavliga strängen om egenskapen DataSourceType är DataSourceType.StringLiterals. Läs/skriv String.

**Returnerar:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Returnerar eller anger den bokstavliga strängen om egenskapen DataSourceType är DataSourceType.StringLiterals. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

Returnerar eller anger den bokstavliga dubblen om egenskapen DataSourceType är DataSourceType.DoubleLiterals. Läs/skriv double.

**Returnerar:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Returnerar eller anger den bokstavliga dubblen om egenskapen DataSourceType är DataSourceType.DoubleLiterals. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Konverterar värdet till double.

**Returnerar:**
double - dubbelvärde double