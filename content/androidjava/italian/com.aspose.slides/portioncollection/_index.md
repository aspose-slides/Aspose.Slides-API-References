---
title: PortionCollection
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta una raccolta di porzioni.
type: docs
url: /it/com.aspose.slides/portioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

Rappresenta una raccolta di porzioni.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCount()](#getCount--) | Restituisce il numero di elementi effettivamente contenuti nella raccolta. |
| [isReadOnly()](#isReadOnly--) | Restituisce un valore che indica se il [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura. |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento all'indice specificato. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | Restituisce l'elemento all'indice specificato. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Aggiunge un Portion alla fine della raccolta. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Determina l'indice di un elemento specifico nella List. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Inserisce un Portion nella raccolta all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla raccolta. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Determina se il [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | Copia gli elementi del [IGenericCollection](../../com.aspose.slides/igenericcollection) in un Array, a partire da un indice specifico dell'Array. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Rimuove la prima occorrenza di un oggetto specifico dal [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato della raccolta. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera sulla raccolta. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera raccolta. |
### getCount() {#getCount--}
```
public final int getCount()
```

Restituisce il numero di elementi effettivamente contenuti nella raccolta. Solo lettura int.

**Restituisce:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Restituisce un valore che indica se il [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura. Solo lettura boolean.

**Restituisce:**
boolean - true se il [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura; altrimenti, false.
### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```

Restituisce l'elemento all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IPortion](../../com.aspose.slides/iportion)
### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```

Restituisce l'elemento all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```

Aggiunge un Portion alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Il Portion da aggiungere alla fine della raccolta. |
### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```

Determina l'indice di un elemento specifico nella List.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | L'oggetto da trovare nella List. |

**Restituisce:**
int - L'indice dell'elemento se trovato nella lista; altrimenti, -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```

Inserisce un Portion nella raccolta all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero al quale il Portion deve essere inserito. |
| value | [IPortion](../../com.aspose.slides/iportion) | Il Portion da inserire. |
### clear() {#clear--}
```
public final void clear()
```

Rimuove tutti gli elementi dalla raccolta.
### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```

Determina se il [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | L'oggetto da trovare nel [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Restituisce:**
boolean - true se l'elemento è trovato nel [IGenericCollection](../../com.aspose.slides/igenericcollection); altrimenti, false.
### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```

Copia gli elementi del [IGenericCollection](../../com.aspose.slides/igenericcollection) in un Array, a partire da uno specifico indice dell'Array.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | L'Array monodimensionale che è la destinazione degli elementi copiati da [IGenericCollection](../../com.aspose.slides/igenericcollection). L'Array deve avere indicizzazione basata su zero. |
| arrayIndex | int | L'indice basato su zero nell'array da cui inizia la copia. |
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```

Rimuove la prima occorrenza di un oggetto specifico dal [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | L'oggetto da rimuovere dal [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Restituisce:**
boolean - true se l'elemento è stato rimosso con successo dal [IGenericCollection](../../com.aspose.slides/igenericcollection); altrimenti, false. Questo metodo restituisce anche false se l'elemento non è trovato nell'originale [IGenericCollection](../../com.aspose.slides/igenericcollection).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove l'elemento all'indice specificato della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da rimuovere. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```

Restituisce un enumeratore che itera sulla raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - Un IGenericEnumerator che può essere usato per iterare sulla raccolta.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```

Restituisce un iteratore java per l'intera raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - Un java.util.Iterator per l'intera raccolta.