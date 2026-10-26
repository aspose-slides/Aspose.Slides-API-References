---
title: ColorOperationCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una raccolta di operazioni di trasformazione del colore.
type: docs
url: /it/com.aspose.slides/coloroperationcollection/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

Rappresenta una raccolta di operazioni di trasformazione del colore.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [size()](#size--) | Restituisce il numero di operazioni in una raccolta. |
| [get_Item(int index)](#get-Item-int-) | Restituisce o imposta l'operazione all'indice specificato. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Restituisce o imposta l'operazione all'indice specificato. |
| [add(int operation, float parameter)](#add-int-float-) | Aggiunge una nuova operazione alla fine della raccolta. |
| [add(int operation)](#add-int-) | Aggiunge una nuova operazione alla fine della raccolta. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Inserisce la nuova operazione in una raccolta. |
| [insert(int position, int operation)](#insert-int-int-) | Inserisce la nuova operazione in una raccolta. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'operazione di colore da una raccolta. |
| [clear()](#clear--) | Rimuove tutte le operazioni di colore. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la raccolta. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iterator java per l'intera raccolta. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi dalla raccolta nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
| [deepClone()](#deepClone--) | Crea una copia di una raccolta ColorOperationCollection. |
| [cloneT()](#cloneT--) | Clona l'oggetto corrente |
### size() {#size--}
```
public final int size()
```


Restituisce il numero di operazioni in una raccolta. Solo lettura int.

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


Aggiunge una nuova operazione alla fine della raccolta.

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


Aggiunge una nuova operazione alla fine della raccolta.

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


Inserisce la nuova operazione in una raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | int | L'indice presso il quale l'operazione verrà inserita. |
| operation | int | Tipo di operazione. |
| parameter | float | Parametro dell'operazione. |

**Restituisce:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operazione inserita.
### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```


Inserisce la nuova operazione in una raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | int | L'indice presso il quale l'operazione verrà inserita. |
| operation | int | Tipo di operazione. |

**Restituisce:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operazione inserita.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Rimuove l'operazione di colore da una raccolta.

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


Restituisce un enumeratore che itera attraverso la raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Un IGenericEnumerator che può essere usato per iterare attraverso la raccolta.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```


Restituisce un iterator java per l'intera raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Un java.util.Iterator per l'intera raccolta.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia tutti gli elementi dalla raccolta nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione. |
| index | int | Indice di partenza nell'array di destinazione. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). Solo lettura boolean.

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Restituisce una radice di sincronizzazione. Solo lettura Object.

**Restituisce:**
java.lang.Object
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Crea una copia di una raccolta ColorOperationCollection.

**Restituisce:**
java.lang.Object - Nuova [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) raccolta.
### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```


Clona l'oggetto corrente

**Restituisce:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - Clone