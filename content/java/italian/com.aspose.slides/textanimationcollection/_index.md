---
title: TextAnimationCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una raccolta di animazioni di testo.
type: docs
url: /it/com.aspose.slides/textanimationcollection/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)
```
public class TextAnimationCollection implements ITextAnimationCollection
```

Rappresenta una raccolta di animazioni di testo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextAnimationCollection()](#TextAnimationCollection--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [size()](#size--) | Restituisce il numero di elementi nella raccolta. |
| [add()](#add--) | Aggiunge una nuova animazione di testo alla raccolta. |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento tramite indice. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Restituisce tutti gli elementi |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la raccolta. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera raccolta. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi dalla raccolta nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
### TextAnimationCollection() {#TextAnimationCollection--}
```
public TextAnimationCollection()
```


### size() {#size--}
```
public final int size()
```


Restituisce il numero di elementi nella raccolta. Solo lettura int.

**Restituisce:**
int
### add() {#add--}
```
public final TextAnimation add()
```


Aggiunge una nuova animazione di testo alla raccolta.

**Restituisce:**
[TextAnimation](../../com.aspose.slides/textanimation) - Added [TextAnimation](../../com.aspose.slides/textanimation)
### get_Item(int index) {#get-Item-int-}
```
public final ITextAnimation get_Item(int index)
```


Restituisce l'elemento tramite indice.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public final ITextAnimation[] get_Item(IShape shape)
```


Restituisce tutti gli elementi

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) to remove. |

**Restituisce:**
com.aspose.slides.ITextAnimation[] - Array of [ITextAnimation](../../com.aspose.slides/itextanimation)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iterator()
```


Restituisce un enumeratore che itera attraverso la raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iteratorJava()
```


Restituisce un iteratore java per l'intera raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia tutti gli elementi dalla raccolta nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array to fill. |
| index | int | Starting position in target array. |

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