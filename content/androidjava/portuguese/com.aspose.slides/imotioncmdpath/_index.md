---
title: IMotionCmdPath
second_title: Aspose.Slides for Android via Java API Reference
description: Represent one command of a path.
type: docs
url: /pt/com.aspose.slides/imotioncmdpath/
---```
public interface IMotionCmdPath
```

Representa um comando de um caminho.
## Métodos

| Método | Descrição |
| --- | --- |
| [getPoints()](#getPoints--) | Especifica os pontos do comando. |
| [setPoints(PointF[] value)](#setPoints-android.graphics.PointF---) | Especifica os pontos do comando. |
| [getCommandType()](#getCommandType--) | Especifica o tipo do comando. |
| [setCommandType(int value)](#setCommandType-int-) | Especifica o tipo do comando. |
| [isRelative()](#isRelative--) | Determina se as coordenadas do comando são relativas ou não. |
| [setRelative(boolean value)](#setRelative-boolean-) | Determina se as coordenadas do comando são relativas ou não. |
| [getPointsType()](#getPointsType--) | Especifica o tipo de pontos do comando Leitura/gravação [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
| [setPointsType(int value)](#setPointsType-int-) | Especifica o tipo de pontos do comando Leitura/gravação [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```

Especifica os pontos do comando. Leitura/gravação android.graphics.PointF[].

**Retorna:**
android.graphics.PointF[]
### setPoints(PointF[] value) {#setPoints-android.graphics.PointF---}
```
public abstract void setPoints(PointF[] value)
```

Especifica os pontos do comando. Leitura/gravação android.graphics.PointF[].

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | android.graphics.PointF[] |  |

### getCommandType() {#getCommandType--}
```
public abstract int getCommandType()
```

Especifica o tipo do comando. Leitura/gravação [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Retorna:**
int
### setCommandType(int value) {#setCommandType-int-}
```
public abstract void setCommandType(int value)
```

Especifica o tipo do comando. Leitura/gravação [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### isRelative() {#isRelative--}
```
public abstract boolean isRelative()
```

Determina se as coordenadas do comando são relativas ou não. Leitura/gravação boolean.

**Retorna:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public abstract void setRelative(boolean value)
```

Determina se as coordenadas do comando são relativas ou não. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```

Especifica o tipo de pontos do comando Leitura/gravação [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Retorna:**
int
### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```

Especifica o tipo de pontos do comando Leitura/gravação [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |