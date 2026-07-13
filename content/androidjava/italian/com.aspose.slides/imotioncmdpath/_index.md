---
title: IMotionCmdPath
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta un comando di un percorso.
type: docs
url: /it/com.aspose.slides/imotioncmdpath/
---```
public interface IMotionCmdPath
```

Rappresenta un comando di un percorso.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPoints()](#getPoints--) | Specifica i punti del comando. |
| [setPoints(PointF[] value)](#setPoints-android.graphics.PointF---) | Specifica i punti del comando. |
| [getCommandType()](#getCommandType--) | Specifica il tipo di comando. |
| [setCommandType(int value)](#setCommandType-int-) | Specifica il tipo di comando. |
| [isRelative()](#isRelative--) | Determina se le coordinate del comando sono relative o no. |
| [setRelative(boolean value)](#setRelative-boolean-) | Determina se le coordinate del comando sono relative o no. |
| [getPointsType()](#getPointsType--) | Specifica il tipo di punti del comando Lettura/Scrittura [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
| [setPointsType(int value)](#setPointsType-int-) | Specifica il tipo di punti del comando Lettura/Scrittura [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |

### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```

Specifică i punti del comando. Lettura/Scrittura android.graphics.PointF[].

**Restituisce:**
android.graphics.PointF[]

### setPoints(PointF[] value) {#setPoints-android.graphics.PointF---}
```
public abstract void setPoints(PointF[] value)
```

Specifică i punti del comando. Lettura/Scrittura android.graphics.PointF[].

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | android.graphics.PointF[] |  |

### getCommandType() {#getCommandType--}
```
public abstract int getCommandType()
```

Specifică il tipo di comando. Lettura/Scrittura [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Restituisce:**
int

### setCommandType(int value) {#setCommandType-int-}
```
public abstract void setCommandType(int value)
```

Specifică il tipo di comando. Lettura/Scrittura [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### isRelative() {#isRelative--}
```
public abstract boolean isRelative()
```

Determina se le coordinate del comando sono relative o no. Lettura/Scrittura boolean.

**Restituisce:**
boolean

### setRelative(boolean value) {#setRelative-boolean-}
```
public abstract void setRelative(boolean value)
```

Determina se le coordinate del comando sono relative o no. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```

Specifică il tipo di punti del comando Lettura/Scrittura [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Restituisce:**
int

### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```

Specifică il tipo di punti del comando Lettura/Scrittura [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |