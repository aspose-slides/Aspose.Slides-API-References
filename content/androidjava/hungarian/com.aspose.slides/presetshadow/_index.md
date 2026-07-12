---
title: PresetShadow
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Egy Preset Shadow effektust képvisel.
type: docs
url: /hu/com.aspose.slides/presetshadow/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

A Preset Shadow effektust képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getDirection()](#getDirection--) | Az árnyék iránya. |
| [setDirection(float value)](#setDirection-float-) | Az árnyék iránya. |
| [getDistance()](#getDistance--) | Az árnyék távolsága. |
| [setDistance(double value)](#setDistance-double-) | Az árnyék távolsága. |
| [getShadowColor()](#getShadowColor--) | Az árnyék színe. |
| [getPreset()](#getPreset--) | Előre beállított. |
| [setPreset(int value)](#setPreset-int-) | Előre beállított. |
| [getEffective()](#getEffective--) | Az öröklést alkalmazva lekéri a hatékony Preset Shadow effektus adatokat. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [PresetShadow](../../com.aspose.slides/presetshadow) egyenlő-e a jelenlegi [PresetShadow](../../com.aspose.slides/presetshadow) példánnyal. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |
### getDirection() {#getDirection--}
```
public final float getDirection()
```


Az árnyék iránya. Olvasás/írás  float .

**Visszatér:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```


Az árnyék iránya. Olvasás/írás  float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```


Az árnyék távolsága. Olvasás/írás  double .

**Visszatér:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


Az árnyék távolsága. Olvasás/írás  double .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```


Az árnyék színe. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public final int getPreset()
```


Előre beállított. Olvasás/írás [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Visszatér:**
int
### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```


Előre beállított. Olvasás/írás [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```


Az öröklést alkalmazva lekéri a hatékony Preset Shadow effektus adatokat.

**Visszatér:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - A [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Visszatér a Parent_Immediate objektummal. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Verzió. Csak olvasható long.

**Visszatér:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Visszatér a szülő IPresentationComponent objektummal. Csak olvasható [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Visszatér:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Megállapítja, hogy a megadott [PresetShadow](../../com.aspose.slides/presetshadow) egyenlő-e a jelenlegi [PresetShadow](../../com.aspose.slides/presetshadow) példánnyal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | Az [PresetShadow](../../com.aspose.slides/presetshadow) összehasonlításhoz. |

**Visszatér:**
boolean - igaz, ha az objektumok egyenlőek; különben hamis.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash függvényként szolgál egy adott típushoz.

**Visszatér:**
int - A jelenlegi objektum hash kódja.