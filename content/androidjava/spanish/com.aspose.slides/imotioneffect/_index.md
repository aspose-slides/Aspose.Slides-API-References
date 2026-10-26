---
title: IMotionEffect
second_title: Aspose.Slides para Android vía Referencia de API Java
description: Representa el comportamiento del efecto de movimiento.
type: docs
url: /es/com.aspose.slides/imotioneffect/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

Representa el comportamiento del efecto de movimiento.

## Métodos

| Method | Description |
| --- | --- |
| [getFrom()](#getFrom--) | Especifica una coordenada x/y desde la cual iniciar la animación (en porcentajes). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Especifica una coordenada x/y desde la cual iniciar la animación (en porcentajes). |
| [getTo()](#getTo--) | Especifica la ubicación objetivo para un efecto de movimiento de animación (en porcentajes). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Especifica la ubicación objetivo para un efecto de movimiento de animación (en porcentajes). |
| [getBy()](#getBy--) | Describe el valor de desplazamiento relativo para la animación (en porcentajes). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Describe el valor de desplazamiento relativo para la animación (en porcentajes). |
| [getRotationCenter()](#getRotationCenter--) | Describe el centro de rotación utilizado para girar una ruta de movimiento por un ángulo X. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Describe el centro de rotación utilizado para girar una ruta de movimiento por un ángulo X. |
| [getOrigin()](#getOrigin--) | Especifica cuál es el origen de la ruta de movimiento en relación a, por ejemplo, el diseño de la diapositiva o el elemento padre. |
| [setOrigin(int value)](#setOrigin-int-) | Especifica cuál es el origen de la ruta de movimiento en relación a, por ejemplo, el diseño de la diapositiva o el elemento padre. |
| [getPath()](#getPath--) | Especifica el elemento primitivo de la ruta seguido de coordenadas para el movimiento de la animación. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Especifica el elemento primitivo de la ruta seguido de coordenadas para el movimiento de la animación. |
| [getPathEditMode()](#getPathEditMode--) | Especifica cómo se mueve la ruta de movimiento cuando se mueve la forma. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Especifica cómo se mueve la ruta de movimiento cuando se mueve la forma. |
| [getAngle()](#getAngle--) | Describe el ángulo relativo de la ruta de movimiento. |
| [setAngle(float value)](#setAngle-float-) | Describe el ángulo relativo de la ruta de movimiento. |

### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

Especifica una coordenada x/y desde la cual iniciar la animación (en porcentajes). Lectura/escritura android.graphics.PointF.

**Devuelve:**
android.graphics.PointF

### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

Especifica una coordenada x/y desde la cual iniciar la animación (en porcentajes). Lectura/escritura android.graphics.PointF.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public abstract PointF getTo()
```

Especifica la ubicación objetivo para un efecto de movimiento de animación (en porcentajes). Lectura/escritura android.graphics.PointF.

**Devuelve:**
android.graphics.PointF

### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

Especifica la ubicación objetivo para un efecto de movimiento de animación (en porcentajes). Lectura/escritura android.graphics.PointF.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public abstract PointF getBy()
```

Describe el valor de desplazamiento relativo para la animación (en porcentajes). Lectura/escritura android.graphics.PointF.

**Devuelve:**
android.graphics.PointF

### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

Describe el valor de desplazamiento relativo para la animación (en porcentajes). Lectura/escritura android.graphics.PointF.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract PointF getRotationCenter()
```

Describe el centro de rotación utilizado para girar una ruta de movimiento por un ángulo X. Lectura/escritura android.graphics.PointF.

**Devuelve:**
android.graphics.PointF

### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public abstract void setRotationCenter(PointF value)
```

Describe el centro de rotación utilizado para girar una ruta de movimiento por un ángulo X. Lectura/escritura android.graphics.PointF.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Especifica cuál es el origen de la ruta de movimiento en relación a, por ejemplo, el diseño de la diapositiva o el elemento padre. Lectura/escritura [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Devuelve:**
int

### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Especifica cuál es el origen de la ruta de movimiento en relación a, por ejemplo, el diseño de la diapositiva o el elemento padre. Lectura/escritura [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Especifica el elemento primitivo de la ruta seguido de coordenadas para el movimiento de la animación. Lectura/escritura [IMotionPath](../../com.aspose.slides/imotionpath).

**Devuelve:**
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Especifica el elemento primitivo de la ruta seguido de coordenadas para el movimiento de la animación. Lectura/escritura [IMotionPath](../../com.aspose.slides/imotionpath).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

Especifica cómo se mueve la ruta de movimiento cuando se mueve la forma. Lectura/escritura [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Devuelve:**
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

Especifica cómo se mueve la ruta de movimiento cuando se mueve la forma. Lectura/escritura [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

Describe el ángulo relativo de la ruta de movimiento. Lectura/escritura float.

**Devuelve:**
float

### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

Describe el ángulo relativo de la ruta de movimiento. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |