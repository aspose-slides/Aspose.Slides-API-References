---
title: IPresetShadowEffectiveData
second_title: Aspose.Slides pro Java – referenční příručka API
description: Neměnný objekt, který představuje přednastavený efekt stínu.
type: docs
url: /cs/com.aspose.slides/ippresetshadoweffectivedata/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IPresetShadowEffectiveData extends IEffectEffectiveData
```

Neměnný objekt, který představuje efekt přednastaveného stínu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getDirection()](#getDirection--) | Směr stínu. |
| [getDistance()](#getDistance--) | Vzdálenost stínu. |
| [getShadowColor()](#getShadowColor--) | Barva stínu. |
| [getPreset()](#getPreset--) | Předvolba. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


Směr stínu. Pouze pro čtení float.

**Vrací:**
float
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


Vzdálenost stínu. Pouze pro čtení double.

**Vrací:**
double
### getShadowColor() {#getShadowColor--}
```
public abstract Color getShadowColor()
```


Barva stínu. Pouze pro čtení java.awt.Color.

**Vrací:**
java.awt.Color
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```


Předvolba. Pouze pro čtení [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Vrací:**
int