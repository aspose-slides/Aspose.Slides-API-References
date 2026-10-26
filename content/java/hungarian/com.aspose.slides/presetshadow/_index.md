---
title: PresetShadow
second_title: Aspose.Slides Java API hivatkozás
description: Egy előre definiált árnyékhatást ábrázol.
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

Egy előre definiált árnyékhatást ábrázol.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getDirection()](#getDirection--) | Az árnyék iránya. |
| [setDirection(float value)](#setDirection-float-) | Az árnyék iránya. |
| [getDistance()](#getDistance--) | Az árnyék távolsága. |
| [setDistance(double value)](#setDistance-double-) | Az árnyék távolsága. |
| [getShadowColor()](#getShadowColor--) | Az árnyék színe. |
| [getPreset()](#getPreset--) | Előre definiált érték. |
| [setPreset(int value)](#setPreset-int-) | Előre definiált érték. |
| [getEffective()](#getEffective--) | Lekéri a tényleges Preset Shadow hatásadatokat az öröklődés alkalmazásával. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Meghatározza, hogy a megadott [PresetShadow](../../com.aspose.slides/presetshadow) egyenlő-e a jelenlegi [PresetShadow](../../com.aspose.slides/presetshadow)-val. |
| [hashCode()](#hashCode--) | Hash-függvényként szolgál egy adott típushoz. |
### getDirection() {#getDirection--}
```
public final float getDirection()
```


Az árnyék iránya. Olvasás/írás  float .

**Visszatérési érték:**
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

**Visszatérési érték:**
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

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public final int getPreset()
```


Előre definiált érték. Olvasás/írás [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Visszatérési érték:**
int
### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```


Előre definiált érték. Olvasás/írás [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```


Lekéri a tényleges Preset Shadow hatásadatokat az öröklődés alkalmazásával.

**Visszatérési érték:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - Egy [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Visszatér a Parent_Immediate objektummal. Csak olvasható IDOMObject.

**Visszatérési érték:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Verzió. Csak olvasható long.

**Visszatérési érték:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Visszatér a szülő IPresentationComponent objektummal. Csak olvasható [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Visszatérési érték:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Meghatározza, hogy a megadott [PresetShadow](../../com.aspose.slides/presetshadow) egyenlő-e a jelenlegi [PresetShadow](../../com.aspose.slides/presetshadow)-val.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [PresetShadow](../../com.aspose.slides/presetshadow) a összehasonlításhoz. |

**Visszatérési érték:**
boolean - igaz, ha az objektumok egyenlőek; egyébként hamis.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash-függvényként szolgál egy adott típushoz.

**Visszatérési érték:**
int - Egy hash kód a jelenlegi objektumhoz.