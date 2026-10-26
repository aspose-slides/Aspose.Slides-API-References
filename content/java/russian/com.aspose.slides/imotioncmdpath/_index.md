---
title: IMotionCmdPath
second_title: Aspose.Slides для Java API
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
| [setPoints(Point2D.Float[] value)](#setPoints-java.awt.geom.Point2D.Float---) | Указывает точки команды. |
| [getCommandType()](#getCommandType--) | Указывает тип команды. |
| [setCommandType(int value)](#setCommandType-int-) | Указывает тип команды. |
| [isRelative()](#isRelative--) | Определяет координаты команды относительные или нет. |
| [setRelative(boolean value)](#setRelative-boolean-) | Определяет координаты команды относительные или нет. |
| [getPointsType()](#getPointsType--) | Указывает тип точек команды Чтение/запись [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
| [setPointsType(int value)](#setPointsType-int-) | Указывает тип точек команды Чтение/запись [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```

Указывает точки команды. Чтение/запись java.awt.geom.Point2D.Float[].

**Возвращаемое значение:**
java.awt.geom.Point2D.Float[]
### setPoints(Point2D.Float[] value) {#setPoints-java.awt.geom.Point2D.Float---}
```
public abstract void setPoints(Point2D.Float[] value)
```

Указывает точки команды. Чтение/запись java.awt.geom.Point2D.Float[].

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float[] |  |
### getCommandType() {#getCommandType--}
```
public abstract int getCommandType()
```

Указывает тип команды. Чтение/запись [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Возвращаемое значение:**
int
### setCommandType(int value) {#setCommandType-int-}
```
public abstract void setCommandType(int value)
```

Указывает тип команды. Чтение/запись [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### isRelative() {#isRelative--}
```
public abstract boolean isRelative()
```

Определяет координаты команды относительные или нет. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public abstract void setRelative(boolean value)
```

Определяет координаты команды относительные или нет. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```

Указывает тип точек команды Чтение/запись [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Возвращаемое значение:**
int
### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```

Указывает тип точек команды Чтение/запись [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |