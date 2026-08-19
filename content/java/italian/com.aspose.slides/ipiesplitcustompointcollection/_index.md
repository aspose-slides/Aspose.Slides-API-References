---
title: IPieSplitCustomPointCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una raccolta di punti che devono essere disegnati nel secondo settore o barra di un grafico a barra-di-pie o pie-di-pie con una divisione personalizzata.
type: docs
url: /it/com.aspose.slides/ipiesplitcustompointcollection/
---
**Tutte le interfacce implementate:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

Rappresenta una raccolta di punti che devono essere disegni nel secondo settore o barra di un grafico a bar-di-pie o pie-di-pie con una divisione personalizzata.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce il punto dati del grafico per indice. |
| [add(int dataPointIndex)](#add-int-) | Aggiunge un punto dati per il suo indice nella raccolta dei punti della serie genitore. |
| [remove(int dataPointIndex)](#remove-int-) | Rimuove l'elemento dalla raccolta per il suo indice nella raccolta dei punti della serie genitore. |
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

Aggiunge un punto dati per il suo indice nella raccolta dei punti della serie genitore.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataPointIndex | int | Indice del punto dati nella raccolta dei punti della serie genitore. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```

Rimuove l'elemento dalla raccolta per il suo indice nella raccolta dei punti della serie genitore.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataPointIndex | int | Indice del punto dati nella raccolta dei punti della serie genitore.. |