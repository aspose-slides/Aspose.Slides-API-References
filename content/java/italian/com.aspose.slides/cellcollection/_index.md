---
title: CellCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una raccolta di celle.
type: docs
url: /it/com.aspose.slides/cellcollection/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), com.aspose.slides.IDOMObject
```
public abstract class CellCollection implements ICellCollection, IDOMObject
```

Rappresenta una collezione di celle.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [size()](#size--) | Restituisce il numero di celle in una collezione. |
| [get_Item(int index)](#get-Item-int-) | Restituisce una cella per la sua posizione. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera collezione. |
| [getSlide()](#getSlide--) | Restituisce la slide padre di una CellCollection. |
| [getPresentation()](#getPresentation--) | Restituisce la presentazione padre di una CellCollection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi dalla collezione nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject
### size() {#size--}
```
public final int size()
```

Restituisce il numero di celle in una collezione. Solo lettura int.

**Restituisce:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICell get_Item(int index)
```

Restituisce una cella per la sua posizione. Solo lettura [Cell](../../com.aspose.slides/cell).

Un oggetto Cell può essere restituito per più indici nel caso in cui la cella sia unita.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[ICell](../../com.aspose.slides/icell)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iterator()
```

Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iteratorJava()
```

Restituisce un iteratore java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - Un java.util.Iterator per l'intera collezione.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Restituisce la slide padre di una CellCollection. Solo lettura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Restituisce:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Restituisce la presentazione padre di una CellCollection. Solo lettura [IPresentation](../../com.aspose.slides/ipresentation).

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation)
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia tutti gli elementi dalla collezione nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione. |
| index | int | Indice iniziale nell'array di destinazione. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). Solo lettura boolean.

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Restituisce una radice di sincronizzazione. Solo lettura Object.

**Restituisce:**
java.lang.Object