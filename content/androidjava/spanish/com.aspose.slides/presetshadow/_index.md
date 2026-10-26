---
title: PresetShadow
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa un efecto de sombra predefinido.
type: docs
url: /es/com.aspose.slides/presetshadow/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
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
| [getPreset()](#getPreset--) | Predefinido. |
| [setPreset(int value)](#setPreset-int-) | Predefinido. |
| [getEffective()](#getEffective--) | Obtiene los datos efectivos del efecto de sombra predefinido con la herencia aplicada. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el [PresetShadow](../../com.aspose.slides/presetshadow) especificado es igual al [PresetShadow](../../com.aspose.slides/presetshadow) actual. |
| [hashCode()](#hashCode--) | Sirve como función hash para un tipo en particular. |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

Dirección de la sombra. Lectura/escritura  float .

**Devuelve:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Dirección de la sombra. Lectura/escritura  float .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

Distancia de la sombra. Lectura/escritura  double .

**Devuelve:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Distancia de la sombra. Lectura/escritura  double .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

Color de la sombra. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public final int getPreset()
```

Predefinido. Lectura/escritura [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Devuelve:**
int
### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```

Predefinido. Lectura/escritura [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```

Obtiene los datos efectivos del efecto de sombra predefinido con la herencia aplicada.

**Devuelve:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - Un [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Versión. Solo lectura long.

**Devuelve:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Devuelve el padre IPresentationComponent. Solo lectura [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Devuelve:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina si el [PresetShadow](../../com.aspose.slides/presetshadow) especificado es igual al [PresetShadow](../../com.aspose.slides/presetshadow) actual.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El [PresetShadow](../../com.aspose.slides/presetshadow) a comparar. |

**Devuelve:**
boolean - true si los objetos son iguales; de lo contrario, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Sirve como función hash para un tipo en particular.

**Devuelve:**
int - Un código hash para el objeto actual.