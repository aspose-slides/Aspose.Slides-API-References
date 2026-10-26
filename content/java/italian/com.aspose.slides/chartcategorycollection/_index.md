---
title: ChartCategoryCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta la collezione di
type: docs
url: /it/com.aspose.slides/chartcategorycollection/
---
**Eredità:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

Rappresenta la collezione di [ChartCategory](../../com.aspose.slides/chartcategory)
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Recupera l'elemento nell'indice specificato. |
| [getUseCells()](#getUseCells--) | Se true allora il foglio di lavoro è usato per memorizzare le categorie (questo caso supporta categorie a più livelli). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Se true allora il foglio di lavoro è usato per memorizzare le categorie (questo caso supporta categorie a più livelli). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Restituisce il conteggio dei livelli di raggruppamento delle categorie utilizzati. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Se la categoria esiste nella collezione, la restituisce. |
| [add(Object value)](#add-java.lang.Object-) | Crea un nuovo [ChartCategory](../../com.aspose.slides/chartcategory) dal valore e lo aggiunge alla collezione. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Cerca il [ChartCategory](../../com.aspose.slides/chartcategory) specificato e restituisce l'indice base-zero della prima occorrenza all'interno dell'intera Collection. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Rimuove il valore specificato. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla collezione. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera collezione. |
| [size()](#size--) | Restituisce il numero di elementi nella collezione. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi della collezione nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla List è sincronizzato (thread safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce un oggetto che può essere usato per sincronizzare l'accesso alla collezione. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

Recupera l'elemento nell'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - L'elemento nell'indice specificato.

### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

Se true allora il foglio di lavoro è usato per memorizzare le categorie (questo caso supporta categorie a più livelli). Se false il foglio di lavoro NON è usato per memorizzare valori (e questo caso non supporta categorie a più livelli). Booleano lettura/scrittura.

**Restituisce:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

Se true allora il foglio di lavoro è usato per memorizzare le categorie (questo caso supporta categorie a più livelli). Se false il foglio di lavoro NON è usato per memorizzare valori (e questo caso non supporta categorie a più livelli). Booleano lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

Restituisce il conteggio dei livelli di raggruppamento delle categorie utilizzati. È più di uno per categorie a più livelli. Intero di sola lettura.

**Restituisce:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

Se la categoria esiste nella collezione, la restituisce. Altrimenti crea una nuova categoria di grafico da [IChartDataCell](../../com.aspose.slides/ichartdatacell) e la aggiunge alla collezione.

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

Crea un nuovo [ChartCategory](../../com.aspose.slides/chartcategory) dal valore e lo aggiunge alla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.Object | Il valore. |

--------------------

Questo metodo aggiunge un foglio di lavoro con nome AUTO_DATA e vi aggiunge tutti i valori. Se usi [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) per aggiungere o modificare i valori delle celle, assicurati di non usare questo foglio di lavoro. Il numero massimo di valori aggiunti con questo metodo non deve superare 16711680 |

**Restituisce:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - [IChartCategory](../../com.aspose.slides/ichartcategory) aggiunto.

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

Cerca il [ChartCategory](../../com.aspose.slides/chartcategory) specificato e restituisce l'indice base-zero della prima occorrenza all'interno dell'intera Collection.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Categoria del grafico. |

**Restituisce:**
int - L'indice base-zero della prima occorrenza del valore all'interno dell'intera CollectionBase, se trovato; altrimenti, -1.

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

Rimuove l'elemento all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della categoria da rimuovere. |

### clear() {#clear--}
```
public final void clear()
```

Rimuove tutti gli elementi dalla collezione.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

Restituisce un iteratore java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Un java.util.Iterator per l'intera collezione.

### size() {#size--}
```
public final int size()
```

Restituisce il numero di elementi nella collezione. Intero di sola lettura.

**Restituisce:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia tutti gli elementi della collezione nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione. |
| index | int | Indice di partenza nell'array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Restituisce un valore che indica se l'accesso alla List è sincronizzato (thread safe). Booleano di sola lettura.

**Restituisce:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Restituisce un oggetto che può essere usato per sincronizzare l'accesso alla collezione. Oggetto di sola lettura.

Restituisce una radice di sincronizzazione. Oggetto di sola lettura.

**Restituisce:**
java.lang.Object