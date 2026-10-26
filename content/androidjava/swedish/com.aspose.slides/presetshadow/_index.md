---
title: PresetShadow
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en Preset Shadow-effekt.
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

Representerar en Preset Shadow-effekt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDirection()](#getDirection--) | Skuggans riktning. |
| [setDirection(float value)](#setDirection-float-) | Skuggans riktning. |
| [getDistance()](#getDistance--) | Skuggans avstånd. |
| [setDistance(double value)](#setDistance-double-) | Skuggans avstånd. |
| [getShadowColor()](#getShadowColor--) | Skuggans färg. |
| [getPreset()](#getPreset--) | Preset. |
| [setPreset(int value)](#setPreset-int-) | Preset. |
| [getEffective()](#getEffective--) | Hämtar effektiv Preset Shadow-effektsdata med ärftlighet tillämpad. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om den angivna [PresetShadow](../../com.aspose.slides/presetshadow) är lika med den aktuella [PresetShadow](../../com.aspose.slides/presetshadow). |
| [hashCode()](#hashCode--) | Fungerar som en hash-funktion för en viss typ. |
### getDirection() {#getDirection--}
```
public final float getDirection()
```

Skuggans riktning. Läs/skriv  float .

**Returnerar:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Skuggans riktning. Läs/skriv  float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```

Skuggans avstånd. Läs/skriv  double .

**Returnerar:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Skuggans avstånd. Läs/skriv  double .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

Skuggans färg. Endast läsning [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public final int getPreset()
```

Preset. Läs/skriv [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Returnerar:**
int
### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```

Preset. Läs/skriv [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```

Hämtar effektiv Preset Shadow-effektsdata med ärftlighet tillämpad.

**Returnerar:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - A [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objekt. Endast läsning IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Version. Endast läsning long.

**Returnerar:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Returnerar överordnad IPresentationComponent. Endast läsning [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Returnerar:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestämmer om den angivna [PresetShadow](../../com.aspose.slides/presetshadow) är lika med den aktuella [PresetShadow](../../com.aspose.slides/presetshadow).

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

Fungerar som en hash-funktion för en viss typ.

**Returnerar:**
int - En hashkod för det aktuella objektet.