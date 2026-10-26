---
title: PointCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt eine Sammlung von Animationspunkten dar.
type: docs
url: /de/com.aspose.slides/pointcollection/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

Stellt eine Sammlung von Animationspunkten dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCount()](#getCount--) | Gibt die Anzahl der Punkte in der Sammlung zurück. |
| [get_Item(int index)](#get-Item-int-) | Gibt einen Punkt am angegebenen Index zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |

### PointCollection() {#PointCollection--}
```
public PointCollection()
```

### getCount() {#getCount--}
```
public final int getCount()
```

Gibt die Anzahl der Punkte in der Sammlung zurück. Nur lesbar int.

**Rückgabe:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```

Gibt einen Punkt am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Elements. |

**Rückgabe:**
[IPoint](../../com.aspose.slides/ipoint) - Das [IPoint](../../com.aspose.slides/ipoint) Objekt.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```

Gibt einen Enumerator zurück, der durch die Sammlung iteriert.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Ein IGenericEnumerator, der verwendet werden kann, um durch die Sammlung zu iterieren.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Ein java.util.Iterator für die gesamte Sammlung.