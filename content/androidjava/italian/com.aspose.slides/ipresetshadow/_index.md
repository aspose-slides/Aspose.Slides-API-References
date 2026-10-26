---
title: IPresetShadow
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un effetto di ombra predefinito.
type: docs
url: /it/com.aspose.slides/ippresetshadow/
---
**Tutte le Interfacce Implementate:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

Rappresenta un effetto di ombra predefinito.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDirection()](#getDirection--) | Direzione dell'ombra. |
| [setDirection(float value)](#setDirection-float-) | Direzione dell'ombra. |
| [getDistance()](#getDistance--) | Distanza dell'ombra. |
| [setDistance(double value)](#setDistance-double-) | Distanza dell'ombra. |
| [getShadowColor()](#getShadowColor--) | Colore dell'ombra. |
| [getPreset()](#getPreset--) | Predefinito. |
| [setPreset(int value)](#setPreset-int-) | Predefinito. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


Direzione dell'ombra. Lettura/scrittura float.

**Restituisce:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```


Direzione dell'ombra. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


Distanza dell'ombra. Lettura/scrittura double.

**Restituisce:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```


Distanza dell'ombra. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```


Colore dell'ombra. Sola lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```


Predefinito. Lettura/scrittura [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Restituisce:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```


Predefinito. Lettura/scrittura [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |