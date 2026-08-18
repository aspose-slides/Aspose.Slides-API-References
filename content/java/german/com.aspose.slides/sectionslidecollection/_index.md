---
title: SectionSlideCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Sammlung von Folien im Abschnitt dar.
type: docs
url: /de/com.aspose.slides/sectionslidecollection/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)
```
public final class SectionSlideCollection extends DomObject<Section> implements ISectionSlideCollection
```

Stellt eine Sammlung von Folien im Abschnitt dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [size()](#size--) | Gibt die tatsächliche Anzahl der in der Sammlung enthaltenen Elemente zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert die gesamte Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (Thread-sicher). |
| [getSyncRoot()](#getSyncRoot--) | Gibt die Synchronisationswurzel zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```


Gibt das Element am angegebenen Index zurück. Nur lesbar [ISlide](../../com.aspose.slides/islide).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[ISlide](../../com.aspose.slides/islide)
### size() {#size--}
```
public final int size()
```


Gibt die tatsächliche Anzahl der in der Sammlung enthaltenen Elemente zurück. Nur lesbar int.

**Rückgabewert:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopiert die gesamte Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Zielarray |
| index | int | Index im Zielarray. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (Thread-sicher). Nur lesbar boolean.

**Rückgabewert:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Gibt die Synchronisationswurzel zurück. Nur lesbar Object.

**Rückgabewert:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```


Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```


Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Ein java.util.Iterator für die gesamte Sammlung.