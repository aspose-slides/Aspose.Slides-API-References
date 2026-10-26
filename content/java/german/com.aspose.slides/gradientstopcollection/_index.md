---
title: GradientStopCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Sammlung von Farbverlaufsstopps dar.
type: docs
url: /de/com.aspose.slides/gradientstopcollection/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

Stellt eine Sammlung von Farbverlaufsstopps dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | Gibt die Anzahl der Farbverlaufsstopps in einer Sammlung zurück. |
| [get_Item(int index)](#get-Item-int-) | Gibt den Farbverlaufsstopp nach Index zurück. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | Erstellt den neuen Farbverlaufsstopp und fügt ihn am Ende der Sammlung hinzu. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Erstellt den neuen Farbverlaufsstopp und fügt ihn am Ende der Sammlung hinzu. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Erstellt den neuen Farbverlaufsstopp und fügt ihn am Ende der Sammlung hinzu. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | Erstellt den neuen Farbverlaufsstopp und fügt ihn an der angegebenen Position in die Sammlung ein. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Erstellt den neuen Farbverlaufsstopp und fügt ihn an der angegebenen Position in die Sammlung ein. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Erstellt den neuen Farbverlaufsstopp und fügt ihn an der angegebenen Position in die Sammlung ein. |
| [removeAt(int index)](#removeAt-int-) | Entfernt einen Farbverlaufsstopp an der angegebenen Position. |
| [clear()](#clear--) | Entfernt alle Farbverlaufsstopps aus einer Sammlung. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen java iterator für die gesamte Sammlung zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt ein Synchronisationsobjekt zurück. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Nur-Lesen long.

**Rückgabewert:**
long
### size() {#size--}
```
public final int size()
```


Gibt die Anzahl der Farbverlaufsstopps in einer Sammlung zurück. Nur-Lesen  int .

**Rückgabewert:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
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
public final IGradientStop add(float position, Color color)
```


Erstellt den neuen Farbverlaufsstopp und fügt ihn am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | float | Position des neuen Farbverlaufsstopps. |
| color | java.awt.Color | Farbe des neuen Farbverlaufsstopps. |

**Rückgabewert:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index des neuen Farbverlaufsstopps in der Sammlung.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```


Erstellt den neuen Farbverlaufsstopp und fügt ihn am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | float | Position des neuen Farbverlaufsstopps. |
| presetColor | int | Farbe des neuen Farbverlaufsstopps. |

**Rückgabewert:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index des neuen Farbverlaufsstopps in der Sammlung.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```


Erstellt den neuen Farbverlaufsstopp und fügt ihn am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | float | Position des neuen Farbverlaufsstopps. |
| schemeColor | int | Farbe des neuen Farbverlaufsstopps. |

**Rückgabewert:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index des neuen Farbverlaufsstopps in der Sammlung.
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public final void insert(int index, float position, Color color)
```


Erstellt den neuen Farbverlaufsstopp und fügt ihn an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index in der Sammlung, an dem der neue Farbverlaufsstopp eingefügt wird. |
| position | float | Position des neuen Farbverlaufsstopps. |
| color | java.awt.Color | Farbe des neuen Farbverlaufsstopps. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```


Erstellt den neuen Farbverlaufsstopp und fügt ihn an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index in der Sammlung, an dem der neue Farbverlaufsstopp eingefügt wird. |
| position | float | Position des neuen Farbverlaufsstopps. |
| presetColor | int | Farbe des neuen Farbverlaufsstopps. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```


Erstellt den neuen Farbverlaufsstopp und fügt ihn an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index in der Sammlung, an dem der neue Farbverlaufsstopp eingefügt wird. |
| position | float | Position des neuen Farbverlaufsstopps. |
| schemeColor | int | Farbe des neuen Farbverlaufsstopps. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Entfernt einen Farbverlaufsstopp an der angegebenen Position.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index eines Farbverlaufsstopps, der gelöscht werden soll. |

### clear() {#clear--}
```
public final void clear()
```


Entfernt alle Farbverlaufsstopps aus einer Sammlung.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```


Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```


Gibt einen java iterator für die gesamte Sammlung zurück.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Ein java.util.Iterator für die gesamte Sammlung.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopiert alle Elemente der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Ziel-Array. |
| index | int | Start-Index im Ziel-Array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. Nur-Lesen  boolean .

**Rückgabewert:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Gibt ein Synchronisationsobjekt zurück. Nur-Lesen Object.

**Rückgabewert:**
java.lang.Object