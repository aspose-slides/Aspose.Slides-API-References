---
title: ChartCellCollection
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta una collezione di celle con dati.
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

Rappresenta una collezione di celle con dati.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Restituisce l'indirizzo del set di celle nella cartella di lavoro. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Stringa di concatenazione dei valori stringa di tutte le celle. |
| [get_Item(int index)](#get-Item-int-) | Restituisce una cella (IChartDataCell) per indice. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | Aggiunge una nuova cella alla collezione. |
| [add(Object value)](#add-java.lang.Object-) | Crea [ChartDataCell](../../com.aspose.slides/chartdatacell) dal valore specificato e lo aggiunge alla collezione. |
| [removeAt(int index)](#removeAt-int-) | Rimuove una cella dalla collezione per indice. |
| [getCount()](#getCount--) | Ottiene il conteggio delle celle nella collezione. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera collezione. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```


Restituisce l'indirizzo del set di celle nella cartella di lavoro.

**Restituisce:**
java.lang.String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```


Stringa di concatenazione dei valori stringa di tutte le celle.

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
| index | int | Indice di una cella. |

**Restituisce:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cella con dati.
### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```


Aggiunge una nuova cella alla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nuova cella da aggiungere. |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```


Crea [ChartDataCell](../../com.aspose.slides/chartdatacell) dal valore specificato e lo aggiunge alla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.Object | Il valore.

--------------------

Questo metodo aggiunge un foglio di lavoro con nome AUTO_DATA e vi aggiunge tutti i valori. Se utilizzi [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) per aggiungere o modificare i valori delle celle, assicurati di non utilizzare questo foglio di lavoro. Il numero massimo di valori aggiunti con questo metodo non deve superare 16711680 |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Rimuove una cella dalla collezione per indice.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di una cella da rimuovere. |

### getCount() {#getCount--}
```
public final int getCount()
```


Ottiene il conteggio delle celle nella collezione. Solo lettura int.

**Restituisce:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```


Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```


Restituisce un iteratore java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Un java.util.Iterator per l'intera collezione.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject