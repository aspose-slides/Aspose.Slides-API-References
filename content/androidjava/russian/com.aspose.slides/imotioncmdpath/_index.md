---
title: IMotionCmdPath
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет одну команду пути.
type: docs
url: /ru/com.aspose.slides/imotioncmdpath/
---```
public interface IMotionCmdPath
```

Представляет одну команду пути.
## Методы

| Метод | Описание |
| --- | --- |
| [getPoints()](#getPoints--) | Указывает точки команды. |
| [setPoints(PointF[] value)](#setPoints-android.graphics.PointF---) | Указывает точки команды. |
| [getCommandType()](#getCommandType--) | Указывает тип команды. |
| [setCommandType(int value)](#setCommandType-int-) | Указывает тип команды. |
| [isRelative()](#isRelative--) | Определяет, являются ли координаты команды относительными или нет. |
| [setRelative(boolean value)](#setRelative-boolean-) | Определяет, являются ли координаты команды относительными или нет. |
| [getPointsType()](#getPointsType--) | Указывает тип точек команды Read/write [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
| [setPointsType(int value)](#setPointsType-int-) | Указывает тип точек команды Read/write [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```

Указывает точки команды. Read/write android.graphics.PointF[].

**Возвращает:**
android.graphics.PointF[]
### setPoints(PointF[] value) {#setPoints-android.graphics.PointF---}
```
public abstract void setPoints(PointF[] value)
```

Указывает точки команды. Read/write android.graphics.PointF[].

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | android.graphics.PointF[] |  |

### getCommandType() {#getCommandType--}
```
public abstract int getCommandType()
```

Указывает тип команды. Read/write [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Возвращает:**
int
### setCommandType(int value) {#setCommandType-int-}
```
public abstract void setCommandType(int value)
```

Указывает тип команды. Read/write [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### isRelative() {#isRelative--}
```
public abstract boolean isRelative()
```

Определяет, являются ли координаты команды относительными или нет. Read/write boolean.

**Возвращает:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public abstract void setRelative(boolean value)
```

Определяет, являются ли координаты команды относительными или нет. Read/write boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```

Указывает тип точек команды Read/write [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Возвращает:**
int
### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```

Указывает тип точек команды Read/write [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |