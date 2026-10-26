---
title: DrawingGuidesCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una raccolta delle guide di disegno regolabili.
type: docs
url: /it/com.aspose.slides/drawingguidescollection/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

Rappresenta una raccolta delle guide di disegno regolabili.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce la guida di disegno per indice. |
| [add(byte orientation, float position)](#add-byte-float-) | Aggiunge la guida di disegno alla fine della raccolta. |
| [removeAt(int index)](#removeAt-int-) | Rimuove la guida di disegno all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla raccolta. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la raccolta. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera raccolta. |
| [getCount()](#getCount--) | Restituisce il numero di elementi nella raccolta. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | Copia tutti gli elementi dalla raccolta nell'array specificato. |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```

Restituisce la guida di disegno per indice. Solo lettura [IDrawingGuide](../../com.aspose.slides/idrawingguide).

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

Aggiunge la guida di disegno alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| orientation | byte | Orientamento della guida di disegno. |
| position | float | Posizione della guida di disegno in punti. |

**Restituisce:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt int index) {#removeAt-int-}
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

Rimuove tutti gli elementi dalla raccolta.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```

Restituisce un enumeratore che itera attraverso la raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - Un IGenericEnumerator che può essere usato per iterare attraverso la raccolta.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```

Restituisce un iteratore java per l'intera raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - Un java.util.Iterator per l'intera raccolta.
### getCount() {#getCount--}
```
public final int getCount()
```

Restituisce il numero di elementi nella raccolta. int di sola lettura.

**Restituisce:**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```

Copia tutti gli elementi dalla raccolta nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | Array di destinazione. |
| index | int | Indice iniziale nell'array di destinazione. |