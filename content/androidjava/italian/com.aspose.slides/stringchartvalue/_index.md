---
title: StringChartValue
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta un valore stringa che può essere memorizzato in un documento di presentazione pptx in due modi: 1) nella/e cella/e della cartella di lavoro correlate al grafico, 2) come valore letterale.
type: docs
url: /it/com.aspose.slides/stringchartvalue/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Tutte le Interfacce Implementate:**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

Rappresenta il valore stringa che può essere memorizzato in un documento di presentazione pptx in due modi: 1) nella/o nelle celle della cartella di lavoro correlate al grafico; 2) come valore letterale.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAsCells()](#getAsCells--) | L'assegnazione di un valore nullo non è consentita. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | L'assegnazione di un valore nullo non è consentita. |
| [getAsLiteralString()](#getAsLiteralString--) | Restituisce o imposta il valore come stringa letterale. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Restituisce o imposta il valore come stringa letterale. |
| [getData()](#getData--) | Restituisce o imposta l'oggetto Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Restituisce o imposta l'oggetto Data. |
| [toString()](#toString--) | Restituisce i dati del valore stringa. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Imposta il valore dalla cella specificata. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Se la proprietà DataSourceType è DataSourceType.Worksheet, questo metodo restituisce l'indirizzo delle celle nella cartella di lavoro che rappresentano i dati stringa. |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

L'assegnazione di un valore nullo non è consentita. Il valore restituito è sempre non nullo. Lettura/scrittura [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Restituisce:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

L'assegnazione di un valore nullo non è consentita. Il valore restituito è sempre non nullo. Lettura/scrittura [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Restituisce o imposta il valore come stringa letterale. Lettura/scrittura String.

**Restituisce:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Restituisce o imposta il valore come stringa letterale. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

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

### toString() {#toString--}
```
public String toString()
```

Restituisce i dati del valore stringa. Restituisce null se DataSourceType è false e nessun valore stringa è stato assegnato.

**Restituisce:**
java.lang.String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

Imposta il valore dalla cella specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cella. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

Se la proprietà DataSourceType è DataSourceType.Worksheet, questo metodo restituisce l'indirizzo delle celle nella cartella di lavoro che rappresentano i dati stringa. Altrimenti restituisce una stringa vuota.

**Restituisce:**
java.lang.String