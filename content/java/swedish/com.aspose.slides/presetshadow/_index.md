---
title: PresetShadow
second_title: Aspose.Slides för Java API-referens
description: Representerar en förinställd skuggeffekt.
type: docs
url: /sv/com.aspose.slides/presetshadow/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Representerar en förinställd skuggeffekt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDirection()](#getDirection--) | Riktning på skugga. |
| [setDirection(float value)](#setDirection-float-) | Riktning på skugga. |
| [getDistance()](#getDistance--) | Avstånd för skugga. |
| [setDistance(double value)](#setDistance-double-) | Avstånd för skugga. |
| [getShadowColor()](#getShadowColor--) | Färg på skugga. |
| [getPreset()](#getPreset--) | Förinställning. |
| [setPreset(int value)](#setPreset-int-) | Förinställning. |
| [getEffective()](#getEffective--) | Hämtar effektiva förinställda skuggeffektsdata med arvet tillämpat. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om den specificerade [PresetShadow](../../com.aspose.slides/presetshadow) är lika med den aktuella [PresetShadow](../../com.aspose.slides/presetshadow). |
| [hashCode()](#hashCode--) | Fungerar som en hashfunktion för en viss typ. |
### getDirection() {#getDirection--}
```
public final float getDirection()
```

Riktning på skugga. Läs/skriv  float .

**Returnerar:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Riktning på skugga. Läs/skriv  float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```

Avstånd för skugga. Läs/skriv  double .

**Returnerar:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Avstånd för skugga. Läs/skriv  double .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

Färg på skugga. Endast läs [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public final int getPreset()
```

Förinställning. Läs/skriv [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Returnerar:**
int
### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```

Förinställning. Läs/skriv [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```

Hämtar effektiva förinställda skuggeffektsdata med arvet tillämpat.

**Returnerar:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - En [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objekt. Endast läs IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Version. Endast läs long.

**Returnerar:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Returnerar förälder IPresentationComponent. Endast läs [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Returnerar:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestämmer om den specificerade [PresetShadow](../../com.aspose.slides/presetshadow) är lika med den aktuella [PresetShadow](../../com.aspose.slides/presetshadow).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Den [PresetShadow](../../com.aspose.slides/presetshadow) att jämföra. |

**Returnerar:**
boolean - true om objekten är lika; annars false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Fungerar som en hashfunktion för en viss typ.

**Returnerar:**
int - En hashkod för det aktuella objektet.