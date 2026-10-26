---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar sträng- eller dubbelvärde som kan lagras i pptx-presentationdokument på två sätt: 1) i cell/celler i arbetsbok relaterad till diagram 2) som bokstavligt värde.
type: docs
url: /sv/com.aspose.slides/istringordoublechartvalue/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

Representerar sträng- eller dubbelvärde som kan lagras i pptx-presentationdokument på två sätt: 1) i cell/celler i arbetsbok relaterad till diagram; 2) som ett bokstavligt värde.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Returnerar eller anger den bokstavliga strängen om egenskapen DataSourceType är DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Returnerar eller anger den bokstavliga strängen om egenskapen DataSourceType är DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Returnerar eller anger den bokstavliga double om egenskapen DataSourceType är DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Returnerar eller anger den bokstavliga double om egenskapen DataSourceType är DataSourceType.DoubleLiterals. |
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

Returnerar eller anger den bokstavliga double om egenskapen DataSourceType är DataSourceType.DoubleLiterals. Läs/skriv double.

**Returnerar:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Returnerar eller anger den bokstavliga double om egenskapen DataSourceType är DataSourceType.DoubleLiterals. Läs/skriv double.

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
double - Dubbelvärde double