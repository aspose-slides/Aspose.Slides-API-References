---
title: TabCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt eine Sammlung von Registerkarten dar.
type: docs
url: /de/com.aspose.slides/tabcollection/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

Stellt eine Sammlung von Registerkarten dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Ermittelt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen. |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [add(double position, int align)](#add-double-int-) | Fügt der Sammlung ein Tab hinzu. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Fügt der Sammlung ein Tab hinzu. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index der Sammlung. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob zwei TabsEx-Instanzen gleich sind. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (Thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt ein Synchronisationsobjekt zurück. |
### size() {#size--}
```
public final int size()
```

Ermittelt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen. Nur lesbar int.

**Rückgabe:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```

Gibt das Element am angegebenen Index zurück. Nur lesbar [Tab](../../com.aspose.slides/tab).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```

Fügt der Sammlung ein Tab hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**Rückgabe:**
[ITab](../../com.aspose.slides/itab) - Hinzugefügtes Tab.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```

Fügt der Sammlung ein Tab hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Das Tab-Objekt, das am Ende der Sammlung hinzugefügt werden soll. |

**Rückgabe:**
int - Der Index, an dem das Tab hinzugefügt wurde.
### clear() {#clear--}
```
public final void clear()
```

Entfernt alle Elemente aus der Sammlung.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt das Element am angegebenen Index der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur lesbar IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestimmt, ob zwei TabsEx-Instanzen gleich sind.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das TabsEx, das mit dem aktuellen TabsEx verglichen werden soll. |

**Rückgabe:**
boolean - **true** wenn das angegebene TabsEx gleich dem aktuellen TabsEx ist; sonst **false**.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - Ein java.util.Iterator für die gesamte Sammlung.
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