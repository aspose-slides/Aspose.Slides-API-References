---
title: GradientStopCollection
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt eine Sammlung von Gradient-Stopps dar.
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

Stellt eine Sammlung von Gradient-Stopps dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | Gibt die Anzahl der Gradient-Stopps in einer Sammlung zurück. |
| [get_Item(int index)](#get-Item-int-) | Gibt den Gradient-Stop anhand des Index zurück. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Erstellt den neuen Gradient-Stop und fügt ihn am Ende der Sammlung hinzu. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Erstellt den neuen Gradient-Stop und fügt ihn am Ende der Sammlung hinzu. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Erstellt den neuen Gradient-Stop und fügt ihn am Ende der Sammlung hinzu. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Erstellt den neuen Gradient-Stop und fügt ihn an der angegebenen Stelle in die Sammlung ein. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Erstellt den neuen Gradient-Stop und fügt ihn an der angegebenen Stelle in die Sammlung ein. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Erstellt den neuen Gradient-Stop und fügt ihn an der angegebenen Stelle in die Sammlung ein. |
| [removeAt(int index)](#removeAt-int-) | Entfernt einen Gradient-Stop an dem angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Gradient-Stopps aus einer Sammlung. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen java-Iterator für die gesamte Sammlung zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (Thread-sicher). |
| [getSyncRoot()](#getSyncRoot--) | Gibt einen Synchronisations-Root zurück. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur-Lese long.

**Rückgabe:**
long
### size() {#size--}
```
public final int size()
```

Gibt die Anzahl der Gradient-Stopps in einer Sammlung zurück. Nur-Lese int .

**Rückgabe:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```

Gibt den Gradient-Stop anhand des Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public final IGradientStop add(float position, Integer color)
```

Erstellt den neuen Gradient-Stop und fügt ihn am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | float | Position des neuen Gradient-Stopps. |
| color | java.lang.Integer | Farbe des neuen Gradient-Stopps. |

**Rückgabe:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index des neuen Gradient-Stopps in der Sammlung.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```

Erstellt den neuen Gradient-Stop und fügt ihn am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | float | Position des neuen Gradient-Stopps. |
| presetColor | int | Farbe des neuen Gradient-Stopps. |

**Rückgabe:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index des neuen Gradient-Stopps in der Sammlung.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```

Erstellt den neuen Gradient-Stop und fügt ihn am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | float | Position des neuen Gradient-Stopps. |
| schemeColor | int | Farbe des neuen Gradient-Stopps. |

**Rückgabe:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index des neuen Gradient-Stopps in der Sammlung.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public final void insert(int index, float position, Integer color)
```

Erstellt den neuen Gradient-Stop und fügt ihn an der angegebenen Stelle in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index in der Sammlung, an dem der neue Gradient-Stop eingefügt wird. |
| position | float | Position des neuen Gradient-Stopps. |
| color | java.lang.Integer | Farbe des neuen Gradient-Stopps. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```

Erstellt den neuen Gradient-Stop und fügt ihn an der angegebenen Stelle in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index in der Sammlung, an dem der neue Gradient-Stop eingefügt wird. |
| position | float | Position des neuen Gradient-Stopps. |
| presetColor | int | Farbe des neuen Gradient-Stopps. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```

Erstellt den neuen Gradient-Stop und fügt ihn an der angegebenen Stelle in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index in der Sammlung, an dem der neue Gradient-Stop eingefügt wird. |
| position | float | Position des neuen Gradient-Stopps. |
| schemeColor | int | Farbe des neuen Gradient-Stopps. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt einen Gradient-Stop an dem angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index eines Gradient-Stopps, der gelöscht werden soll. |

### clear() {#clear--}
```
public final void clear()
```

Entfernt alle Gradient-Stopps aus einer Sammlung.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Ein IGenericEnumerator, der verwendet werden kann, um die Sammlung zu durchlaufen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```

Gibt einen java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
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
| index | int | Startindex im Ziel-Array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (Thread-sicher). Nur-Lese boolean .

**Rückgabe:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Gibt einen Synchronisations-Root zurück. Nur-Lese Object.

**Rückgabe:**
java.lang.Object