---
title: ColumnCollection
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Sammlung von Spalten in einer Tabelle dar.
type: docs
url: /de/com.aspose.slides/columncollection/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

Stellt eine Sammlung von Spalten in einer Tabelle dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Gibt die Anzahl der Spalten in einer Sammlung zurück. |
| [get_Item(int index)](#get-Item-int-) | Gibt die Spalte am angegebenen Index zurück. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie am unteren Ende einer Tabelle ein. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Erstellt eine Kopie der angegebenen Vorlagenspalte und fügt sie an der angegebenen Position in einer Tabelle ein. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Entfernt eine Spalte an der angegebenen Position aus einer Tabelle. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt eine Synchronisationswurzel zurück. |

### size() {#size--}
```
public final int size()
```


Gibt die Anzahl der Spalten in einer Sammlung zurück. Nur lesbar int.

**Rückgabe:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```


Gibt die Spalte am angegebenen Index zurück. Nur lesbar [Column](../../com.aspose.slides/column).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IColumn](../../com.aspose.slides/icolumn)

### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie am unteren Ende einer Tabelle ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Spalte, die als Vorlage verwendet wird. |
| withAttachedColumns | boolean | True, um ebenfalls alle an die Vorlagenzeile angehängten Spalten zu kopieren. |

**Rückgabe:**
com.aspose.slides.IColumn[] - Hinzugefügte Spalten.

### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


Erstellt eine Kopie der angegebenen Vorlagenspalte und fügt sie an der angegebenen Position in einer Tabelle ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index einer neuen Spalte. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Spalte, die als Vorlage verwendet wird. |
| withAttachedColumns | boolean | True, um ebenfalls alle an die Vorlagenspalte angehängten Spalten zu kopieren. |

**Rückgabe:**
com.aspose.slides.IColumn[] – Eingefügte Spalten.

### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


Entfernt eine Spalte an der angegebenen Position aus einer Tabelle.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstColumnIndex | int | Index einer zu löschenden Spalte. |
| withAttachedRows | boolean | True, um ebenfalls alle angehängten Spalten zu löschen. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```


Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - Ein IGenericEnumerator, der verwendet werden kann, um die Sammlung zu durchlaufen.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```


Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - Ein java.util.Iterator für die gesamte Sammlung.

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


Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. Nur lesbar boolean.

**Rückgabe:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Gibt eine Synchronisationswurzel zurück. Nur lesbar Object.

**Rückgabe:**
java.lang.Object