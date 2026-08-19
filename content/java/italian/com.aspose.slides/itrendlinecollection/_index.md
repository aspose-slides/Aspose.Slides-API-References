---
title: ITrendlineCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una raccolta di TrendlineEx
type: docs
url: /it/com.aspose.slides/itrendlinecollection/
---
**Tutte le interfacce implementate:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

Rappresenta una raccolta di TrendlineEx
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [getCount()](#getCount--) | Ottiene il numero di elementi effettivamente contenuti nella raccolta. |
| [add(int trendlineType)](#add-int-) | Aggiunge il nuovo Trendline alla fine di una raccolta e lo restituisce. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Rimuove il valore specificato. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```


Ottiene l'elemento all'indice specificato. Solo lettura [ITrendline](../../com.aspose.slides/itrendline).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Ottiene il numero di elementi effettivamente contenuti nella raccolta. Solo lettura int.

**Restituisce:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```


Aggiunge il nuovo Trendline alla fine di una raccolta e lo restituisce.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| trendlineType | int | Tipo di Trendline [TrendlineType](../../com.aspose.slides/trendlinetype) |

**Restituisce:**
[ITrendline](../../com.aspose.slides/itrendline) - Nuovo Trendline [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```


Rimuove il valore specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | Trendline da rimuovere [ITrendline](../../com.aspose.slides/itrendline) |