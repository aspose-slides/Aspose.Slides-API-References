---
title: Duotone
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Duoton-Effekt dar.
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

Stellt einen Duoton-Effekt dar. Für jedes Pixel kombiniert es Color1 und Color2 durch eine lineare Interpolation, um die neue Farbe für dieses Pixel zu bestimmen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColor1()](#getColor1--) | Gibt das Zielfarbformat für dunkle Pixel zurück. |
| [getColor2()](#getColor2--) | Gibt das Zielfarbformat für helle Pixel zurück. |
| [getEffective()](#getEffective--) | Ruft die effektiven Duoton-Effektdaten mit angewandter Vererbung ab. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene [Duotone](../../com.aspose.slides/duotone) gleich dem aktuellen [Duotone](../../com.aspose.slides/duotone) ist. |
| [hashCode()](#hashCode--) | Dient als Hashfunktion für einen bestimmten Typ. |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```


Gibt das Zielfarbformat für dunkle Pixel zurück. Nur-Lesen [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```


Gibt das Zielfarbformat für helle Pixel zurück. Nur-Lesen [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```


Ruft die effektiven Duoton-Effektdaten mit angewandter Vererbung ab.

**Rückgabe:**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - Ein [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Nur-Lesen long.

**Rückgabe:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene [Duotone](../../com.aspose.slides/duotone) gleich dem aktuellen [Duotone](../../com.aspose.slides/duotone) ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Der [Duotone](../../com.aspose.slides/duotone) zum Vergleichen. |

**Rückgabe:**
boolean - true, wenn Objekte gleich sind; andernfalls false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als Hashfunktion für einen bestimmten Typ.

**Rückgabe:**
int - Ein Hashcode für das aktuelle Objekt.