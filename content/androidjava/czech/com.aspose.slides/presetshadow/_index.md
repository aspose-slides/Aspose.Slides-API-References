---
title: PresetShadow
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Představuje přednastavený stínový efekt.
type: docs
url: /cs/com.aspose.slides/presetshadow/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Představuje přednastavený stínový efekt.
## Metody

| Metoda | Popis |
| --- | --- |
| [getDirection()](#getDirection--) | Směr stínu. |
| [setDirection(float value)](#setDirection-float-) | Směr stínu. |
| [getDistance()](#getDistance--) | Vzdálenost stínu. |
| [setDistance(double value)](#setDistance-double-) | Vzdálenost stínu. |
| [getShadowColor()](#getShadowColor--) | Barva stínu. |
| [getPreset()](#getPreset--) | Předvolba. |
| [setPreset(int value)](#setPreset-int-) | Předvolba. |
| [getEffective()](#getEffective--) | Získá efektivní data přednastaveného stínového efektu s aplikovaným děděním. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda je zadaný [PresetShadow](../../com.aspose.slides/presetshadow) roven aktuálnímu [PresetShadow](../../com.aspose.slides/presetshadow). |
| [hashCode()](#hashCode--) | Slouží jako hashovací funkce pro daný typ. |
### getDirection() {#getDirection--}
```
public final float getDirection()
```

Směr stínu. Čtení/Zápis  float .

**Vrací:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Směr stínu. Čtení/Zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```

Vzdálenost stínu. Čtení/Zápis  double .

**Vrací:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Vzdálenost stínu. Čtení/Zápis  double .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

Barva stínu. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public final int getPreset()
```

Předvolba. Čtení/Zápis [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Vrací:**
int
### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```

Předvolba. Čtení/Zápis [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```

Získá efektivní data přednastaveného stínového efektu s aplikovaným děděním.

**Vrací:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - A [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Verze. Pouze pro čtení long.

**Vrací:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Vrací rodiče IPresentationComponent. Pouze pro čtení [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Vrací:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Určuje, zda je zadaný [PresetShadow](../../com.aspose.slides/presetshadow) roven aktuálnímu [PresetShadow](../../com.aspose.slides/presetshadow).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | [PresetShadow](../../com.aspose.slides/presetshadow) k porovnání. |

**Vrací:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Slouží jako hashovací funkce pro daný typ.

**Vrací:**
int - A hash code for the current object.