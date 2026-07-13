---
title: Duotone
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een Duotone-effect voor.
type: docs
url: /nl/com.aspose.slides/duotone/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

Stelt een Duotone-effect voor. Voor elke pixel combineert het Color1 en Color2 via een lineaire interpolatie om de nieuwe kleur voor die pixel te bepalen.
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getColor1()](#getColor1--) | Retourneert het doelkleurformaat voor donkere pixels. |
| [getColor2()](#getColor2--) | Retourneert het doelkleurformaat voor lichte pixels. |
| [getEffective()](#getEffective--) | Haalt de effectieve Duotone-effectgegevens op met de overerving toegepast. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of de opgegeven [Duotone](../../com.aspose.slides/duotone) gelijk is aan de huidige [Duotone](../../com.aspose.slides/duotone). |
| [hashCode()](#hashCode--) | Dient als hashfunctie voor een bepaald type. |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```

Retourneert het doelkleurformaat voor donkere pixels. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retourneert:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```

Retourneert het doelkleurformaat voor lichte pixels. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retourneert:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```

Haalt de effectieve Duotone-effectgegevens op met de overerving toegepast.

**Retourneert:**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - Een [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versie. Alleen-lezen long.

**Retourneert:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bepaalt of de opgegeven [Duotone](../../com.aspose.slides/duotone) gelijk is aan de huidige [Duotone](../../com.aspose.slides/duotone).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | De [Duotone](../../com.aspose.slides/duotone) om te vergelijken. |

**Retourneert:**
boolean - true als objecten gelijk zijn; anders false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als hashfunctie voor een bepaald type.

**Retourneert:**
int - Een hashcode voor het huidige object.