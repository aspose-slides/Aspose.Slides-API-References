---
title: IMotionCmdPath
second_title: Aspose.Slides for Android Java API referencia
description: Egy útvonal egy parancsát képviseli.
type: docs
url: /hu/com.aspose.slides/imotioncmdpath/
---```
public interface IMotionCmdPath
```

Egy útvonal egy parancsát képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getPoints()](#getPoints--) | Meghatározza a parancs pontjait. |
| [setPoints(PointF[] value)](#setPoints-android.graphics.PointF---) | Meghatározza a parancs pontjait. |
| [getCommandType()](#getCommandType--) | Meghatározza a parancs típusát. |
| [setCommandType(int value)](#setCommandType-int-) | Meghatározza a parancs típusát. |
| [isRelative()](#isRelative--) | Meghatározza, hogy a parancs koordinátái relatívak-e vagy sem. |
| [setRelative(boolean value)](#setRelative-boolean-) | Meghatározza, hogy a parancs koordinátái relatívak-e vagy sem. |
| [getPointsType()](#getPointsType--) | Meghatározza a parancs pontjainak típusát Read/write [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
| [setPointsType(int value)](#setPointsType-int-) | Meghatározza a parancs pontjainak típusát Read/write [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```

Meghatározza a parancs pontjait. Read/write android.graphics.PointF[].

**Visszatér:**  
android.graphics.PointF[]
### setPoints(PointF[] value) {#setPoints-android.graphics.PointF---}
```
public abstract void setPoints(PointF[] value)
```

Meghatározza a parancs pontjait. Read/write android.graphics.PointF[].

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | android.graphics.PointF[] |  |
### getCommandType() {#getCommandType--}
```
public abstract int getCommandType()
```

Meghatározza a parancs típusát. Read/write [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Visszatér:**  
int
### setCommandType(int value) {#setCommandType-int-}
```
public abstract void setCommandType(int value)
```

Meghatározza a parancs típusát. Read/write [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### isRelative() {#isRelative--}
```
public abstract boolean isRelative()
```

Meghatározza, hogy a parancs koordinátái relatívak-e vagy sem. Read/write boolean.

**Visszatér:**  
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public abstract void setRelative(boolean value)
```

Meghatározza, hogy a parancs koordinátái relatívak-e vagy sem. Read/write boolean.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```

Meghatározza a parancs pontjainak típusát Read/write [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Visszatér:**  
int
### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```

Meghatározza a parancs pontjainak típusát Read/write [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |