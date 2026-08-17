---
title: PresetShadow
second_title: Aspose.Slides für Java API Referenz
description: Stellt einen voreingestellten Schatteneffekt dar.
type: docs
url: /de/com.aspose.slides/presetshadow/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Stellt einen voreingestellten Schatteneffekt dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDirection()](#getDirection--) | Richtung des Schattens. |
| [setDirection(float value)](#setDirection-float-) | Richtung des Schattens. |
| [getDistance()](#getDistance--) | Abstand des Schattens. |
| [setDistance(double value)](#setDistance-double-) | Abstand des Schattens. |
| [getShadowColor()](#getShadowColor--) | Farbe des Schattens. |
| [getPreset()](#getPreset--) | Voreinstellung. |
| [setPreset(int value)](#setPreset-int-) | Voreinstellung. |
| [getEffective()](#getEffective--) | Ruft die effektiven Daten des voreingestellten Schatteneffekts mit angewandter Vererbung ab. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene [PresetShadow](../../com.aspose.slides/presetshadow) gleich dem aktuellen [PresetShadow](../../com.aspose.slides/presetshadow) ist. |
| [hashCode()](#hashCode--) | Dient als Hash-Funktion für einen bestimmten Typ. |
### getDirection() {#getDirection--}
```
public final float getDirection()
```


Richtung des Schattens. Lese-/Schreibzugriff float .

**Rückgabe:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```


Richtung des Schattens. Lese-/Schreibzugriff float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```


Abstand des Schattens. Lese-/Schreibzugriff double .

**Rückgabe:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


Abstand des Schattens. Lese-/Schreibzugriff double .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```


Farbe des Schattens. Nur lesend [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public final int getPreset()
```


Voreinstellung. Lese-/Schreibzugriff [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Rückgabe:**
int
### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```


Voreinstellung. Lese-/Schreibzugriff [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```


Ruft die effektiven Daten des voreingestellten Schatteneffekts mit angewandter Vererbung ab.

**Rückgabe:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - Ein [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Gibt das Parent_Immediate-Objekt zurück. Nur lesend IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Version. Nur lesend long.

**Rückgabe:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Gibt das übergeordnete IPresentationComponent zurück. Nur lesend [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Rückgabe:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene [PresetShadow](../../com.aspose.slides/presetshadow) gleich dem aktuellen [PresetShadow](../../com.aspose.slides/presetshadow) ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das [PresetShadow](../../com.aspose.slides/presetshadow) zum Vergleich. |

**Rückgabe:**
boolean - true, wenn Objekte gleich sind; andernfalls false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als Hash-Funktion für einen bestimmten Typ.

**Rückgabe:**
int - Ein Hashcode für das aktuelle Objekt.