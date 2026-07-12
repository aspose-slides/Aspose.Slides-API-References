---
title: Duotone
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt einen Duotone-Effekt dar.
type: docs
url: /de/com.aspose.slides/duotone/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

Stellt einen Duotone-Effekt dar. Für jedes Pixel werden Color1 und Color2 durch lineare Interpolation kombiniert, um die neue Farbe für dieses Pixel zu bestimmen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColor1()](#getColor1--) | Gibt das Zielfarbformat für dunkle Pixel zurück. |
| [getColor2()](#getColor2--) | Gibt das Zielfarbformat für helle Pixel zurück. |
| [getEffective()](#getEffective--) | Ermittelt die effektiven Duotone-Effektdaten mit angewandter Vererbung. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene [Duotone](../../com.aspose.slides/duotone) gleich dem aktuellen [Duotone](../../com.aspose.slides/duotone) ist. |
| [hashCode()](#hashCode--) | Dient als Hashfunktion für einen bestimmten Typ. |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```


Gibt das Zielfarbformat für dunkle Pixel zurück. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabewert:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```


Gibt das Zielfarbformat für helle Pixel zurück. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabewert:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```


Ermittelt die effektiven Duotone-Effektdaten mit angewandter Vererbung.

**Rückgabewert:**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - Ein [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Nur lesbare long.

**Rückgabewert:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene [Duotone](../../com.aspose.slides/duotone) gleich dem aktuellen [Duotone](../../com.aspose.slides/duotone) ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das [Duotone](../../com.aspose.slides/duotone) zum Vergleich. |

**Rückgabewert:**
boolean - true, wenn die Objekte gleich sind; andernfalls false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als Hashfunktion für einen bestimmten Typ.

**Rückgabewert:**
int - Ein Hashcode für das aktuelle Objekt.