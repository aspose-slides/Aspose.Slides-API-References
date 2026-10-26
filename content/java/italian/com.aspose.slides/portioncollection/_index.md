---
title: PortionCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una collezione di porzioni.
type: docs
url: /it/com.aspose.slides/portioncollection/
---
**Ereditarietà:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

Rappresenta una collezione di porzioni.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCount()](#getCount--) | Restituisce il numero di elementi effettivamente contenuti nella collezione. |
| [isReadOnly()](#isReadOnly--) | Restituisce un valore che indica se [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura. |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento all'indice specificato. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | Restituisce l'elemento all'indice specificato. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Aggiunge una Portion alla fine della collezione. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Determina l'indice di un elemento specifico nella List. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Inserisce una Portion nella collezione all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla collezione. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Determina se [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | Copia gli elementi di [IGenericCollection](../../com.aspose.slides/igenericcollection) in un Array, iniziando da un indice specifico dell'Array. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Rimuove la prima occorrenza di un oggetto specifico da [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato della collezione. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iterator Java per l'intera collezione. |
### getCount() {#getCount--}
```
public final int getCount()
```

Restituisce il numero di elementi effettivamente contenuti nella collezione. Intero di sola lettura.

**Restituisce:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Restituisce un valore che indica se [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura. Boolean di sola lettura.

**Restituisce:**
boolean - true se [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura; altrimenti, false.
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

Aggiunge una Portion alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | La Portion da aggiungere alla fine della collezione. |
### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```

Determina l'indice di un elemento specifico nella List.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | L'oggetto da individuare nella List. |

**Restituisce:**
int - L'indice dell'item se trovato nella lista; altrimenti, -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```

Inserisce una Portion nella collezione all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero al quale la Portion deve essere inserita. |
| value | [IPortion](../../com.aspose.slides/iportion) | La Portion da inserire. |
### clear() {#clear--}
```
public final void clear()
```

Rimuove tutti gli elementi dalla collezione.
### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```

Determina se [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | L'oggetto da individuare in [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Restituisce:**
boolean - true se l'item è trovato in [IGenericCollection](../../com.aspose.slides/igenericcollection); altrimenti, false.
### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```

Copia gli elementi di [IGenericCollection](../../com.aspose.slides/igenericcollection) in un Array, iniziando da un indice specifico dell'Array.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | L'Array monodimensionale che è la destinazione degli elementi copiati da [IGenericCollection](../../com.aspose.slides/igenericcollection). L'Array deve avere un indice basato su zero. |
| arrayIndex | int | L'indice basato su zero nell'array a partire dal quale inizia la copia. |
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```

Rimuove la prima occorrenza di un oggetto specifico da [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | L'oggetto da rimuovere da [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Restituisce:**
boolean - true se l'item è stato rimosso con successo da [IGenericCollection](../../com.aspose.slides/igenericcollection); altrimenti, false. Questo metodo restituisce anche false se l'item non è trovato nella [IGenericCollection](../../com.aspose.slides/igenericcollection) originale.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove l'elemento all'indice specificato della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da rimuovere. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```

Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```

Restituisce un iterator Java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - Un java.util.Iterator per l'intera collezione.