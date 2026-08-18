---
title: IDrawingGuidesCollection
second_title: Aspose.Slides für Java API Referenz
description: Stellt eine Sammlung der anpassbaren Zeichenführungen dar.
type: docs
url: /de/com.aspose.slides/idrawingguidescollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

Stellt eine Sammlung der anpassbaren Zeichenführungen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt die Zeichenführung anhand des Index zurück. |
| [add(byte orientation, float position)](#add-byte-float-) | Fügt die Zeichenführung am Ende der Sammlung hinzu. |
| [removeAt(int index)](#removeAt-int-) | Entfernt die Zeichenführung am angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [getCount()](#getCount--) | Ermittelt die Anzahl aller Elemente in der Sammlung. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```

Gibt die Zeichenführung anhand des Index zurück. Nur lesbar [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```

Fügt die Zeichenführung am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| orientation | byte | Ausrichtung der Zeichenführung. |
| position | float | Position der Zeichenführung in Punkten. |

**Rückgabewert:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Entfernt die Zeichenführung am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der Zeichenführung, die gelöscht werden soll. |

### clear() {#clear--}
```
public abstract void clear()
```

Entfernt alle Elemente aus der Sammlung.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Ermittelt die Anzahl aller Elemente in der Sammlung. Nur lesbar int.

**Rückgabewert:**
int