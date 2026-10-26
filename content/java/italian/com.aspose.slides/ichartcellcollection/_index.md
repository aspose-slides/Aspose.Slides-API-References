---
title: IChartCellCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una raccolta di celle con dati.
type: docs
url: /it/com.aspose.slides/ichartcellcollection/
---
**Tutte le interfacce implementate:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

Rappresenta una raccolta di celle con dati.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Restituisce l'indirizzo dell'insieme di celle nella cartella di lavoro. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Stringa di concatenazione dei valori stringa di tutte le celle. |
| [get_Item(int index)](#get-Item-int-) | Restituisce una cella (IChartDataCell) per indice. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Aggiunge una nuova cella alla raccolta. |
| [add(Object value)](#add-java.lang.Object-) | Crea [IChartDataCell](../../com.aspose.slides/ichartdatacell) dal valore specificato e lo aggiunge alla raccolta. |
| [removeAt(int index)](#removeAt-int-) | Rimuove una cella dalla raccolta per indice. |
| [getCount()](#getCount--) | Restituisce il conteggio delle celle nella raccolta. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```


Restituisce l'indirizzo dell'insieme di celle nella cartella di lavoro.

**Restituisce:**
java.lang.String - Indirizzo dell'insieme di celle nella cartella di lavoro String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```


Stringa di concatenazione dei valori stringa di tutte le celle.

**Restituisce:**
java.lang.String - Stringa risultante String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```


Restituisce una cella (IChartDataCell) per indice.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di una cella. |

**Restituisce:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cella con dati.
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```


Aggiunge una nuova cella alla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nuova cella da aggiungere. |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```


Crea [IChartDataCell](../../com.aspose.slides/ichartdatacell) dal valore specificato e lo aggiunge alla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.Object | Il valore.

--------------------

Questo metodo aggiunge un foglio di lavoro con nome AUTO_DATA e vi inserisce tutti i valori. Se utilizzi [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) per aggiungere o modificare valori di Cell, assicurati di non utilizzare questo foglio di lavoro Il numero massimo di valori aggiunti con questo metodo non deve superare 16711680 |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Rimuove una cella dalla raccolta per indice.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di una cella da rimuovere. |

### getCount() {#getCount--}
```
public abstract int getCount()
```


Restituisce il conteggio delle celle nella raccolta. Solo lettura int.

**Restituisce:**
int