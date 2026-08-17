---
title: ColorChange
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Color Change-Effekt dar.
type: docs
url: /de/com.aspose.slides/colorchange/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

Repräsentiert einen Color Change-Effekt. Instanzen von FromColor werden durch Instanzen von ToColor ersetzt.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFromColor()](#getFromColor--) | Farbe, die ersetzt wird. |
| [getToColor()](#getToColor--) | Farbe, die ersetzt. |
| [getEffective()](#getEffective--) | Ruft wirksame Color Change-Effektdaten mit angewandter Vererbung ab. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene [ColorChange](../../com.aspose.slides/colorchange) gleich dem aktuellen [ColorChange](../../com.aspose.slides/colorchange) ist. |
| [hashCode()](#hashCode--) | Dient als Hashfunktion für einen bestimmten Typ. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```


Farbe, die ersetzt wird. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```


Farbe, die ersetzt. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```


Ruft wirksame Color Change-Effektdaten mit angewandter Vererbung ab.

**Rückgabe:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - Ein [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Nur lesbar long.

**Rückgabe:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene [ColorChange](../../com.aspose.slides/colorchange) gleich dem aktuellen [ColorChange](../../com.aspose.slides/colorchange) ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das [ColorChange](../../com.aspose.slides/colorchange) zum Vergleichen. |

**Rückgabe:**
boolean - true, wenn Objekte gleich sind; sonst false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als Hashfunktion für einen bestimmten Typ.

**Rückgabe:**
int - Ein Hashcode für das aktuelle Objekt.