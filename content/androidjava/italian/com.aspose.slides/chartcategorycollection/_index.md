---
title: ChartCategoryCollection
second_title: Aspose.Slides per Android via Riferimento API Java
description: Rappresenta una raccolta di
type: docs
url: /it/com.aspose.slides/chartcategorycollection/
---
**Eredita da:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

Rappresenta una raccolta di [ChartCategory](../../com.aspose.slides/chartcategory)
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [getUseCells()](#getUseCells--) | Se true, il foglio di lavoro è usato per memorizzare le categorie (questo caso supporta categorie a più livelli). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Se true, il foglio di lavoro è usato per memorizzare le categorie (questo caso supporta categorie a più livelli). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Restituisce il conteggio dei livelli di raggruppamento delle categorie utilizzati. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Se la categoria esiste nella raccolta, la restituisce. |
| [add(Object value)](#add-java.lang.Object-) | Crea un nuovo [ChartCategory](../../com.aspose.slides/chartcategory) dal valore e lo aggiunge alla raccolta. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Cerca il [ChartCategory](../../com.aspose.slides/chartcategory) specificato e restituisce l'indice basato su zero della prima occorrenza nell'intera Collection. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Rimuove il valore specificato. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice fornito. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla raccolta. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la raccolta. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore Java per l'intera raccolta. |
| [size()](#size--) | Restituisce il numero di elementi nella raccolta. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi della raccolta nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla List è sincronizzato (thread safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce un oggetto che può essere usato per sincronizzare l'accesso alla raccolta. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

Ottiene l'elemento all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - L'elemento all'indice specificato.
### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

Se true, il foglio di lavoro è usato per memorizzare le categorie (questo caso supporta categorie a più livelli). Se false, il foglio di lavoro NON è usato per memorizzare i valori (e questo caso non supporta categorie a più livelli). Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

Se true, il foglio di lavoro è usato per memorizzare le categorie (questo caso supporta categorie a più livelli). Se false, il foglio di lavoro NON è usato per memorizzare i valori (e questo caso non supporta categorie a più livelli). Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

Restituisce il conteggio dei livelli di raggruppamento delle categorie usati. È più di uno per categorie a più livelli. Solo lettura int.

**Restituisce:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

Se la categoria esiste nella raccolta, la restituisce. Altrimenti crea una nuova categoria del grafico da [IChartDataCell](../../com.aspose.slides/ichartdatacell) e la aggiunge alla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cella usata per creare la categoria del grafico. |

**Restituisce:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Categoria aggiunta o esistente.
### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

Crea un nuovo [ChartCategory](../../com.aspose.slides/chartcategory) dal valore e lo aggiunge alla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.Object | Il valore.

--------------------

Questo metodo aggiunge un foglio di lavoro con nome AUTO_DATA e vi aggiunge tutti i valori. Se utilizzi [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) per aggiungere o modificare i valori delle celle, assicurati di non usare questo foglio di lavoro. Il numero massimo di valori aggiunti con questo metodo non deve superare 16711680

**Restituisce:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - [IChartCategory](../../com.aspose.slides/ichartcategory) aggiunto.
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

Cerca il [ChartCategory](../../com.aspose.slides/chartcategory) specificato e restituisce l'indice basato su zero della prima occorrenza nell'intera Collection.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Categoria del grafico. |

**Restituisce:**
int - L'indice basato su zero della prima occorrenza del valore nell'intera CollectionBase, se trovato; altrimenti, -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

Rimuove il valore specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Il valore. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove l'elemento all'indice fornito.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della categoria da rimuovere. |
### clear() {#clear--}
```
public final void clear()
```

Rimuove tutti gli elementi dalla raccolta.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

Restituisce un enumeratore che itera attraverso la raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Un IGenericEnumerator che può essere usato per iterare attraverso la raccolta.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

Restituisce un iteratore java per l'intera raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Un java.util.Iterator per l'intera raccolta.
### size() {#size--}
```
public final int size()
```

Restituisce il numero di elementi nella raccolta. Solo lettura int.

**Restituisce:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia tutti gli elementi della raccolta nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione. |
| index | int | Indice di partenza nell'array. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Restituisce un valore che indica se l'accesso alla List è sincronizzato (thread safe). Solo lettura boolean.

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Restituisce un oggetto che può essere usato per sincronizzare l'accesso alla raccolta. Solo lettura Object.

Restituisce una radice di sincronizzazione. Solo lettura Object.

**Restituisce:**
java.lang.Object