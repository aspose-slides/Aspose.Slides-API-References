---
title: IDoubleChartValue
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un valore double che può essere memorizzato in un documento di presentazione pptx in due modi: 1) in cella/celle della cartella di lavoro collegata al grafico; 2) come valore letterale.
type: docs
url: /it/com.aspose.slides/idoublechartvalue/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

Rappresenta un valore double che può essere memorizzato nel documento di presentazione pptx in due modi: 1) in cella/celle della cartella di lavoro legate al grafico; 2) come valore letterale.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Restituisce o imposta il valore double letterale se DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Restituisce o imposta il valore double letterale se DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Converte a double. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

Restituisce o imposta il valore double letterale se DataSourceType = Charts.DataSourceType.DoubleLiterals. Lettura/scrittura double.

**Restituisce:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Restituisce o imposta il valore double letterale se DataSourceType = Charts.DataSourceType.DoubleLiterals. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Converte a double.

**Restituisce:**
double - Valore double.