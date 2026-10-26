---
title: IMotionCmdPath
second_title: Aspose.Slides for Android via Java API Reference
description: Representa un comando de una ruta.
type: docs
url: /es/com.aspose.slides/imotioncmdpath/
---```
public interface IMotionCmdPath
```

Representa un comando de una ruta.
## Métodos

| Method | Description |
| --- | --- |
| [getPoints()](#getPoints--) | Especifica los puntos del comando. |
| [setPoints(PointF[] value)](#setPoints-android.graphics.PointF---) | Especifica los puntos del comando. |
| [getCommandType()](#getCommandType--) | Especifica el tipo de comando. |
| [setCommandType(int value)](#setCommandType-int-) | Especifica el tipo de comando. |
| [isRelative()](#isRelative--) | Determina si las coordenadas del comando son relativas o no. |
| [setRelative(boolean value)](#setRelative-boolean-) | Determina si las coordenadas del comando son relativas o no. |
| [getPointsType()](#getPointsType--) | Especifica el tipo de puntos del comando Lectura/escritura [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
| [setPointsType(int value)](#setPointsType-int-) | Especifica el tipo de puntos del comando Lectura/escritura [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```


Especifica los puntos del comando. Lectura/escritura android.graphics.PointF[].

**Devuelve:**
android.graphics.PointF[]
### setPoints(PointF[] value) {#setPoints-android.graphics.PointF---}
```
public abstract void setPoints(PointF[] value)
```


Especifica los puntos del comando. Lectura/escritura android.graphics.PointF[].

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | android.graphics.PointF[] |  |

### getCommandType() {#getCommandType--}
```
public abstract int getCommandType()
```


Especifica el tipo de comando. Lectura/escritura [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Devuelve:**
int
### setCommandType(int value) {#setCommandType-int-}
```
public abstract void setCommandType(int value)
```


Especifica el tipo de comando. Lectura/escritura [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### isRelative() {#isRelative--}
```
public abstract boolean isRelative()
```


Determina si las coordenadas del comando son relativas o no. Lectura/escritura boolean.

**Devuelve:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public abstract void setRelative(boolean value)
```


Determina si las coordenadas del comando son relativas o no. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```


Especifica el tipo de puntos del comando Lectura/escritura [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Devuelve:**
int
### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```


Especifica el tipo de puntos del comando Lectura/escritura [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |