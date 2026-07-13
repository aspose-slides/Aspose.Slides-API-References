---
title: IStringChartValue
second_title: Aspose.Slides per Android tramite Java API Reference
description: Rappresenta il valore stringa che può essere memorizzato in un documento di presentazione pptx in due modi: 1) in cella/e del foglio di lavoro relativo al grafico; 2) come valore letterale.
type: docs
url: /it/com.aspose.slides/istringchartvalue/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

Rappresenta il valore stringa che può essere memorizzato in un documento di presentazione pptx in due modi: 1) in cella/e del foglio di calcolo relativo al grafico; 2) come valore letterale.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Restituisce o imposta la stringa letterale se la proprietà DataSourceType è DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Restituisce o imposta la stringa letterale se la proprietà DataSourceType è DataSourceType.StringLiterals. |
| [toString()](#toString--) | Restituisce la rappresentazione della stringa. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Imposta il valore dalla cella specificata. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Se la proprietà DataSourceType è DataSourceType.Worksheet questo metodo restituisce l'indirizzo delle celle nel foglio di lavoro che rappresentano i dati stringa. |

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

### toString() {#toString--}
```
public abstract String toString()
```

Restituisce la rappresentazione della stringa.

**Restituisce:**
java.lang.String - Rappresentazione stringa di un valore String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

Imposta il valore dalla cella specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cella. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

Se la proprietà DataSourceType è DataSourceType.Worksheet questo metodo restituisce l'indirizzo delle celle nel foglio di lavoro che rappresentano i dati stringa. Altrimenti restituisce una stringa vuota.

**Restituisce:**
java.lang.String - Valore stringa String