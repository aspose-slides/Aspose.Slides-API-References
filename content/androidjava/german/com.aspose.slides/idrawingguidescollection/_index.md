---
title: IDrawingGuidesCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt eine Sammlung der anpassbaren Zeichenleitfäden dar.
type: docs
url: /de/com.aspose.slides/idrawingguidescollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

Stellt eine Sammlung der anpassbaren Zeichenleitfäden dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt den Zeichenleitfaden nach Index zurück. |
| [add(byte orientation, float position)](#add-byte-float-) | Fügt den Zeichenleitfaden am Ende der Sammlung hinzu. |
| [removeAt(int index)](#removeAt-int-) | Entfernt den Zeichenleitfaden am angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [getCount()](#getCount--) | Ermittelt die Anzahl aller Elemente in der Sammlung. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```


Gibt den Zeichenleitfaden nach Index zurück. Nur lesbar [IDrawingGuide](../../com.aspose.slides/idrawingguide).

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


Fügt den Zeichenleitfaden am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| orientation | byte | Ausrichtung des Zeichenleitfadens. |
| position | float | Position des Zeichenleitfadens in Punkten. |

**Rückgabewert:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Entfernt den Zeichenleitfaden am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des zu löschenden Zeichenleitfadens. |

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