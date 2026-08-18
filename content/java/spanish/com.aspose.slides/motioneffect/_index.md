---
title: MotionEffect
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa el comportamiento del efecto de movimiento.
type: docs
url: /es/com.aspose.slides/motioneffect/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**All Implemented Interfaces:**  
[com.aspose.slides.IMotionEffect](../../com.aspose.slides/imotioneffect)  
```
public class MotionEffect extends Behavior implements IMotionEffect
```

Representa el comportamiento del efecto de movimiento de efecto.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFrom()](#getFrom--) | Especifica una coordenada x/y desde la cual iniciar la animación (en porcentajes). |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | Especifica una coordenada x/y desde la cual iniciar la animación (en porcentajes). |
| [getTo()](#getTo--) | Especifica la ubicación objetivo para un efecto de movimiento de animación (en porcentajes). |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | Especifica la ubicación objetivo para un efecto de movimiento de animación (en porcentajes). |
| [getBy()](#getBy--) | Describe el valor de desplazamiento relativo para la animación (en porcentajes). |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | Describe el valor de desplazamiento relativo para la animación (en porcentajes). |
| [getRotationCenter()](#getRotationCenter--) | Describe el centro de rotación utilizado para girar una ruta de movimiento por un ángulo X. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | Describe el centro de rotación utilizado para girar una ruta de movimiento por un ángulo X. |
| [getOrigin()](#getOrigin--) | Especifica a qué se refiere el origen de la ruta de movimiento, como la disposición de la diapositiva o el elemento padre. |
| [setOrigin(int value)](#setOrigin-int-) | Especifica a qué se refiere el origen de la ruta de movimiento, como la disposición de la diapositiva o el elemento padre. |
| [getPath()](#getPath--) | Especifica la primitiva de ruta seguida de coordenadas para el movimiento de la animación. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Especifica la primitiva de ruta seguida de coordenadas para el movimiento de la animación. |
| [getPathEditMode()](#getPathEditMode--) | Especifica cómo se mueve la ruta de movimiento cuando se desplaza la forma. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Especifica cómo se mueve la ruta de movimiento cuando se desplaza la forma. |
| [getAngle()](#getAngle--) | Describe el ángulo relativo de la ruta de movimiento. |
| [setAngle(float value)](#setAngle-float-) | Describe el ángulo relativo de la ruta de movimiento. |
### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```

### getFrom() {#getFrom--}
```
public final Point2D.Float getFrom()
```

Especifica una coordenada x/y desde la cual iniciar la animación (en porcentajes). Lectura/escritura java.awt.geom.Point2D.Float.

**Devuelve:**
java.awt.geom.Point2D.Float
### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public final void setFrom(Point2D.Float value)
```

Especifica una coordenada x/y desde la cual iniciar la animación (en porcentajes). Lectura/escritura java.awt.geom.Point2D.Float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public final Point2D.Float getTo()
```

Especifica la ubicación objetivo para un efecto de movimiento de animación (en porcentajes). Lectura/escritura java.awt.geom.Point2D.Float.

**Devuelve:**
java.awt.geom.Point2D.Float
### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public final void setTo(Point2D.Float value)
```

Especifica la ubicación objetivo para un efecto de movimiento de animación (en porcentajes). Lectura/escritura java.awt.geom.Point2D.Float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public final Point2D.Float getBy()
```

Describe el valor de desplazamiento relativo para la animación (en porcentajes). Lectura/escritura java.awt.geom.Point2D.Float.

**Devuelve:**
java.awt.geom.Point2D.Float
### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public final void setBy(Point2D.Float value)
```

Describe el valor de desplazamiento relativo para la animación (en porcentajes). Lectura/escritura java.awt.geom.Point2D.Float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public final Point2D.Float getRotationCenter()
```

Describe el centro de rotación utilizado para girar una ruta de movimiento por un ángulo X. Lectura/escritura java.awt.geom.Point2D.Float.

**Devuelve:**
java.awt.geom.Point2D.Float
### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public final void setRotationCenter(Point2D.Float value)
```

Describe el centro de rotación utilizado para girar una ruta de movimiento por un ángulo X. Lectura/escritura java.awt.geom.Point2D.Float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```

Especifica a qué se refiere el origen de la ruta de movimiento, como la disposición de la diapositiva o el elemento padre. Lectura/escritura [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Devuelve:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```

Especifica a qué se refiere el origen de la ruta de movimiento, como la disposición de la diapositiva o el elemento padre. Lectura/escritura [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```

Especifica la primitiva de ruta seguida de coordenadas para el movimiento de la animación. Lectura/escritura [IMotionPath](../../com.aspose.slides/imotionpath).

**Devuelve:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```

Especifica la primitiva de ruta seguida de coordenadas para el movimiento de la animación. Lectura/escritura [IMotionPath](../../com.aspose.slides/imotionpath).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```

Especifica cómo se mueve la ruta de movimiento cuando se desplaza la forma. Lectura/escritura [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Devuelve:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```

Especifica cómo se mueve la ruta de movimiento cuando se desplaza la forma. Lectura/escritura [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```

Describe el ángulo relativo de la ruta de movimiento. Lectura/escritura float.

**Devuelve:**
float
### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```

Describe el ángulo relativo de la ruta de movimiento. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |