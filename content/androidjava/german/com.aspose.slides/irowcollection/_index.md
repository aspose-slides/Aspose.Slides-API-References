---
title: IRowCollection
second_title: Aspose.Slides für Android über Java-API-Referenz
description: Stellt die Zeilensammlung einer Tabelle dar.
type: docs
url: /de/com.aspose.slides/irowcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

Stellt die Zeilensammlung einer Tabelle dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ruft das Element am angegebenen Index ab. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie am unteren Ende einer Tabelle ein. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie an der angegebenen Position in einer Tabelle ein. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Entfernt eine Zeile an der angegebenen Position aus einer Tabelle. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```


Ruft das Element am angegebenen Index ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```


Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie am unteren Ende einer Tabelle ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Zeile, die als Vorlage verwendet wird. |
| withAttachedRows | boolean | True, um ebenfalls alle an die Vorlagenzeile angehängten Zeilen zu kopieren. |

**Rückgabewert:**
com.aspose.slides.IRow[] - Hinzugefügte Zeilen.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie an der angegebenen Position in einer Tabelle ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index einer neuen Zeile. |
| templ | [IRow](../../com.aspose.slides/irow) | Zeile, die als Vorlage verwendet wird. |
| withAttachedRows | boolean | True, um ebenfalls alle an die Vorlagenzeile angehängten Zeilen zu kopieren. |

**Rückgabewert:**
com.aspose.slides.IRow[] - Eingefügte Zeilen.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```


Entfernt eine Zeile an der angegebenen Position aus einer Tabelle.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstRowIndex | int | Index der zu löschenden Zeile. |
| withAttachedRows | boolean | True, um ebenfalls alle angehängten Zeilen zu löschen. |