---
title: IPresetShadow
second_title: Referencia de API de Aspose.Slides para Java
description: Representa un efecto de sombra predefinido.
type: docs
url: /es/com.aspose.slides/ipresetshadow/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

Representa un efecto de sombra predefinido.
## Métodos

| Método | Descripción |
| --- | --- |
| [getDirection()](#getDirection--) | Dirección de la sombra. |
| [setDirection(float value)](#setDirection-float-) | Dirección de la sombra. |
| [getDistance()](#getDistance--) | Distancia de la sombra. |
| [setDistance(double value)](#setDistance-double-) | Distancia de la sombra. |
| [getShadowColor()](#getShadowColor--) | Color de la sombra. |
| [getPreset()](#getPreset--) | Preajuste. |
| [setPreset(int value)](#setPreset-int-) | Preajuste. |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Dirección de la sombra. Lectura/escritura float.

**Devuelve:**
float

### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Dirección de la sombra. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Distancia de la sombra. Lectura/escritura double.

**Devuelve:**
double

### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Distancia de la sombra. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Color de la sombra. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

Preajuste. Lectura/escritura [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Devuelve:**
int

### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```

Preajuste. Lectura/escritura [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |