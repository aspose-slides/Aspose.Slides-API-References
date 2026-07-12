---
title: ITabCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt eine Sammlung von Tabulatoren dar.
type: docs
url: /de/com.aspose.slides/itabcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

Stellt eine Sammlung von Tabulatoren dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [add(double position, int align)](#add-double-int-) | Fügt einen Tab zur Sammlung hinzu. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Fügt einen Tab zur Sammlung hinzu. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index der Sammlung. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```


Gibt das Element am angegebenen Index zurück. Nur lesbar [ITab](../../com.aspose.slides/itab).

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


Fügt einen Tab zur Sammlung hinzu.

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


Fügt einen Tab zur Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Das Tab-Objekt, das am Ende der Sammlung hinzugefügt wird. |

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