---
title: IChartCategoryCollection
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una collezione di
type: docs
url: /it/com.aspose.slides/ichartcategorycollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

Rappresenta la collezione di [IChartCategory](../../com.aspose.slides/ichartcategory)
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [getUseCells()](#getUseCells--) | Se true, il foglio di lavoro è usato per memorizzare le categorie (questo caso supporta categorie a più livelli). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Se true, il foglio di lavoro è usato per memorizzare le categorie (questo caso supporta categorie a più livelli). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Restituisce il conteggio dei livelli di raggruppamento delle categorie usati. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Se la categoria esiste nella collezione, la restituisce. |
| [add(Object value)](#add-java.lang.Object-) | Crea un nuovo [IChartCategory](../../com.aspose.slides/ichartcategory) dal valore e lo aggiunge alla collezione. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Cerca il [IChartCategory](../../com.aspose.slides/ichartcategory) specificato e restituisce l'indice base-zero della prima occorrenza all'interno dell'intera Collection |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Rimuove il valore specificato. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice fornito. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla collezione. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
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
public abstract boolean getUseCells()
```

Se true, il foglio di lavoro è usato per memorizzare le categorie (questo caso supporta categorie a più livelli). Se false, il foglio di lavoro NON è usato per memorizzare i valori (e questo caso non supporta categorie a più livelli). Booleano leggibile/scrivibile.

**Restituisce:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

Se true, il foglio di lavoro è usato per memorizzare le categorie (questo caso supporta categorie a più livelli). Se false, il foglio di lavoro NON è usato per memorizzare i valori (e questo caso non supporta categorie a più livelli). Booleano leggibile/scrivibile.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

Restituisce il conteggio dei livelli di raggruppamento delle categorie usati. È maggiore di uno per categorie a più livelli. Intero di sola lettura.

**Restituisce:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

Se la categoria esiste nella collezione, la restituisce. Altrimenti crea una nuova categoria di grafico da [IChartDataCell](../../com.aspose.slides/ichartdatacell) e la aggiunge alla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell usata per creare la categoria di grafico. |

**Restituisce:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Categoria aggiunta o esistente.
### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

Crea un nuovo [IChartCategory](../../com.aspose.slides/ichartcategory) dal valore e lo aggiunge alla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.Object | Il valore. |

--------------------

Questo metodo aggiunge un foglio di lavoro con il nome AUTO_DATA e vi aggiunge tutti i valori. Se usi [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) per aggiungere o modificare i valori delle celle, assicurati di non usare questo foglio di lavoro. Il numero massimo di valori aggiunti usando questo metodo non deve superare 16711680 |

**Restituisce:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Aggiunto [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

Cerca il [IChartCategory](../../com.aspose.slides/ichartcategory) specificato e restituisce l'indice base-zero della prima occorrenza all'interno dell'intera Collection

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Categoria del grafico. |

**Restituisce:**
int - L'indice base-zero della prima occorrenza del valore all'interno dell'intera CollectionBase, se trovato; altrimenti, -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

Rimuove il valore specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Il valore. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Rimuove l'elemento all'indice fornito.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della categoria da rimuovere. |
### clear() {#clear--}
```
public abstract void clear()
```

Rimuove tutti gli elementi dalla collezione.