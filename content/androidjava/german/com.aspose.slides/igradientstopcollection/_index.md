---
title: IGradientStopCollection
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Sammlung von Farbverlaufspunkten dar.
type: docs
url: /de/com.aspose.slides/igradientstopcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Stellt eine Sammlung von Farbverlaufspunkten dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt den Farbverlaufspunkt nach Index zurück. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Erstellt den neuen Farbverlaufspunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Erstellt den neuen Farbverlaufspunkt und fügt ihn am Ende der Sammlung hinzu. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Erstellt den neuen Farbverlaufspunkt und fügt ihn am Ende der Sammlung hinzu. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Erstellt den neuen Farbverlaufspunkt und fügt ihn an dem angegebenen Index in die Sammlung ein. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Erstellt den neuen Farbverlaufspunkt und fügt ihn an dem angegebenen Index in die Sammlung ein. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Erstellt den neuen Farbverlaufspunkt und fügt ihn an dem angegebenen Index in die Sammlung ein. |
| [removeAt(int index)](#removeAt-int-) | Entfernt einen Farbverlaufspunkt an dem angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Farbverlaufspunkte aus einer Sammlung. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```


Gibt den Farbverlaufspunkt nach Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public abstract IGradientStop add(float position, Integer color)
```


Erstellt den neuen Farbverlaufspunkt und fügt ihn am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | float | Position des neuen Farbverlaufspunkts. |
| color | java.lang.Integer | Farbe des neuen Farbverlaufspunkts. |

**Rückgabe:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index des neuen Farbverlaufspunkts in der Sammlung.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```


Erstellt den neuen Farbverlaufspunkt und fügt ihn am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | float | Position des neuen Farbverlaufspunkts. |
| presetColor | int | Farbe des neuen Farbverlaufspunkts. |

**Rückgabe:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index des neuen Farbverlaufspunkts in der Sammlung.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```


Erstellt den neuen Farbverlaufspunkt und fügt ihn am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | float | Position des neuen Farbverlaufspunkts. |
| schemeColor | int | Farbe des neuen Farbverlaufspunkts. |

**Rückgabe:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index des neuen Farbverlaufspunkts in der Sammlung.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```


Erstellt den neuen Farbverlaufspunkt und fügt ihn an dem angegebenen Index in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index in der Sammlung, an dem der neue Farbverlaufspunkt eingefügt wird. |
| position | float | Position des neuen Farbverlaufspunkts. |
| color | java.lang.Integer | Farbe des neuen Farbverlaufspunkts. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```


Erstellt den neuen Farbverlaufspunkt und fügt ihn an dem angegebenen Index in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index in der Sammlung, an dem der neue Farbverlaufspunkt eingefügt wird. |
| position | float | Position des neuen Farbverlaufspunkts. |
| presetColor | int | Farbe des neuen Farbverlaufspunkts. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```


Erstellt den neuen Farbverlaufspunkt und fügt ihn an dem angegebenen Index in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index in der Sammlung, an dem der neue Farbverlaufspunkt eingefügt wird. |
| position | float | Position des neuen Farbverlaufspunkts. |
| schemeColor | int | Farbe des neuen Farbverlaufspunkts. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Entfernt einen Farbverlaufspunkt an dem angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index eines Farbverlaufspunkts, der gelöscht werden soll. |

### clear() {#clear--}
```
public abstract void clear()
```


Entfernt alle Farbverlaufspunkte aus einer Sammlung.