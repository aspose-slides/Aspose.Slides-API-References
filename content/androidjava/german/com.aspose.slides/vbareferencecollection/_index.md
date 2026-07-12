---
title: VbaReferenceCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt eine Sammlung von VBA-Projekt-Referenzen dar.
type: docs
url: /de/com.aspose.slides/vbareferencecollection/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
```
public class VbaReferenceCollection implements IVbaReferenceCollection
```

Stellt eine Sammlung von VBA-Projektreferenzen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Gibt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen zurück. |
| [add(IVbaReference value)](#add-com.aspose.slides.IVbaReference-) | Fügt die neue Referenz zur Referenzsammlung hinzu. |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (Thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt ein Synchronisationsobjekt zurück. |

### size() {#size--}
```
public final int size()
```


Gibt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen zurück. Nur lesbar int.

**Rückgabe:**
int

### add(IVbaReference value) {#add-com.aspose.slides.IVbaReference-}
```
public final void add(IVbaReference value)
```


Fügt die neue Referenz zur Referenzsammlung hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IVbaReference](../../com.aspose.slides/ivbareference) |  |

### get_Item(int index) {#get-Item-int-}
```
public final IVbaReference get_Item(int index)
```


Gibt das Element am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IVbaReference](../../com.aspose.slides/ivbareference)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaReference> iterator()
```


Gibt einen Enumerator zurück, der durch die Sammlung iteriert.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaReference> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaReference> iteratorJava()
```


Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaReference> - Ein java.util.Iterator für die gesamte Sammlung.

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