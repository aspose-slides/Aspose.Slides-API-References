---
title: PresetShadow
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt een vooraf ingesteld schaduweffect.
type: docs
url: /nl/com.aspose.slides/presetshadow/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Vertegenwoordigt een vooraf ingesteld schaduweffect.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getDirection()](#getDirection--) | Richting van de schaduw. |
| [setDirection(float value)](#setDirection-float-) | Richting van de schaduw. |
| [getDistance()](#getDistance--) | Afstand van de schaduw. |
| [setDistance(double value)](#setDistance-double-) | Afstand van de schaduw. |
| [getShadowColor()](#getShadowColor--) | Kleur van de schaduw. |
| [getPreset()](#getPreset--) | Voorinstelling. |
| [setPreset(int value)](#setPreset-int-) | Voorinstelling. |
| [getEffective()](#getEffective--) | Haalt effectieve Preset Shadow effectgegevens op met de erfenis toegepast. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of de opgegeven [PresetShadow](../../com.aspose.slides/presetshadow) gelijk is aan de huidige [PresetShadow](../../com.aspose.slides/presetshadow). |
| [hashCode()](#hashCode--) | Dient als een hashfunctie voor een bepaald type. |
### getDirection() {#getDirection--}
```
public final float getDirection()
```

Richting van de schaduw. Lezen/schrijven  float .

**Retour:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Richting van de schaduw. Lezen/schrijven  float .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

Afstand van de schaduw. Lezen/schrijven  double .

**Retour:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Afstand van de schaduw. Lezen/schrijven  double .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

Kleur van de schaduw. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public final int getPreset()
```

Voorinstelling. Lezen/schrijven [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Retour:**
int
### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```

Voorinstelling. Lezen/schrijven [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```

Haalt effectieve Preset Shadow effectgegevens op met de erfenis toegepast.

**Retour:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - Een [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert Parent_Immediate object. Alleen-lezen IDOMObject.

**Retour:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Versie. Alleen-lezen long.

**Retour:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Retourneert parent IPresentationComponent. Alleen-lezen [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Retour:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bepaalt of de opgegeven [PresetShadow](../../com.aspose.slides/presetshadow) gelijk is aan de huidige [PresetShadow](../../com.aspose.slides/presetshadow).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | De [PresetShadow](../../com.aspose.slides/presetshadow) om te vergelijken. |

**Retour:**
boolean - true als objecten gelijk zijn; anders false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als een hashfunctie voor een bepaald type.

**Retour:**
int - Een hashcode voor het huidige object.