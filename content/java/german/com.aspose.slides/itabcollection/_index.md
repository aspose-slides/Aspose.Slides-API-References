---
title: ITabCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Sammlung von Tabs dar.
type: docs
url: /de/com.aspose.slides/itabcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

Stellt eine Sammlung von Tabs dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Liefert das Element am angegebenen Index. |
| [add(double position, int align)](#add-double-int-) | Fügt der Sammlung einen Tab hinzu. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Fügt der Sammlung einen Tab hinzu. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index der Sammlung. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```


Liefert das Element am angegebenen Index. Nur lesbar [ITab](../../com.aspose.slides/itab).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```


Fügt der Sammlung einen Tab hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | double | Tab-Position. |
| align | int | Tab-Ausrichtung. |

**Rückgabewert:**
[ITab](../../com.aspose.slides/itab) - Hinzugefügter Tab.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```


Fügt der Sammlung einen Tab hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Das Tab-Objekt, das am Ende der Sammlung hinzugefügt werden soll. |

**Rückgabewert:**
int - Der Index, an dem der Tab hinzugefügt wurde.
### clear() {#clear--}
```
public abstract void clear()
```


Entfernt alle Elemente aus der Sammlung.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Entfernt das Element am angegebenen Index der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |