---
title: LayoutSlideCollection
second_title: Aspose.Slides für Android über die Java API Referenz
description: Stellt eine Basisklasse für eine Sammlung von Layout-Folien dar.
type: docs
url: /de/com.aspose.slides/layoutslidecollection/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

Stellt eine Basisklasse für eine Sammlung von Layout-Folien dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Gibt die Anzahl der Layout-Folien in einer Sammlung zurück. |
| [get_Item(int index)](#get-Item-int-) | Gibt die Layout-Folie nach Index zurück. |
| [getByType(byte type)](#getByType-byte-) | Gibt die erste Layout-Folie des angegebenen Typs zurück. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Entfernt ein Layout aus der Sammlung. |
| [removeUnused()](#removeUnused--) | Entfernt unbenutzte Layout-Folien (Layout-Folien, deren HasDependingSlides false ist). |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-safe) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt ein Synchronisations-Root zurück. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```


Gibt die Anzahl der Layout-Folien in einer Sammlung zurück. Nur-Lese int.

**Rückgabewert:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```


Gibt die Layout-Folie nach Index zurück. Nur-Lese [LayoutSlide](../../com.aspose.slides/layoutslide).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```


Gibt die erste Layout-Folie des angegebenen Typs zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | byte | Ein Typ der zu findenden Layout-Folie. |

**Rückgabewert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) mit angegebenem Typ oder null, wenn keine Layouts gefunden wurden.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```


Entfernt ein Layout aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Die zu entfernende Layout-Folie aus der Sammlung.

--------------------

1) Um das Werfen von PptxEditException zu vermeiden, prüfen Sie vorab die HasDependingSlides-Eigenschaft des Layouts. 2) Sie können auch die [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove)-Methode verwenden, um den Code zu vereinfachen. |
### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```


Entfernt unbenutzte Layout-Folien (Layout-Folien, deren HasDependingSlides false ist).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```


Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```


Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - An java.util.Iterator for the entire collection.
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


Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-safe) ist. Nur-Lese boolean.

**Rückgabewert:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Gibt ein Synchronisations-Root zurück. Nur-Lese Object.

**Rückgabewert:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Gibt das Parent_Immediate-Objekt zurück. Nur-Lese IDOMObject.

**Rückgabewert:**
com.aspose.slides.IDOMObject