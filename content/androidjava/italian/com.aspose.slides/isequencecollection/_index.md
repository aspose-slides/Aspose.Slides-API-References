---
title: ISequenceCollection
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una collezione di sequenze interattive.
type: docs
url: /it/com.aspose.slides/isequencecollection/
---
**Tutte le interfacce implementate:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

Rappresenta una collezione di sequenze interattive.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCount()](#getCount--) | Restituisce il numero di elementi in una collezione int in sola lettura. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Aggiunge nuova sequenza interattiva. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Rimuove la sequenza specificata da una collezione. |
| [removeAt(int index)](#removeAt-int-) | Rimuove la sequenza all'indice specificato. |
| [clear()](#clear--) | Rimuove tutte le sequenze da una collezione. |
| [get_Item(int index)](#get-Item-int-) | Restituisce una sequenza all'indice specificato. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Restituisce il numero di elementi in una collezione int in sola lettura.

**Restituisce:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```

Aggiunge nuova sequenza interattiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | oggetto Shape [IShape](../../com.aspose.slides/ishape) |

**Restituisce:**
[ISequence](../../com.aspose.slides/isequence) - Nuova sequenza [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```

Rimuove la sequenza specificata da una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Sequenza da rimuovere. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Rimuove la sequenza all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dell'elemento nella collezione int |

### clear() {#clear--}
```
public abstract void clear()
```

Rimuove tutte le sequenze da una collezione.

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```

Restituisce una sequenza all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dell'elemento. |

**Restituisce:**
[ISequence](../../com.aspose.slides/isequence) - L'[ISequence](../../com.aspose.slides/isequence) oggetto.