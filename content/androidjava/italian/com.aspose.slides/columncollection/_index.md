---
title: ColumnCollection
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una raccolta di colonne in una tabella.
type: docs
url: /it/com.aspose.slides/columncollection/
---
**Ereditarietà:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

Rappresenta una raccolta di colonne in una tabella.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [size()](#size--) | Restituisce il numero di colonne in una raccolta. |
| [get_Item(int index)](#get-Item-int-) | Restituisce la colonna all'indice specificato. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Crea una copia della riga modello specificata e la inserisce nella parte inferiore di una tabella. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Crea una copia della colonna modello specificata e la inserisce nella posizione specificata in una tabella. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Rimuove una colonna nella posizione specificata da una tabella. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera sulla raccolta. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera raccolta. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi dalla raccolta nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
### size() {#size--}
```
public final int size()
```

Restituisce il numero di colonne in una raccolta. Sola lettura int.

**Restituisce:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```

Restituisce la colonna all'indice specificato. Sola lettura [Column](../../com.aspose.slides/column).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

Crea una copia della riga modello specificata e la inserisce nella parte inferiore di una tabella.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Colonna utilizzata come modello. |
| withAttachedColumns | boolean | True per copiare anche tutte le colonne collegate alla riga modello. |

**Restituisce:**
com.aspose.slides.IColumn[] - Colonne aggiunte.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

Crea una copia della colonna modello specificata e la inserisce nella posizione specificata in una tabella.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di una nuova colonna. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Colonna utilizzata come modello. |
| withAttachedColumns | boolean | True per copiare anche tutte le colonne collegate alla colonna modello. |

**Restituisce:**
com.aspose.slides.IColumn[] - Colonne inserite.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Rimuove una colonna nella posizione specificata da una tabella.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstColumnIndex | int | Indice della colonna da eliminare. |
| withAttachedRows | boolean | True per eliminare anche tutte le colonne collegate. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```

Restituisce un enumeratore che itera sulla raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - Un IGenericEnumerator che può essere utilizzato per iterare nella raccolta.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```

Restituisce un iteratore java per l'intera raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - Un java.util.Iterator per l'intera raccolta.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia tutti gli elementi dalla raccolta nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione. |
| index | int | Indice iniziale nell'array di destinazione. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). Sola lettura boolean.

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Restituisce una radice di sincronizzazione. Sola lettura Object.

**Restituisce:**
java.lang.Object