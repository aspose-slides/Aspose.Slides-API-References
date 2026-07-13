---
title: IChartSeriesCollection
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta la collezione di
type: docs
url: /it/com.aspose.slides/ichartseriescollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

Rappresenta la collezione di [IChartSeries](../../com.aspose.slides/ichartseries)
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [add(int type)](#add-int-) | Crea una nuova serie di grafico e la aggiunge alla collezione. |
| [insert(int index, int type)](#insert-int-int-) | Crea una nuova serie di grafico e la inserisce nella collezione. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Crea una nuova serie di grafico da [IChartDataCell](../../com.aspose.slides/ichartdatacell) e la aggiunge alla collezione. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Crea una nuova serie di grafico da [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) e la aggiunge alla collezione. |
| [add(String name, int type)](#add-java.lang.String-int-) | Crea una nuova serie di grafico dal valore e la aggiunge alla collezione. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Cerca il [IChartSeries](../../com.aspose.slides/ichartseries) specificato e restituisce l'indice basato su zero della prima occorrenza all'interno dell'intera Collection |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Rimuove il valore specificato. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato |
| [clear()](#clear--) | Rimuove tutti gli elementi (incluso lo stile del grafico) dalla collezione. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```


Ottiene l'elemento all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IChartSeries](../../com.aspose.slides/ichartseries) - L'elemento all'indice specificato.
### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```


Crea una nuova serie di grafico e la aggiunge alla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Tipo di serie |

**Restituisce:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Nuova serie di grafico.
### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```


Crea una nuova serie di grafico e la inserisce nella collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice per l'inserimento |
| type | int | Tipo di grafico [ChartType](../../com.aspose.slides/charttype) |

**Restituisce:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Nuova serie di grafico [IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```


Crea una nuova serie di grafico da [IChartDataCell](../../com.aspose.slides/ichartdatacell) e la aggiunge alla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cella che contiene il nome della serie. |
| type | int | Tipo impostato della serie

--------------------

Se una serie di grafico creata dalla stessa cella è già nella collezione, il metodo non aggiunge nulla e restituisce il suo indice. |

**Restituisce:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Serie di grafico aggiunta o serie già presente nella collezione.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```


Crea una nuova serie di grafico da [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) e la aggiunge alla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Celle che contengono il nome della serie. |
| type | int | Tipo impostato della serie

--------------------

Se una serie di grafico creata dalla stessa cella è già nella collezione, il metodo non aggiunge nulla e restituisce il suo indice. |

**Restituisce:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Serie di grafico aggiunta o serie già presente nella collezione.
### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```


Crea una nuova serie di grafico dal valore e la aggiunge alla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della serie. |
| type | int | Tipo impostato della serie |

**Restituisce:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Serie di grafico aggiunta.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```


Cerca il [IChartSeries](../../com.aspose.slides/ichartseries) specificato e restituisce l'indice basato su zero della prima occorrenza all'interno dell'intera Collection

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Valore della serie di grafico. |

**Restituisce:**
int - L'indice basato su zero della prima occorrenza del valore all'interno dell'intera CollectionBase, se trovato; altrimenti, -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```


Rimuove il valore specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Il valore. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Rimuove l'elemento all'indice specificato

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice |
### clear() {#clear--}
```
public abstract void clear()
```


Rimuove tutti gli elementi (incluso lo stile del grafico) dalla collezione.