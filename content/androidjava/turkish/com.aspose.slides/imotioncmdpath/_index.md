---
title: IMotionCmdPath
second_title: Aspose.Slides Android için Java API Referansı
description: Bir yolun bir komutunu temsil eder.
type: docs
url: /tr/com.aspose.slides/imotioncmdpath/
---```
public interface IMotionCmdPath
```

Bir yolun bir komutunu temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getPoints()](#getPoints--) | Komutun noktalarını belirtir. |
| [setPoints(PointF[] value)](#setPoints-android.graphics.PointF---) | Komutun noktalarını belirtir. |
| [getCommandType()](#getCommandType--) | Komut tipini belirtir. |
| [setCommandType(int value)](#setCommandType-int-) | Komut tipini belirtir. |
| [isRelative()](#isRelative--) | Komut koordinatlarının göreli olup olmadığını belirler. |
| [setRelative(boolean value)](#setRelative-boolean-) | Komut koordinatlarının göreli olup olmadığını belirler. |
| [getPointsType()](#getPointsType--) | Komut noktaları tipini belirtir Okunur/Yazılabilir [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
| [setPointsType(int value)](#setPointsType-int-) | Komut noktaları tipini belirtir Okunur/Yazılabilir [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```


Komutun noktalarını belirtir. Okunur/Yazılabilir android.graphics.PointF[].

**Döndürür:**
android.graphics.PointF[]
### setPoints(PointF[] value) {#setPoints-android.graphics.PointF---}
```
public abstract void setPoints(PointF[] value)
```


Komutun noktalarını belirtir. Okunur/Yazılabilir android.graphics.PointF[].

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | android.graphics.PointF[] |  |

### getCommandType() {#getCommandType--}
```
public abstract int getCommandType()
```


Komut tipini belirtir. Okunur/Yazılabilir [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Döndürür:**
int
### setCommandType(int value) {#setCommandType-int-}
```
public abstract void setCommandType(int value)
```


Komut tipini belirtir. Okunur/Yazılabilir [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### isRelative() {#isRelative--}
```
public abstract boolean isRelative()
```


Komut koordinatlarının göreli olup olmadığını belirler. Okunur/Yazılabilir boolean.

**Döndürür:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public abstract void setRelative(boolean value)
```


Komut koordinatlarının göreli olup olmadığını belirler. Okunur/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```


Komut noktaları tipini belirtir Okunur/Yazılabilir [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Döndürür:**
int
### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```


Komut noktaları tipini belirtir Okunur/Yazılabilir [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |