---
title: SmartArtShapeCollection
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Sammlung von SmartArt-Formen dar
type: docs
url: /de/com.aspose.slides/smartartshapecollection/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
```
public class SmartArtShapeCollection implements ISmartArtShapeCollection
```

Stellt eine Sammlung von SmartArt-Formen dar
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Gibt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen zurück. |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (Thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt ein Synchronisationsobjekt zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente aus der Sammlung in das angegebene Array. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
### size() {#size--}
```
public final int size()
```


Gibt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen zurück. Nur lesbar int.

**Rückgabe:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtShape get_Item(int index)
```


Gibt das Element am angegebenen Index zurück. Nur lesbar [SmartArtShape](../../com.aspose.slides/smartartshape).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der Form |

**Rückgabe:**
[ISmartArtShape](../../com.aspose.slides/ismartartshape) - Die SmartArt-Form
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (Thread-sicher) ist. Nur lesbar boolean.

**Rückgabe:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Gibt ein Synchronisationsobjekt zurück. Nur lesbar Object.

**Rückgabe:**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopiert alle Elemente aus der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Ziel-Array. |
| index | int | Startindex im Ziel-Array. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iterator()
```


Gibt einen Enumerator zurück, der durch die Sammlung iteriert.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - Ein IGenericEnumerator, der verwendet werden kann, um durch die Sammlung zu iterieren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iteratorJava()
```


Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - Ein java.util.Iterator für die gesamte Sammlung.