---
title: RowCollection
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta la collezione di righe di tabella.
type: docs
url: /it/com.aspose.slides/rowcollection/
---
**Eredità:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

Rappresenta la collezione di righe di tabella.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [size()](#size--) | Ottiene il numero di righe effettivamente contenute nella collezione. |
| [get_Item(int index)](#get-Item-int-) | Restituisce la riga all'indice specificato. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Crea una copia della riga modello specificata e la inserisce nella parte inferiore di una tabella. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Crea una copia della riga modello specificata e la inserisce nella posizione specificata di una tabella. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Rimuove una riga alla posizione specificata da una tabella. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore Java per l'intera collezione. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi della collezione nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
### size() {#size--}
```
public final int size()
```


Ottiene il numero di righe effettivamente contenute nella collezione. Solo lettura int.

**Restituisce:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```


Restituisce la riga all'indice specificato. Solo lettura [Row](../../com.aspose.slides/row).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```


Crea una copia della riga modello specificata e la inserisce nella parte inferiore di una tabella.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Riga utilizzata come modello. |
| withAttachedRows | boolean | True per copiare anche tutte le righe collegate alla riga modello. |

**Restituisce:**
com.aspose.slides.IRow[] - Righe aggiunte.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


Crea una copia della riga modello specificata e la inserisce nella posizione specificata di una tabella.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di una nuova riga. |
| templ | [IRow](../../com.aspose.slides/irow) | Riga utilizzata come modello. |
| withAttachedRows | boolean | True per copiare anche tutte le righe collegate alla riga modello. |

**Restituisce:**
com.aspose.slides.IRow[] - Righe inserite.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```


Rimuove una riga alla posizione specificata da una tabella.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstRowIndex | int | Indice della riga da eliminare. |
| withAttachedRows | boolean | True per eliminare anche tutte le righe collegate. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```


Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```


Restituisce un iteratore Java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Un java.util.Iterator per l'intera collezione.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia tutti gli elementi della collezione nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione. |
| index | int | Indice di partenza nell'array di destinazione. |

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