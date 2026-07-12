---
title: DrawingGuidesCollection
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Sammlung der einstellbaren Zeichenhilfen dar.
type: docs
url: /de/com.aspose.slides/drawingguidescollection/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

Stellt eine Sammlung der einstellbaren Zeichenhilfen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt die Zeichenhilfe am Index zurück. |
| [add(byte orientation, float position)](#add-byte-float-) | Fügt die Zeichenhilfe am Ende der Sammlung hinzu. |
| [removeAt(int index)](#removeAt-int-) | Entfernt die Zeichenhilfe am angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [getCount()](#getCount--) | Gibt die Anzahl der Elemente in der Sammlung zurück. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | Kopiert alle Elemente der Sammlung in das angegebene Array. |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```


Gibt die Zeichenhilfe am Index zurück. Nur Lesezugriff [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```


Fügt die Zeichenhilfe am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| orientation | byte | Ausrichtung der Zeichenhilfe. |
| position | float | Position der Zeichenhilfe in Punkten. |

**Rückgabewert:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Entfernt die Zeichenhilfe am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der zu löschenden Zeichenhilfe. |

### clear() {#clear--}
```
public final void clear()
```


Entfernt alle Elemente aus der Sammlung.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```


Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```


Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - Ein java.util.Iterator für die gesamte Sammlung.
### getCount() {#getCount--}
```
public final int getCount()
```


Gibt die Anzahl der Elemente in der Sammlung zurück. Nur Lesezugriff int.

**Rückgabewert:**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```


Kopiert alle Elemente der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | Ziel-Array. |
| index | int | Startindex im Ziel-Array. |