---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta un valore stringa o double che può essere memorizzato in un documento di presentazione pptx in due modi: 1) in cella/e del workbook relativo al grafico; 2) come valore letterale.
type: docs
url: /it/com.aspose.slides/istringordoublechartvalue/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

Rappresenta un valore stringa o double che può essere memorizzato in un documento di presentazione pptx in due modi: 1) in cella/e del foglio di lavoro correlato al grafico; 2) come valore letterale.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Restituisce o imposta la stringa letterale se la proprietà DataSourceType è DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Restituisce o imposta la stringa letterale se la proprietà DataSourceType è DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Restituisce o imposta il double letterale se la proprietà DataSourceType è DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Restituisce o imposta il double letterale se la proprietà DataSourceType è DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Converte il valore in double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```


Restituisce o imposta la stringa letterale se la proprietà DataSourceType è DataSourceType.StringLiterals. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```


Restituisce o imposta la stringa letterale se la proprietà DataSourceType è DataSourceType.StringLiterals. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


Restituisce o imposta il double letterale se la proprietà DataSourceType è DataSourceType.DoubleLiterals. Lettura/scrittura double.

**Restituisce:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


Restituisce o imposta il double letterale se la proprietà DataSourceType è DataSourceType.DoubleLiterals. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Converte il valore in double.

**Restituisce:**
double - Valore double double