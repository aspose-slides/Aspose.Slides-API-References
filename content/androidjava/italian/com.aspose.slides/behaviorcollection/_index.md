---
title: BehaviorCollection
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta una collezione di effetti di comportamento.
type: docs
url: /it/com.aspose.slides/behaviorcollection/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

Rappresenta una collezione di effetti di comportamento.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCount()](#getCount--) | Restituisce il numero di comportamenti in una collezione. |
| [isReadOnly()](#isReadOnly--) | Ottiene un valore che indica se il [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Aggiunge un nuovo comportamento a una collezione. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Determina l'indice di un elemento specifico nella Lista. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Inserisce un nuovo comportamento in una collezione all'indice specificato. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | Copia gli elementi di [IGenericCollection](../../com.aspose.slides/igenericcollection) in un Array, a partire da un indice specifico dell'Array. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Rimuove il comportamento specificato da una collezione. |
| [removeAt(int index)](#removeAt-int-) | Rimuove un comportamento da una collezione all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti i comportamenti da una collezione. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Determina se [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico. |
| [get_Item(int index)](#get-Item-int-) | Restituisce un comportamento all'indice specificato. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Imposta un comportamento all'indice specificato. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera collezione. |
### getCount() {#getCount--}
```
public final int getCount()
```

Restituisce il numero di comportamenti in una collezione. int di sola lettura.

**Restituisce:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Ottiene un valore che indica se [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura. boolean di sola lettura.

**Restituisce:**
boolean - true se [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura; altrimenti, false.
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```

Aggiunge un nuovo comportamento a una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportamento da aggiungere. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```

Determina l'indice di un elemento specifico nella Lista.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | L'oggetto da individuare nella Lista. |

**Restituisce:**
int - L'indice dell'elemento se trovato nella lista; altrimenti, -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```

Inserisce un nuovo comportamento in una collezione all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dove inserire il nuovo comportamento. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportamento da inserire. |

### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```

Copia gli elementi di [IGenericCollection](../../com.aspose.slides/igenericcollection) in un Array, a partire da un indice specifico dell'Array.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | L'Array monodimensionale che è la destinazione degli elementi copiati da [IGenericCollection](../../com.aspose.slides/igenericcollection). L'Array deve avere indicizzazione basata su zero. |
| arrayIndex | int | L'indice basato su zero nell'array a partire dal quale inizia la copia. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```

Rimuove il comportamento specificato da una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportamento da rimuovere. |

**Restituisce:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove un comportamento da una collezione all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di un comportamento da rimuovere. |

### clear() {#clear--}
```
public final void clear()
```

Rimuove tutti i comportamenti da una collezione.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```

Determina se [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | L'oggetto da individuare in [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Restituisce:**
boolean - true se l'elemento è trovato in [IGenericCollection](../../com.aspose.slides/igenericcollection); altrimenti, false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```

Restituisce un comportamento all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di un comportamento da restituire. |

**Restituisce:**
[IBehavior](../../com.aspose.slides/ibehavior) - Comportamento di animazione.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```

Imposta un comportamento all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di un comportamento da restituire. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```

Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```

Restituisce un iteratore java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - Un java.util.Iterator per l'intera collezione.