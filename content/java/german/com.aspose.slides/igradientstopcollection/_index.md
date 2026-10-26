---
title: IGradientStopCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Sammlung von Farbverlaufsstopps dar.
type: docs
url: /de/com.aspose.slides/igradientstopcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Stellt eine Sammlung von Farbverlaufsstopps dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt den Farbverlaufsstopp nach Index zurück. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | Erstellt einen neuen Farbverlaufsstopp und fügt ihn am Ende der Sammlung hinzu. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Erstellt einen neuen Farbverlaufsstopp und fügt ihn am Ende der Sammlung hinzu. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Erstellt einen neuen Farbverlaufsstopp und fügt ihn am Ende der Sammlung hinzu. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | Erstellt einen neuen Farbverlaufsstopp und fügt ihn am Ende der Sammlung hinzu. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Erstellt einen neuen Farbverlaufsstopp und fügt ihn am Ende der Sammlung hinzu. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Erstellt einen neuen Farbverlaufsstopp und fügt ihn am Ende der Sammlung hinzu. |
| [removeAt(int index)](#removeAt-int-) | Entfernt einen Farbverlaufsstopp an dem angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Farbverlaufsstopps aus einer Sammlung. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```


Gibt den Farbverlaufsstopp nach Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Color color) {#add-float-java.awt.Color-}
```
public abstract IGradientStop add(float position, Color color)
```


Erstellt einen neuen Farbverlaufsstopp und fügt ihn am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | float | Position des neuen Farbverlaufsstopps. |
| color | java.awt.Color | Farbe des neuen Farbverlaufsstopps. |

**Rückgabewert:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index des neuen Farbverlaufsstopps in der Sammlung.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```


Erstellt einen neuen Farbverlaufsstopp und fügt ihn am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | float | Position des neuen Farbverlaufsstopps. |
| presetColor | int | Farbe des neuen Farbverlaufsstopps. |

**Rückgabewert:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index des neuen Farbverlaufsstopps in der Sammlung.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```


Erstellt einen neuen Farbverlaufsstopp und fügt ihn am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | float | Position des neuen Farbverlaufsstopps. |
| schemeColor | int | Farbe des neuen Farbverlaufsstopps. |

**Rückgabewert:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index des neuen Farbverlaufsstopps in der Sammlung.
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public abstract void insert(int index, float position, Color color)
```


Erstellt einen neuen Farbverlaufsstopp und fügt ihn an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index in der Sammlung, an dem der neue Farbverlaufsstopp eingefügt wird. |
| position | float | Position des neuen Farbverlaufsstopps. |
| color | java.awt.Color | Farbe des neuen Farbverlaufsstopps. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```


Erstellt einen neuen Farbverlaufsstopp und fügt ihn an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index in der Sammlung, an dem der neue Farbverlaufsstopp eingefügt wird. |
| position | float | Position des neuen Farbverlaufsstopps. |
| presetColor | int | Farbe des neuen Farbverlaufsstopps. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```


Erstellt einen neuen Farbverlaufsstopp und fügt ihn an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index in der Sammlung, an dem der neue Farbverlaufsstopp eingefügt wird. |
| position | float | Position des neuen Farbverlaufsstopps. |
| schemeColor | int | Farbe des neuen Farbverlaufsstopps. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Entfernt einen Farbverlaufsstopp an dem angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index eines Farbverlaufsstopps, der gelöscht werden soll. |

### clear() {#clear--}
```
public abstract void clear()
```


Entfernt alle Farbverlaufsstopps aus einer Sammlung.