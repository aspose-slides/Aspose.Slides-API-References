---
title: PieSplitCustomPointCollection
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una collezione di punti per il punto di divisione in un grafico a torta con barra o a torta annidata con una divisione personalizzata.
type: docs
url: /it/com.aspose.slides/piesplitcustompointcollection/
---
**Ereditarietà:**
java.lang.Object

**Tutte le Interfacce Implementate:**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

Rappresenta una collezione di punti per il punto di divisione in un grafico a torta con barra o a torta annidata con una divisione personalizzata.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce il punto dati del grafico per l'indice specificato. |
| [add(int dataPointIndex)](#add-int-) | Aggiunge il punto dati nel suo indice nella raccolta dei punti della serie padre. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | Aggiunge il punto dati alla collezione. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | Rimuove l'elemento dalla collezione. |
| [remove(int dataPointIndex)](#remove-int-) | Rimuove l'elemento dalla collezione tramite il suo indice nella raccolta dei punti della serie padre. |
| [clear()](#clear--) | Rimuove tutti gli elementi dal [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | Determina se il [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | Copia gli elementi del [IGenericCollection](../../com.aspose.slides/igenericcollection) in un Array, a partire da un indice specifico dell'Array. |
| [size()](#size--) | Restituisce o imposta il conteggio dei punti dati del grafico. |
| [isReadOnly()](#isReadOnly--) | Ottiene un valore che indica se il [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore Java per l'intera collezione. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Restituisce il punto dati del grafico per l'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice. |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Punto dati del grafico.

### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

Aggiunge il punto dati nel suo indice nella raccolta dei punti della serie padre.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataPointIndex | int | Indice del punto dati nella raccolta dei punti della serie padre. |

### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

Aggiunge il punto dati alla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Punto dati da aggiungere. |

### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

Rimuove l'elemento dalla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Punto dati da rimuovere. |

**Restituisce:**
boolean - true se l'elemento è stato rimosso con successo; altrimenti, false. Questo metodo restituisce anche false se l'elemento non è stato trovato nella System.Collections.Generic.List\{T\}.

### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

Rimuove l'elemento dalla collezione tramite il suo indice nella raccolta dei punti della serie padre.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataPointIndex | int | Indice del punto dati nella raccolta dei punti della serie padre. |

### clear() {#clear--}
```
public final void clear()
```

Rimuove tutti gli elementi dal [IGenericCollection](../../com.aspose.slides/igenericcollection).

### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

Determina se il [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | L'oggetto da individuare nel [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Restituisce:**
boolean - true se l'elemento è trovato nel [IGenericCollection](../../com.aspose.slides/igenericcollection); altrimenti, false.

### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

Copia gli elementi del [IGenericCollection](../../com.aspose.slides/igenericcollection) in un Array, a partire da un indice specifico dell'Array.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | L'Array monodimensionale che è la destinazione degli elementi copiati da [IGenericCollection](../../com.aspose.slides/igenericcollection). L'Array deve avere indicizzazione a base zero. |
| arrayIndex | int | L'indice a base zero nell'array a partire dal quale inizia la copia. |

### size() {#size--}
```
public final int size()
```

Restituisce o imposta il conteggio dei punti dati del grafico. int di sola lettura.

**Restituisce:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Ottiene un valore che indica se il [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura. boolean di sola lettura.

**Restituisce:**
boolean - true se il [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura; altrimenti, false.

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). boolean di sola lettura.

**Restituisce:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Restituisce una radice di sincronizzazione. Object di sola lettura.

**Restituisce:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Restituisce un enumeratore che itera attraversa la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Restituisce un iteratore Java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Un java.util.Iterator per l'intera collezione.