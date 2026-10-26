---
title: IColumnCollection
second_title: Aspose.Slides für Android über Java API Reference
description: Stellt eine Sammlung von Spalten in einer Tabelle dar.
type: docs
url: /de/com.aspose.slides/icolumncollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

Stellt eine Sammlung von Spalten in einer Tabelle dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt die Spalte am angegebenen Index zurück. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie am unteren Ende einer Tabelle ein. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Erstellt eine Kopie der angegebenen Vorlage-Spalte und fügt sie an der angegebenen Position in einer Tabelle ein. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Entfernt eine Spalte an der angegebenen Position aus einer Tabelle. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```


Gibt die Spalte am angegebenen Index zurück. Nur lesbar [IColumn](../../com.aspose.slides/icolumn).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie am unteren Ende einer Tabelle ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Spalte, die als Vorlage verwendet wird. |
| withAttachedColumns | boolean | True, um ebenfalls alle an die Vorlagenzeile angehängten Spalten zu kopieren. |

**Rückgabewert:**
com.aspose.slides.IColumn[] - Hinzugefügte Spalten.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


Erstellt eine Kopie der angegebenen Vorlage-Spalte und fügt sie an der angegebenen Position in einer Tabelle ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der neuen Spalte. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Spalte, die als Vorlage verwendet wird. |
| withAttachedColumns | boolean | True, um ebenfalls alle an die Vorlage-Spalte angehängten Spalten zu kopieren. |

**Rückgabewert:**
com.aspose.slides.IColumn[] - Eingefügte Spalten.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


Entfernt eine Spalte an der angegebenen Position aus einer Tabelle.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstColumnIndex | int | Index der zu löschenden Spalte. |
| withAttachedRows | boolean | True, um ebenfalls alle angehängten Spalten zu löschen. |