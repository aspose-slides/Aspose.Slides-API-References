---
title: ColorOperationCollection
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una collezione di operazioni di trasformazione del colore.
type: docs
url: /it/com.aspose.slides/coloroperationcollection/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

Rappresenta una collezione di operazioni di trasformazione del colore.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [size()](#size--) | Restituisce il numero di operazioni in una collezione. |
| [get_Item(int index)](#get-Item-int-) | Restituisce o imposta l'operazione all'indice specificato. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Restituisce o imposta l'operazione all'indice specificato. |
| [add(int operation, float parameter)](#add-int-float-) | Aggiunge una nuova operazione alla fine della collezione. |
| [add(int operation)](#add-int-) | Aggiunge una nuova operazione alla fine della collezione. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Inserisce la nuova operazione in una collezione. |
| [insert(int position, int operation)](#insert-int-int-) | Inserisce la nuova operazione in una collezione. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'operazione di colore da una collezione. |
| [clear()](#clear--) | Rimuove tutte le operazioni di colore. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera collezione. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi dalla collezione nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
| [deepClone()](#deepClone--) | Crea una copia di una collezione ColorOperationCollection. |
| [cloneT()](#cloneT--) | Clona l'oggetto corrente |
### size() {#size--}
```
public final int size()
```

Restituisce il numero di operazioni in una collezione. Sola lettura int.

**Restituisce:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

Restituisce o imposta l'operazione all'indice specificato. Lettura/scrittura [ColorOperation](../../com.aspose.slides/coloroperation).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

Restituisce o imposta l'operazione all'indice specificato. Lettura/scrittura [ColorOperation](../../com.aspose.slides/coloroperation).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |
### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

Aggiunge una nuova operazione alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| operation | int | Tipo di operazione. |
| parameter | float | Parametro dell'operazione. |

**Restituisce:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operazione aggiunta.
### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

Aggiunge una nuova operazione alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| operation | int | Tipo di operazione. |

**Restituisce:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operazione aggiunta.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

Inserisce la nuova operazione in una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | int | L'indice al quale l'operazione verrà inserita. |
| operation | int | Tipo di operazione. |
| parameter | float | Parametro dell'operazione. |

**Restituisce:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operazione inserita.
### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

Inserisce la nuova operazione in una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | int | L'indice al quale l'operazione verrà inserita. |
| operation | int | Tipo di operazione. |

**Restituisce:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operazione inserita.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove l'operazione di colore da una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di un'operazione di colore da rimuovere. |
### clear() {#clear--}
```
public final void clear()
```

Rimuove tutte le operazioni di colore.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

Restituisce un iteratore java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Un java.util.Iterator per l'intera collezione.
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

Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). Sola lettura boolean.

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Restituisce una radice di sincronizzazione. Sola lettura Object.

**Restituisce:**
java.lang.Object
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Crea una copia di una collezione ColorOperationCollection.

**Restituisce:**
java.lang.Object - Nuova collezione [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection).
### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

Clona l'oggetto corrente

**Restituisce:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - Clona