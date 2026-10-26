---
title: RowCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt die Sammlung von Tabellenzeilen dar.
type: docs
url: /de/com.aspose.slides/rowcollection/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

Stellt die Sammlung von Tabellenzeilen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Ermittelt die tatsächlich in der Sammlung enthaltene Zeilenanzahl. |
| [get_Item(int index)](#get-Item-int-) | Gibt die Zeile am angegebenen Index zurück. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie am unteren Ende einer Tabelle ein. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie an der angegebenen Position in einer Tabelle ein. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Entfernt eine Zeile an der angegebenen Position aus einer Tabelle. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (Thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt ein Synchronisations-Root zurück. |
### size() {#size--}
```
public final int size()
```


Ermittelt die tatsächlich in der Sammlung enthaltene Zeilenanzahl. Nur lesbar int.

**Rückgabe:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```


Gibt die Zeile am angegebenen Index zurück. Nur lesbar [Row](../../com.aspose.slides/row).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```


Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie am unteren Ende einer Tabelle ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Zeile, die als Vorlage verwendet wird. |
| withAttachedRows | boolean | True, um ebenfalls alle an die Vorlagenzeile angehängten Zeilen zu kopieren. |

**Rückgabe:**
com.aspose.slides.IRow[] - Hinzugefügte Zeilen.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie an der angegebenen Position in einer Tabelle ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index einer neuen Zeile. |
| templ | [IRow](../../com.aspose.slides/irow) | Zeile, die als Vorlage verwendet wird. |
| withAttachedRows | boolean | True, um ebenfalls alle an die Vorlagenzeile angehängten Zeilen zu kopieren. |

**Rückgabe:**
com.aspose.slides.IRow[] - Eingefügte Zeilen.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```


Entfernt eine Zeile an der angegebenen Position aus einer Tabelle.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstRowIndex | int | Index einer zu löschenden Zeile. |
| withAttachedRows | boolean | True, um ebenfalls alle angehängten Zeilen zu löschen. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```


Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Ein IGenericEnumerator, der verwendet werden kann, um die Sammlung zu durchlaufen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```


Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Ein java.util.Iterator für die gesamte Sammlung.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopiert alle Elemente der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Zielarray. |
| index | int | Startindex im Zielarray. |

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


Gibt ein Synchronisations-Root zurück. Nur lesbar Object.

**Rückgabe:**
java.lang.Object