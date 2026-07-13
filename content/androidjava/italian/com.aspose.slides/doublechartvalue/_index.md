---
title: DoubleChartValue
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un valore double che può essere memorizzato in un documento di presentazione pptx in due modi: 1 in cella/celle della cartella di lavoro relative al grafico 2 come valore letterale.
type: docs
url: /it/com.aspose.slides/doublechartvalue/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Tutte le interfacce implementate:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

Rappresenta un valore double che può essere memorizzato in un documento di presentazione pptx in due modi: 1) in cella/celle della cartella di lavoro relative al grafico; 2) come valore letterale.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAsCell()](#getAsCell--) | Restituisce o imposta la cella dei dati del grafico. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Restituisce o imposta la cella dei dati del grafico. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Restituisce o imposta il valore come double letterale. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Restituisce o imposta il valore come double letterale. |
| [getData()](#getData--) | Restituisce o imposta l'oggetto Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Restituisce o imposta l'oggetto Data. |
| [toDouble()](#toDouble--) | Converte in double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Restituisce o imposta la cella dei dati del grafico. Lettura/scrittura [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Restituisce:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Restituisce o imposta la cella dei dati del grafico. Lettura/scrittura [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

Restituisce o imposta il valore come double letterale. Lettura/scrittura double.

**Restituisce:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

Restituisce o imposta il valore come double letterale. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```

Restituisce o imposta l'oggetto Data. Lettura/scrittura Object.

**Restituisce:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Restituisce o imposta l'oggetto Data. Lettura/scrittura Object.

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
double - Restituisce LiteralDouble se DataSourceType è uguale a DoubleLiterals. Se DataSourceType è uguale a Worksheet restituisce il valore della cella convertito correttamente in double, altrimenti restituisce NaN.