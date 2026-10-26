---
title: IPieSplitCustomPointCollection
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una raccolta di punti che devono essere disegnati nella seconda fetta o barra di un grafico a barra-in-fetta o fetta-in-fetta con una divisione personalizzata.
type: docs
url: /it/com.aspose.slides/ipiesplitcustompointcollection/
---
**Tutte le interfacce implementate:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

Rappresenta una raccolta di punti che devono essere disegnati nella seconda fetta o barra su un grafico a barra-in-fetta o fetta-in-fetta con una divisione personalizzata.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce il punto dati del grafico per indice. |
| [add(int dataPointIndex)](#add-int-) | Aggiunge il punto dati in base al suo indice nella collezione di punti della serie padre. |
| [remove(int dataPointIndex)](#remove-int-) | Rimuove l'elemento dalla collezione in base al suo indice nella collezione di punti della serie padre. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Restituisce il punto dati del grafico per indice.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice del punto dati. |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Punto dati del grafico.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```

Aggiunge il punto dati in base al suo indice nella collezione di punti della serie padre.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataPointIndex | int | Indice del punto dati nella collezione di punti della serie padre. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```

Rimuove l'elemento dalla collezione in base al suo indice nella collezione di punti della serie padre.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataPointIndex | int | Indice del punto dati nella collezione di punti della serie padre.. |