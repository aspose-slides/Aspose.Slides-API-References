---
title: Duotone
second_title: Aspose.Slides för Java API-referens
description: Representerar en Duotone-effekt.
type: docs
url: /sv/com.aspose.slides/duotone/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

Representerar en Duotone-effekt. För varje pixel kombineras Color1 och Color2 genom en linjär interpolation för att bestämma den nya färgen för den pixeln.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getColor1()](#getColor1--) | Returnerar målformatet för mörka pixlar. |
| [getColor2()](#getColor2--) | Returnerar målformatet för ljusa pixlar. |
| [getEffective()](#getEffective--) | Hämtar effektiv Duotone-effektsdata med arv tillämpat. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Avgör om den angivna [Duotone](../../com.aspose.slides/duotone) är lika med den aktuella [Duotone](../../com.aspose.slides/duotone). |
| [hashCode()](#hashCode--) | Fungerar som en hashfunktion för en viss typ. |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```


Returnerar målformatet för mörka pixlar. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```


Returnerar målformatet för ljusa pixlar. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```


Hämtar effektiv Duotone-effektsdata med arv tillämpat.

**Returnerar:**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - A [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Skrivskyddad long.

**Returnerar:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Avgör om den angivna [Duotone](../../com.aspose.slides/duotone) är lika med den aktuella [Duotone](../../com.aspose.slides/duotone).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Den [Duotone](../../com.aspose.slides/duotone) att jämföra. |

**Returnerar:**
boolean - true om objekten är lika; annars false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Fungerar som en hashfunktion för en viss typ.

**Returnerar:**
int - En hashkod för det aktuella objektet.