---
title: BehaviorCollection
second_title: Riferimento API Aspose.Slides per Java
description: Rappresenta una raccolta di effetti di comportamento.
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

Rappresenta una raccolta di effetti di comportamento.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCount()](#getCount--) | Restituisce il numero di comportamenti in una raccolta. |
| [isReadOnly()](#isReadOnly--) | Ottiene un valore che indica se il [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Aggiunge un nuovo comportamento a una raccolta. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Determina l'indice di un elemento specifico nella List. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Inserisce un nuovo comportamento in una raccolta all'indice specificato. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | Copia gli elementi del [IGenericCollection](../../com.aspose.slides/igenericcollection) in un Array, a partire da un indice specifico dell'Array. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Rimuove il comportamento specificato da una raccolta. |
| [removeAt(int index)](#removeAt-int-) | Rimuove un comportamento da una raccolta all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti i comportamenti da una raccolta. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Determina se il [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico. |
| [get_Item(int index)](#get-Item-int-) | Restituisce un comportamento all'indice specificato. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Imposta un comportamento all'indice specificato. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la raccolta. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iterator java per l'intera raccolta. |
### getCount() {#getCount--}
```
public final int getCount()
```


Restituisce il numero di comportamenti in una raccolta. int di sola lettura.

**Restituisce:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Ottiene un valore che indica se il [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura. boolean di sola lettura.

**Restituisce:**
boolean - true se il [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura; altrimenti, false.
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```


Aggiunge un nuovo comportamento a una raccolta.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportamento da aggiungere. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```


Determina l'indice di un elemento specifico nella List.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | L'oggetto da individuare nella List. |

**Restituisce:**
int - L'indice dell'item se trovato nella lista; altrimenti, -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```


Inserisce un nuovo comportamento in una raccolta all'indice specificato.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indice dove inserire il nuovo comportamento. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportamento da inserire. |

### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```


Copia gli elementi del [IGenericCollection](../../com.aspose.slides/igenericcollection) in un Array, a partire da un indice specifico dell'Array.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | L'Array monodimensionale che è la destinazione degli elementi copiati da [IGenericCollection](../../com.aspose.slides/igenericcollection). L'Array deve avere indicizzazione basata su zero. |
| arrayIndex | int | L'indice basato su zero nell'array a partire dal quale inizia la copia. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```


Rimuove il comportamento specificato da una raccolta.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportamento da rimuovere. |

**Restituisce:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Rimuove un comportamento da una raccolta all'indice specificato.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indice di un comportamento da rimuovere. |

### clear() {#clear--}
```
public final void clear()
```


Rimuove tutti i comportamenti da una raccolta.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```


Determina se il [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | L'oggetto da individuare nel [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Restituisce:**
boolean - true se l'item è trovato nel [IGenericCollection](../../com.aspose.slides/igenericcollection); altrimenti, false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```


Restituisce un comportamento all'indice specificato.

**Parametri:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indice di un comportamento da impostare. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```


Restituisce un enumeratore che itera attraverso la raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - Un IGenericEnumerator che può essere usato per iterare attraverso la raccolta.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```


Restituisce un iterator java per l'intera raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - Un java.util.Iterator per l'intera raccolta.