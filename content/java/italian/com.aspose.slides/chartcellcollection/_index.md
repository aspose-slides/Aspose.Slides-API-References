---
title: ChartCellCollection
second_title: Riferimento API Aspose.Slides per Java
description: Rappresenta una raccolta di celle con dati.
type: docs
url: /it/com.aspose.slides/chartcellcollection/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

Rappresenta una raccolta di celle con dati.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Restituisce l'indirizzo del gruppo di celle nella cartella di lavoro. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Stringa di concatenazione di tutti i valori stringa delle celle. |
| [get_Item(int index)](#get-Item-int-) | Restituisce una cella (IChartDataCell) per indice. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | Aggiunge una nuova cella alla raccolta. |
| [add(Object value)](#add-java.lang.Object-) | Crea [ChartDataCell](../../com.aspose.slides/chartdatacell) dal valore specificato e lo aggiunge alla raccolta. |
| [removeAt(int index)](#removeAt-int-) | Rimuove una cella dalla raccolta per indice. |
| [getCount()](#getCount--) | Restituisce il numero di celle nella raccolta. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la raccolta. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera raccolta. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```

Restituisce l'indirizzo del gruppo di celle nella cartella di lavoro.

**Restituisce:**
java.lang.String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```

Stringa di concatenazione di tutti i valori stringa delle celle.

**Restituisce:**
java.lang.String
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```

Restituisce una cella (IChartDataCell) per indice.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della cella. |

**Restituisce:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cella con dati.
### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```

Aggiunge una nuova cella alla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nuova cella da aggiungere. |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```

Crea [ChartDataCell](../../com.aspose.slides/chartdatacell) dal valore specificato e lo aggiunge alla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.Object | Il valore.

--------------------

Questo metodo aggiunge un foglio di lavoro con nome AUTO_DATA e vi aggiunge tutti i valori. Se usi [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) per aggiungere o modificare i valori delle Celle, assicurati di non utilizzare questo foglio di lavoro. Il numero massimo di valori aggiunti con questo metodo non deve superare 16711680 |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove una cella dalla raccolta per indice.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della cella da rimuovere. |
### getCount() {#getCount--}
```
public final int getCount()
```

Restituisce il numero di celle nella raccolta. int di sola lettura.

**Restituisce:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```

Restituisce un enumeratore che itera attraverso la raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Un IGenericEnumerator che può essere usato per iterare attraverso la raccolta.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```

Restituisce un iteratore java per l'intera raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Un java.util.Iterator per l'intera raccolta.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. IDOMObject di sola lettura.

**Restituisce:**
com.aspose.slides.IDOMObject