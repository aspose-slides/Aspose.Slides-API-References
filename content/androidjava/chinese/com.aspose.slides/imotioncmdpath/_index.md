---
title: IMotionCmdPath
second_title: Aspose.Slides for Android via Java API 参考
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
| [setPoints(PointF[] value)](#setPoints-android.graphics.PointF---) | 指定命令的点。 |
| [getCommandType()](#getCommandType--) | 指定命令类型。 |
| [setCommandType(int value)](#setCommandType-int-) | 指定命令类型。 |
| [isRelative()](#isRelative--) | 确定命令坐标是否相对。 |
| [setRelative(boolean value)](#setRelative-boolean-) | 确定命令坐标是否相对。 |
| [getPointsType()](#getPointsType--) | 指定命令点的类型 读/写 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype)。 |
| [setPointsType(int value)](#setPointsType-int-) | 指定命令点的类型 读/写 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype)。 |
### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```

指定命令的点。读/写 android.graphics.PointF[]。

**返回值：**
android.graphics.PointF[]
### setPoints(PointF[] value) {#setPoints-android.graphics.PointF---}
```
public abstract void setPoints(PointF[] value)
```

指定命令的点。读/写 android.graphics.PointF[]。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | android.graphics.PointF[] |  |
### getCommandType() {#getCommandType--}
```
public abstract int getCommandType()
```

指定命令类型。读/写 [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype)。

**返回值：**
int
### setCommandType(int value) {#setCommandType-int-}
```
public abstract void setCommandType(int value)
```

指定命令类型。读/写 [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### isRelative() {#isRelative--}
```
public abstract boolean isRelative()
```

确定命令坐标是否相对。读/写 boolean。

**返回值：**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public abstract void setRelative(boolean value)
```

确定命令坐标是否相对。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```

指定命令点的类型 读/写 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype)。

**返回值：**
int
### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```

指定命令点的类型 读/写 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |