---
title: TagCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta la collezione di tag, coppie di stringhe definite dall'utente
type: docs
url: /it/com.aspose.slides/tagcollection/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

Rappresenta la collezione di tag (coppie di stringhe definite dall'utente)

--------------------

> ```
> The following example shows how to add a tag to a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ITagCollection tags = pres.getCustomData().getTags();
>      pres.getCustomData().getTags().add("MyTag", "My Tag Value");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [size()](#size--) | Restituisce il numero di tag nella collezione. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Aggiunge un nuovo tag alla collezione. |
| [remove(String name)](#remove-java.lang.String-) | Rimuove il tag con un nome specificato dalla collezione. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Restituisce l'indice basato su zero della chiave specificata nella collezione. |
| [contains(String name)](#contains-java.lang.String-) | Determina se la collezione contiene un nome specifico. |
| [removeAt(int index)](#removeAt-int-) | Rimuove il tag all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti i tag dalla collezione. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Restituisce il valore di un tag all'indice specificato. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Restituisce la chiave di un tag all'indice specificato. |
| [getNamesOfTags()](#getNamesOfTags--) | Restituisce i nomi dei tag. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Restituisce o imposta una coppia chiave/valore di un tag. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Restituisce o imposta una coppia chiave/valore di un tag. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi dalla collezione nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce la radice di sincronizzazione. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera collezione. |
### size() {#size--}
```
public final int size()
```


Restituisce il numero di tag nella collezione. Solo lettura int.

**Restituisce:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```


Aggiunge un nuovo tag alla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Il nome del tag. |
| value | java.lang.String | Il valore del tag. |

**Restituisce:**
int - L'indice del tag aggiunto.
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```


Rimuove il tag con un nome specificato dalla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Il nome del tag da rimuovere. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```


Restituisce l'indice basato su zero della chiave specificata nella collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Il nome da cercare nella collezione. |

**Restituisce:**
int - L'indice basato su zero della chiave, se la chiave è trovata nella collezione; altrimenti, -1.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


Determina se la collezione contiene un nome specifico.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | La chiave da cercare. |

**Restituisce:**
boolean - true se la collezione contiene un tag con la chiave specificata; altrimenti, false.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Rimuove il tag all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero del tag da rimuovere. |
### clear() {#clear--}
```
public final void clear()
```


Rimuove tutti i tag dalla collezione.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```


Restituisce il valore di un tag all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice del tag da restituire. |

**Restituisce:**
java.lang.String - Valore di un tag.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```


Restituisce la chiave di un tag all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice del tag da restituire. |

**Restituisce:**
java.lang.String - Chiave di un tag.
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```


Restituisce i nomi dei tag.

**Restituisce:**
java.lang.String[] - Nomi dei tag.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```


Restituisce o imposta una coppia chiave/valore di un tag.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Chiave di un tag. |

**Restituisce:**
java.lang.String - Valore di un tag.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```


Restituisce o imposta una coppia chiave/valore di un tag.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Chiave di un tag. |
| value | java.lang.String |  |
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia tutti gli elementi dalla collezione nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array da riempire. |
| index | int | Posizione iniziale nell'array di destinazione. |
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
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```


Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```


Restituisce un iteratore java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.