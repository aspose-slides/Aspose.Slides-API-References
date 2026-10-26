---
title: IMotionCmdPath
second_title: Aspose.Slides için Java API Referansı
description: Bir yolun bir komutunu temsil eder.
type: docs
url: /tr/com.aspose.slides/imotioncmdpath/
---```
public interface IMotionCmdPath
```

Bir yolun bir komutunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPoints()](#getPoints--) | Komutun noktalarını belirtir. |
| [setPoints(Point2D.Float[] value)](#setPoints-java.awt.geom.Point2D.Float---) | Komutun noktalarını belirtir. |
| [getCommandType()](#getCommandType--) | Komut tipini belirtir. |
| [setCommandType(int value)](#setCommandType-int-) | Komut tipini belirtir. |
| [isRelative()](#isRelative--) | Komut koordinatlarının göreceli olup olmadığını belirler. |
| [setRelative(boolean value)](#setRelative-boolean-) | Komut koordinatlarının göreceli olup olmadığını belirler. |
| [getPointsType()](#getPointsType--) | Komut noktalarının tipini belirtir Okunur/Yazılır [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
| [setPointsType(int value)](#setPointsType-int-) | Komut noktalarının tipini belirtir Okunur/Yazılır [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```


Komutun noktalarını belirtir. Okunur/Yazılır java.awt.geom.Point2D.Float[].

**Döndürür:**
java.awt.geom.Point2D.Float[]
### setPoints(Point2D.Float[] value) {#setPoints-java.awt.geom.Point2D.Float---}
```
public abstract void setPoints(Point2D.Float[] value)
```


Komutun noktalarını belirtir. Okunur/Yazılır java.awt.geom.Point2D.Float[].

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float[] |  |

### getCommandType() {#getCommandType--}
```
public abstract int getCommandType()
```


Komut tipini belirtir. Okunur/Yazılır [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Döndürür:**
int
### setCommandType(int value) {#setCommandType-int-}
```
public abstract void setCommandType(int value)
```


Komut tipini belirtir. Okunur/Yazılır [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### isRelative() {#isRelative--}
```
public abstract boolean isRelative()
```


Komut koordinatlarının göreceli olup olmadığını belirler. Okunur/Yazılır boolean.

**Döndürür:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public abstract void setRelative(boolean value)
```


Komut koordinatlarının göreceli olup olmadığını belirler. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```


Komut noktalarının tipini belirtir Okunur/Yazılır [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Döndürür:**
int
### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```


Komut noktalarının tipini belirtir Okunur/Yazılır [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
