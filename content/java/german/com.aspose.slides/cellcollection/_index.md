---
title: CellCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Sammlung von Zellen dar.
type: docs
url: /de/com.aspose.slides/cellcollection/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), com.aspose.slides.IDOMObject
```
public abstract class CellCollection implements ICellCollection, IDOMObject
```

Stellt eine Sammlung von Zellen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [size()](#size--) | Gibt die Anzahl der Zellen in einer Sammlung zurück. |
| [get_Item(int index)](#get-Item-int-) | Gibt eine Zelle anhand ihrer Position zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie einer CellCollection zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation einer CellCollection zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt die Synchronisationswurzel zurück. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur-Lesen IDOMObject.

**Rückgabewert:**
com.aspose.slides.IDOMObject
### size() {#size--}
```
public final int size()
```

Gibt die Anzahl der Zellen in einer Sammlung zurück. Nur-Lesen int.

**Rückgabewert:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICell get_Item(int index)
```

Gibt eine Zelle anhand ihrer Position zurück. Nur-Lesen [Cell](../../com.aspose.slides/cell).

--------------------

Ein Cell-Objekt kann für mehrere Indizes zurückgegeben werden, falls cell zusammengeführt ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[ICell](../../com.aspose.slides/icell)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - Ein java.util.Iterator für die gesamte Sammlung.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Gibt die übergeordnete Folie einer CellCollection zurück. Nur-Lesen [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Rückgabewert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Gibt die übergeordnete Präsentation einer CellCollection zurück. Nur-Lesen [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabewert:**
[IPresentation](../../com.aspose.slides/ipresentation)
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiert alle Elemente der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Ziel-Array. |
| index | int | Startindex im Ziel-Array. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. Nur-Lesen boolean.

**Rückgabewert:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Gibt eine Synchronisationswurzel zurück. Nur-Lesen Object.

**Rückgabewert:**
java.lang.Object