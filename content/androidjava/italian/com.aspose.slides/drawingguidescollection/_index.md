---
title: DrawingGuidesCollection
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una collezione di guide di disegno regolabili.
type: docs
url: /it/com.aspose.slides/drawingguidescollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

Rappresenta una collezione di guide di disegno regolabili.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce la guida di disegno per indice. |
| [add(byte orientation, float position)](#add-byte-float-) | Aggiunge la guida di disegno alla fine della collezione. |
| [removeAt(int index)](#removeAt-int-) | Rimuove la guida di disegno all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla collezione. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore Java per l'intera collezione. |
| [getCount()](#getCount--) | Restituisce il numero di elementi nella collezione. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | Copia tutti gli elementi della collezione nell'array specificato. |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```


Restituisce la guida di disegno per indice. Sola lettura [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```


Aggiunge la guida di disegno alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| orientation | byte | Orientamento della guida di disegno. |
| position | float | Posizione della guida di disegno in punti. |

**Restituisce:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Rimuove la guida di disegno all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della guida di disegno da eliminare. |

### clear() {#clear--}
```
public final void clear()
```


Rimuove tutti gli elementi dalla collezione.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```


Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```


Restituisce un iteratore Java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - Un java.util.Iterator per l'intera collezione.
### getCount() {#getCount--}
```
public final int getCount()
```


Restituisce il numero di elementi nella collezione. Sola lettura int.

**Restituisce:**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```


Copia tutti gli elementi della collezione nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | Array di destinazione. |
| index | int | Indice di partenza nell'array di destinazione. |