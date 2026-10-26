---
title: SequenceCollection
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta una collezione di sequenze interattive.
type: docs
url: /it/com.aspose.slides/sequencecollection/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

Rappresenta una collezione di sequenze interattive.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCount()](#getCount--) | Restituisce il numero di elementi in una collezione di sola lettura int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Aggiunge una nuova sequenza interattiva. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Rimuove la sequenza specificata da una collezione. |
| [removeAt(int index)](#removeAt-int-) | Rimuove la sequenza all'indice specificato. |
| [clear()](#clear--) | Rimuove tutte le sequenze da una collezione. |
| [get_Item(int index)](#get-Item-int-) | Restituisce una sequenza all'indice specificato. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iterator java per l'intera collezione. |
### getCount() {#getCount--}
```
public final int getCount()
```


Restituisce il numero di elementi in una collezione di sola lettura int.

**Restituisce:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```


Aggiunge una nuova sequenza interattiva. Lettura/scrittura [Sequence](../../com.aspose.slides/sequence).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**Restituisce:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```


Rimuove la sequenza specificata da una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Sequenza da rimuovere. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Rimuove la sequenza all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della sequenza da eliminare. |

### clear() {#clear--}
```
public final void clear()
```


Rimuove tutte le sequenze da una collezione.

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```


Restituisce una sequenza all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dell'elemento. |

**Restituisce:**
[ISequence](../../com.aspose.slides/isequence) - L'oggetto [ISequence](../../com.aspose.slides/isequence).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```


Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```


Restituisce un iterator java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Un java.util.Iterator per l'intera collezione.