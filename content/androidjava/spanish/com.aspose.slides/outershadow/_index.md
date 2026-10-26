---
title: OuterShadow
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa un efecto de sombra externa.
type: docs
url: /es/com.aspose.slides/outershadow/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IOuterShadow](../../com.aspose.slides/ioutershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class OuterShadow implements IOuterShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Representa un efecto de sombra externa.
## Métodos

| Método | Descripción |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Radio de desenfoque, en puntos. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Radio de desenfoque, en puntos. |
| [getDirection()](#getDirection--) | Dirección de la sombra, en grados. |
| [setDirection(float value)](#setDirection-float-) | Dirección de la sombra, en grados. |
| [getDistance()](#getDistance--) | Distancia de la sombra al objeto, en puntos. |
| [setDistance(double value)](#setDistance-double-) | Distancia de la sombra al objeto, en puntos. |
| [getShadowColor()](#getShadowColor--) | Color de la sombra. |
| [getRectangleAlign()](#getRectangleAlign--) | Alineación del rectángulo. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Alineación del rectángulo. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Ángulo de sesgo horizontal, en grados. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Ángulo de sesgo horizontal, en grados. |
| [getSkewVertical()](#getSkewVertical--) | Ángulo de sesgo vertical, en grados. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Ángulo de sesgo vertical, en grados. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Indica si la sombra gira junto con la forma. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Indica si la sombra gira junto con la forma. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Factor de escala horizontal, en porcentaje del tamaño original. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Factor de escala horizontal, en porcentaje del tamaño original. |
| [getScaleVertical()](#getScaleVertical--) | Factor de escala vertical, en porcentaje del tamaño original. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Factor de escala vertical, en porcentaje del tamaño original. |
| [getEffective()](#getEffective--) | Obtiene los datos efectivos del efecto de sombra externa con la herencia aplicada. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el [OuterShadow](../../com.aspose.slides/outershadow) especificado es igual al [OuterShadow](../../com.aspose.slides/outershadow) actual. |
| [hashCode()](#hashCode--) | Sirve como función hash para un tipo particular. |

### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

Radio de desenfoque, en puntos. Valor predeterminado - 0 pt. Lectura/escritura double.

**Devuelve:**
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

Radio de desenfoque, en puntos. Valor predeterminado - 0 pt. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

Dirección de la sombra, en grados. Valor predeterminado - 0 � (left-to-right). Lectura/escritura float.

**Devuelve:**
float

### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Dirección de la sombra, en grados. Valor predeterminado - 0 � (left-to-right). Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

Distancia de la sombra al objeto, en puntos. Valor predeterminado - 0 pt. Lectura/escritura double.

**Devuelve:**
double

### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Distancia de la sombra al objeto, en puntos. Valor predeterminado - 0 pt. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

Color de la sombra. Valor predeterminado - negro automático (dependiente del tema). Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```

Alineación del rectángulo. Valor predeterminado - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Lectura/escritura [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Devuelve:**
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```

Alineación del rectángulo. Valor predeterminado - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Lectura/escritura [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```

Ángulo de sesgo horizontal, en grados. Valor predeterminado - 0 �. Lectura/escritura double.

**Devuelve:**
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```

Ángulo de sesgo horizontal, en grados. Valor predeterminado - 0 �. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```

Ángulo de sesgo vertical, en grados. Valor predeterminado - 0 �. Lectura/escritura double.

**Devuelve:**
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```

Ángulo de sesgo vertical, en grados. Valor predeterminado - 0 �. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```

Indica si la sombra gira junto con la forma. Valor predeterminado - true. Lectura/escritura boolean.

**Devuelve:**
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```

Indica si la sombra gira junto con la forma. Valor predeterminado - true. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```

Factor de escala horizontal, en porcentaje del tamaño original. El escalado negativo produce una inversión. Valor predeterminado - 100 %. Lectura/escritura double.

**Devuelve:**
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```

Factor de escala horizontal, en porcentaje del tamaño original. El escalado negativo produce una inversión. Valor predeterminado - 100 %. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```

Factor de escala vertical, en porcentaje del tamaño original. El escalado negativo produce una inversión. Valor predeterminado - 100 %. Lectura/escritura double.

**Devuelve:**
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```

Factor de escala vertical, en porcentaje del tamaño original. El escalado negativo produce una inversión. Valor predeterminado - 100 %. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final IOuterShadowEffectiveData getEffective()
```

Obtiene los datos efectivos del efecto de sombra externa con la herencia aplicada.

**Devuelve:**
[IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata) - Un [IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata).

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

Devuelve el IPresentationComponent padre. Solo lectura [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Devuelve:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina si el [OuterShadow](../../com.aspose.slides/outershadow) especificado es igual al [OuterShadow](../../com.aspose.slides/outershadow) actual.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El [OuterShadow](../../com.aspose.slides/outershadow) a comparar. |

**Devuelve:**
boolean - true si los objetos son iguales; de lo contrario, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Sirve como función hash para un tipo particular.

**Devuelve:**
int - Un código hash para el objeto actual.