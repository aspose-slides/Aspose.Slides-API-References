---
title: ChartSeriesCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta la raccolta di
type: docs
url: /it/com.aspose.slides/chartseriescollection/
---
**Eredità:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

Rappresenta la raccolta di [ChartSeries](../../com.aspose.slides/chartseries)
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [size()](#size--) | Restituisce il numero di oggetti nella raccolta. |
| [add(int type)](#add-int-) | Crea una nuova serie di grafico e la aggiunge alla raccolta. |
| [insert(int index, int type)](#insert-int-int-) | Crea una nuova serie di grafico e la inserisce nella raccolta. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Crea una nuova serie di grafico da [ChartDataCell](../../com.aspose.slides/chartdatacell) e la aggiunge alla raccolta. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Crea una nuova serie di grafico da [ChartCellCollection](../../com.aspose.slides/chartcellcollection) e la aggiunge alla raccolta. |
| [add(String name, int type)](#add-java.lang.String-int-) | Crea una nuova serie di grafico dal valore e la aggiunge alla raccolta. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Cerca il [ChartSeries](../../com.aspose.slides/chartseries) specificato e restituisce l'indice basato su zero della prima occorrenza nell'intera Collection. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Rimuove il valore specificato. |
| [removeAt(int index)](#removeAt-int-) | Rimuove un controllo ActiveX memorizzato nella posizione specificata dalla raccolta. |
| [clear()](#clear--) | Rimuove tutti i controlli dalla raccolta. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la raccolta. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera raccolta. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia l'intera raccolta nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Ottiene l'elemento all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IChartSeries](../../com.aspose.slides/ichartseries) - L'elemento all'indice specificato.
### size() {#size--}
```
public final int size()
```

Restituisce il numero di oggetti nella raccolta. int di sola lettura.

**Restituisce:**
int
### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```

Crea una nuova serie di grafico e la aggiunge alla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Tipo di serie |

**Restituisce:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Nuova serie di grafico.
### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```

Crea una nuova serie di grafico e la inserisce nella raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**Restituisce:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Crea una nuova serie di grafico da [ChartDataCell](../../com.aspose.slides/chartdatacell) e la aggiunge alla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cella che contiene il nome della serie. |
| type | int | Tipo di serie impostato. |

--------------------

Se una serie di grafico creata dalla stessa cella è già nella raccolta, il metodo non aggiunge nulla e restituisce il suo indice.

**Restituisce:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Serie di grafico aggiunta o serie già presente nella raccolta.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Crea una nuova serie di grafico da [ChartCellCollection](../../com.aspose.slides/chartcellcollection) e la aggiunge alla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Celle che contengono il nome della serie. |
| type | int | Tipo di serie impostato. |

--------------------

Se una serie di grafico creata dalla stessa cella è già nella raccolta, il metodo non aggiunge nulla e restituisce il suo indice.

**Restituisce:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Serie di grafico aggiunta o serie già presente nella raccolta.
### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

Crea una nuova serie di grafico dal valore e la aggiunge alla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della serie. |
| type | int | Tipo di serie impostato. |

**Restituisce:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Serie di grafico aggiunta.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

Cerca il [ChartSeries](../../com.aspose.slides/chartseries) specificato e restituisce l'indice basato su zero della prima occorrenza all'interno dell'intera Collection.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Valore della serie di grafico. |

**Restituisce:**
int - L'indice basato su zero della prima occorrenza del valore nell'intera CollectionBase, se trovato; altrimenti, -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```

Rimuove il valore specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Il valore. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove un controllo ActiveX memorizzato nella posizione specificata dalla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice del controllo da rimuovere. |
### clear() {#clear--}
```
public final void clear()
```

Rimuove tutti i controlli dalla raccolta.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

Restituisce un enumeratore che itera attraverso la raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - Un IGenericEnumerator che può essere usato per iterare attraverso la raccolta.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

Restituisce un iteratore java per l'intera raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - Un java.util.Iterator per l'intera raccolta.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia l'intera raccolta nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione |
| index | int | Indice nell'array di destinazione. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). Boolean di sola lettura.

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Restituisce una radice di sincronizzazione. Oggetto di sola lettura.

**Restituisce:**
java.lang.Object