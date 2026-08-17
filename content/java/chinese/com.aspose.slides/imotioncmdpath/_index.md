---
title: IMotionCmdPath
second_title: Aspose.Slides Java API 参考
description: 表示路径的一个命令。
type: docs
url: /zh/com.aspose.slides/imotioncmdpath/
---```
public interface IMotionCmdPath
```

表示路径的一个命令。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPoints()](#getPoints--) | 指定命令的点。 |
| [setPoints(Point2D.Float[] value)](#setPoints-java.awt.geom.Point2D.Float---) | 指定命令的点。 |
| [getCommandType()](#getCommandType--) | 指定命令类型。 |
| [setCommandType(int value)](#setCommandType-int-) | 指定命令类型。 |
| [isRelative()](#isRelative--) | 确定命令坐标是否相对。 |
| [setRelative(boolean value)](#setRelative-boolean-) | 确定命令坐标是否相对。 |
| [getPointsType()](#getPointsType--) | 指定命令点类型 读取/写入 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype)。 |
| [setPointsType(int value)](#setPointsType-int-) | 指定命令点类型 读取/写入 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype)。 |
### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```

指定命令的点。读取/写入 java.awt.geom.Point2D.Float[]。

**返回:**
java.awt.geom.Point2D.Float[]
### setPoints(Point2D.Float[] value) {#setPoints-java.awt.geom.Point2D.Float---}
```
public abstract void setPoints(Point2D.Float[] value)
```

指定命令的点。读取/写入 java.awt.geom.Point2D.Float[]。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float[] |  |
### getCommandType() {#getCommandType--}
```
public abstract int getCommandType()
```

指定命令类型。读取/写入 [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype)。

**返回:**
int
### setCommandType(int value) {#setCommandType-int-}
```
public abstract void setCommandType(int value)
```

指定命令类型。读取/写入 [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### isRelative() {#isRelative--}
```
public abstract boolean isRelative()
```

确定命令坐标是否相对。读取/写入 boolean。

**返回:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public abstract void setRelative(boolean value)
```

确定命令坐标是否相对。读取/写入 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```

指定命令点类型 读取/写入 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype)。

**返回:**
int
### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```

指定命令点类型 读取/写入 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |