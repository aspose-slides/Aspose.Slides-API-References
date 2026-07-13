---
title: ChartSeriesCollection
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una collezione di
type: docs
url: /it/com.aspose.slides/chartseriescollection/
---
**Ereditarietà:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

Rappresenta una collezione di [ChartSeries](../../com.aspose.slides/chartseries)
## Metodi

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [size()](#size--) | Restituisce un numero di oggetti nella collezione. |
| [add(int type)](#add-int-) | Crea una nuova serie di diagramma e la aggiunge alla collezione. |
| [insert(int index, int type)](#insert-int-int-) | Crea una nuova serie di diagramma e la inserisce nella collezione. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Crea una nuova serie di diagramma da [ChartDataCell](../../com.aspose.slides/chartdatacell) e la aggiunge alla collezione. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Crea una nuova serie di diagramma da [ChartCellCollection](../../com.aspose.slides/chartcellcollection) e la aggiunge alla collezione. |
| [add(String name, int type)](#add-java.lang.String-int-) | Crea una nuova serie di diagramma da valore e la aggiunge alla collezione. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Cerca il [ChartSeries](../../com.aspose.slides/chartseries) specificato e restituisce l'indice basato su zero della prima occorrenza all'interno dell'intera Collection |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Rimuove il valore specificato. |
| [removeAt(int index)](#removeAt-int-) | Rimuove un controllo ActiveX memorizzato nella posizione specificata dalla collezione. |
| [clear()](#clear--) | Rimuove tutti i controlli dalla collezione. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera collezione. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia l'intera collezione nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Ottiene l'elemento all'indice specificato.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IChartSeries](../../com.aspose.slides/ichartseries) - L'elemento all'indice specificato.
### size() {#size--}
```
public final int size()
```

Restituisce un numero di oggetti nella collezione. int a sola lettura.

**Restituisce:**
int
### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```

Crea una nuova serie di diagramma e la aggiunge alla collezione.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Tipo della serie |

**Restituisce:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Nuova serie di diagramma.
### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```

Crea una nuova serie di diagramma e la inserisce nella collezione.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**Restituisce:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Crea una nuova serie di diagramma da [ChartDataCell](../../com.aspose.slides/chartdatacell) e la aggiunge alla collezione.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cella che contiene il nome della serie. |
| type | int | Tipo della serie |

--------------------

Se la serie di diagramma creata dalla stessa cella è già presente nella collezione, il metodo non aggiunge nulla e restituisce il suo indice. |

**Restituisce:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Serie di diagramma aggiunta o serie già presente nella collezione.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Crea una nuova serie di diagramma da [ChartCellCollection](../../com.aspose.slides/chartcellcollection) e la aggiunge alla collezione.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Celle che contengono il nome della serie. |
| type | int | Tipo della serie |

--------------------

Se la serie di diagramma creata dalla stessa cella è già presente nella collezione, il metodo non aggiunge nulla e restituisce il suo indice. |

**Restituisce:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Serie di diagramma aggiunta o serie già presente nella collezione.
### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

Crea una nuova serie di diagramma da valore e la aggiunge alla collezione.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nome della serie. |
| type | int | Tipo della serie |

**Restituisce:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Serie di diagramma aggiunta.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

Cerca il [ChartSeries](../../com.aspose.slides/chartseries) specificato e restituisce l'indice basato su zero della prima occorrenza all'interno dell'intera Collection

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Valore della serie di diagramma. |

**Restituisce:**
int - L'indice basato su zero della prima occorrenza del valore all'interno dell'intera CollectionBase, se trovato; altrimenti, -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```

Rimuove il valore specificato.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Il valore. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove un controllo ActiveX memorizzato nella posizione specificata dalla collezione.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indice del controllo da rimuovere. |

### clear() {#clear--}
```
public final void clear()
```

Rimuove tutti i controlli dalla collezione.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

Restituisce un iteratore java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - Un java.util.Iterator per l'intera collezione.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia l'intera collezione nell'array specificato.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione |
| index | int | Indice nell'array di destinazione. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). boolean a sola lettura.

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Restituisce una radice di sincronizzazione. Object a sola lettura.

**Restituisce:**
java.lang.Object