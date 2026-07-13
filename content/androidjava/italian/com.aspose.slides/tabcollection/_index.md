---
title: TabCollection
second_title: Aspose.Slides per Android tramite Java API Reference
description: Rappresenta una collezione di tab.
type: docs
url: /it/com.aspose.slides/tabcollection/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

Rappresenta una collezione di tab.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [size()](#size--) | Restituisce il numero di elementi effettivamente contenuti nella collezione. |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento all'indice specificato. |
| [add(double position, int align)](#add-double-int-) | Aggiunge un Tab alla collezione. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Aggiunge un Tab alla collezione. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla collezione. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato della collezione. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se due istanze di TabsEx sono uguali. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera collezione. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi dalla collezione nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
### size() {#size--}
```
public final int size()
```

Restituisce il numero di elementi effettivamente contenuti nella collezione. Solo lettura int.

**Restituisce:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```

Restituisce l'elemento all'indice specificato. Solo lettura [Tab](../../com.aspose.slides/tab).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```

Aggiunge un Tab alla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**Restituisce:**
[ITab](../../com.aspose.slides/itab) - Tab aggiunto.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```

Aggiunge un Tab alla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | L'oggetto Tab da aggiungere alla fine della collezione. |

**Restituisce:**
int - L'indice in cui il tab è stato aggiunto.
### clear() {#clear--}
```
public final void clear()
```

Rimuove tutti gli elementi dalla collezione.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove l'elemento all'indice specificato della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da rimuovere. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina se due istanze di TabsEx sono uguali.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Il TabsEx da confrontare con l'attuale TabsEx. |

**Restituisce:**
boolean - **true** se il TabsEx specificato è uguale all'attuale TabsEx; altrimenti, **false**.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```

Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```

Restituisce un iteratore java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - Un java.util.Iterator per l'intera collezione.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia tutti gli elementi dalla collezione nell'array specificato.

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