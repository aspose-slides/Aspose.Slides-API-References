---
title: MotionEffect
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa el comportamiento del efecto de movimiento.
type: docs
url: /es/com.aspose.slides/motioneffect/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**Todas las interfaces implementadas:**
[com.aspose.slides.IMotionEffect](../../com.aspose.slides/imotioneffect)
```
public class MotionEffect extends Behavior implements IMotionEffect
```

Representa el comportamiento del efecto de movimiento del efecto.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [getFrom()](#getFrom--) | Especifica una coordenada x/y desde la cual iniciar la animación (en porcentajes). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Especifica una coordenada x/y desde la cual iniciar la animación (en porcentajes). |
| [getTo()](#getTo--) | Especifica la ubicación objetivo para un efecto de movimiento de animación (en porcentajes). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Especifica la ubicación objetivo para un efecto de movimiento de animación (en porcentajes). |
| [getBy()](#getBy--) | Describe el valor de desplazamiento relativo para la animación (en porcentajes). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Describe el valor de desplazamiento relativo para la animación (en porcentajes). |
| [getRotationCenter()](#getRotationCenter--) | Describe el centro de rotación usado para girar una trayectoria de movimiento por ángulo X. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Describe el centro de rotación usado para girar una trayectoria de movimiento por ángulo X. |
| [getOrigin()](#getOrigin--) | Especifica cuál es el origen de la trayectoria de movimiento relativo a, por ejemplo, el diseño de la diapositiva o el elemento padre. |
| [setOrigin(int value)](#setOrigin-int-) | Especifica cuál es el origen de la trayectoria de movimiento relativo a, por ejemplo, el diseño de la diapositiva o el elemento padre. |
| [getPath()](#getPath--) | Especifica la primitiva de ruta seguida de coordenadas para el movimiento de la animación. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Especifica la primitiva de ruta seguida de coordenadas para el movimiento de la animación. |
| [getPathEditMode()](#getPathEditMode--) | Especifica cómo se mueve la trayectoria de movimiento cuando se mueve la forma. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Especifica cómo se mueve la trayectoria de movimiento cuando se mueve la forma. |
| [getAngle()](#getAngle--) | Describe el ángulo relativo de la trayectoria de movimiento. |
| [setAngle(float value)](#setAngle-float-) | Describe el ángulo relativo de la trayectoria de movimiento. |

### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```

### getFrom() {#getFrom--}
```
public final PointF getFrom()
```

Especifica una coordenada x/y desde la cual iniciar la animación (en porcentajes). Lectura/escritura android.graphics.PointF.

**Devuelve:**
android.graphics.PointF

### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public final void setFrom(PointF value)
```

Especifica una coordenada x/y desde la cual iniciar la animación (en porcentajes). Lectura/escritura android.graphics.PointF.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public final PointF getTo()
```

Especifica la ubicación objetivo para un efecto de movimiento de animación (en porcentajes). Lectura/escritura android.graphics.PointF.

**Devuelve:**
android.graphics.PointF

### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public final void setTo(PointF value)
```

Especifica la ubicación objetivo para un efecto de movimiento de animación (en porcentajes). Lectura/escritura android.graphics.PointF.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public final PointF getBy()
```

Describe el valor de desplazamiento relativo para la animación (en porcentajes). Lectura/escritura android.graphics.PointF.

**Devuelve:**
android.graphics.PointF

### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public final void setBy(PointF value)
```

Describe el valor de desplazamiento relativo para la animación (en porcentajes). Lectura/escritura android.graphics.PointF.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public final PointF getRotationCenter()
```

Describe el centro de rotación usado para girar una trayectoria de movimiento por ángulo X. Lectura/escritura android.graphics.PointF.

**Devuelve:**
android.graphics.PointF

### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public final void setRotationCenter(PointF value)
```

Describe el centro de rotación usado para girar una trayectoria de movimiento por ángulo X. Lectura/escritura android.graphics.PointF.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```

Especifica cuál es el origen de la trayectoria de movimiento relativo a, por ejemplo, el diseño de la diapositiva o el elemento padre. Lectura/escritura [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Devuelve:**
int

### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```

Especifica cuál es el origen de la trayectoria de movimiento relativo a, por ejemplo, el diseño de la diapositiva o el elemento padre. Lectura/escritura [MotionOriginType](../../com.aspose.slides/motionorigintype).

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

Especifica cómo se mueve la trayectoria de movimiento cuando se mueve la forma. Lectura/escritura [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Devuelve:**
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```

Especifica cómo se mueve la trayectoria de movimiento cuando se mueve la forma. Lectura/escritura [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```

Describe el ángulo relativo de la trayectoria de movimiento. Lectura/escritura float.

**Devuelve:**
float

### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```

Describe el ángulo relativo de la trayectoria de movimiento. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |