---
title: IMotionCmdPath
second_title: Aspose.Slides for Java API Reference
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
| [setPoints(Point2D.Float[] value)](#setPoints-java.awt.geom.Point2D.Float---) | Specifica i punti del comando. |
| [getCommandType()](#getCommandType--) | Specifica il tipo di comando. |
| [setCommandType(int value)](#setCommandType-int-) | Specifica il tipo di comando. |
| [isRelative()](#isRelative--) | Determina se le coordinate del comando sono relative o meno. |
| [setRelative(boolean value)](#setRelative-boolean-) | Determina se le coordinate del comando sono relative o meno. |
| [getPointsType()](#getPointsType--) | Specifica il tipo di punti del comando Lettura/Scrittura [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
| [setPointsType(int value)](#setPointsType-int-) | Specifica il tipo di punti del comando Lettura/Scrittura [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |

### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```

Specifica i punti del comando. Lettura/Scrittura java.awt.geom.Point2D.Float[].

**Restituisce:**
java.awt.geom.Point2D.Float[]

### setPoints(Point2D.Float[] value) {#setPoints-java.awt.geom.Point2D.Float---}
```
public abstract void setPoints(Point2D.Float[] value)
```

Specifica i punti del comando. Lettura/Scrittura java.awt.geom.Point2D.Float[].

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float[] |  |

### getCommandType() {#getCommandType--}
```
public abstract int getCommandType()
```

Specifica il tipo di comando. Lettura/Scrittura [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Restituisce:**
int

### setCommandType(int value) {#setCommandType-int-}
```
public abstract void setCommandType(int value)
```

Specifica il tipo di comando. Lettura/Scrittura [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### isRelative() {#isRelative--}
```
public abstract boolean isRelative()
```

Determina se le coordinate del comando sono relative o non. Lettura/Scrittura boolean.

**Restituisce:**
boolean

### setRelative(boolean value) {#setRelative-boolean-}
```
public abstract void setRelative(boolean value)
```

Determina se le coordinate del comando sono relative o non. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```

Specifica il tipo di punti del comando Lettura/Scrittura [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Restituisce:**
int

### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```

Specifica il tipo di punti del comando Lettura/Scrittura [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |