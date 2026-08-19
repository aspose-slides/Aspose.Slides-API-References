---
title: StringOrDoubleChartValue
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un valore stringa o double che può essere memorizzato in un documento di presentazione pptx in due modi: 1) in cella/e del foglio di lavoro relativo al grafico; 2) come valore letterale.
type: docs
url: /it/com.aspose.slides/stringordoublechartvalue/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Tutte le interfacce implementate:**
[com.aspose.slides.IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
```
public class StringOrDoubleChartValue extends BaseChartValue implements IStringOrDoubleChartValue
```

Rappresenta un valore stringa o double che può essere memorizzato in un documento di presentazione pptx in due modi: 1) in cella/e del foglio di lavoro relativo al grafico; 2) come valore letterale.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAsCell()](#getAsCell--) | Restituisce o imposta la cella dati del grafico. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Restituisce o imposta la cella dati del grafico. |
| [getAsLiteralString()](#getAsLiteralString--) | Restituisce o imposta il valore come stringa letterale. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Restituisce o imposta il valore come stringa letterale. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Restituisce o imposta il valore come double letterale. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Restituisce o imposta il valore come double letterale. |
| [getData()](#getData--) | Restituisce o imposta l'oggetto Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Restituisce o imposta l'oggetto Data. |
| [toDouble()](#toDouble--) | Converte in double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```


Restituisce o imposta la cella dati del grafico. Lettura/Scrittura [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Restituisce:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```


Restituisce o imposta la cella dati del grafico. Lettura/Scrittura [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```


Restituisce o imposta il valore come stringa letterale. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```


Restituisce o imposta il valore come stringa letterale. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```


Restituisce o imposta il valore come double letterale. Lettura/Scrittura double.

**Restituisce:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```


Restituisce o imposta il valore come double letterale. Lettura/Scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```


Restituisce o imposta l'oggetto Data. Lettura/Scrittura Object.

**Restituisce:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```


Restituisce o imposta l'oggetto Data. Lettura/Scrittura Object.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.Object |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```


Converte in double.

**Restituisce:**
double - Double value.