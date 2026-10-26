---
title: IMotionCmdPath
second_title: Aspose.Slides for Android via Java API Reference
description: Represent one command of a path.
type: docs
url: /zh-hant/com.aspose.slides/imotioncmdpath/
---```
public interface IMotionCmdPath
```

表示路徑中的一個指令。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getPoints()](#getPoints--) | 指定指令的點。 |
| [setPoints(PointF[] value)](#setPoints-android.graphics.PointF---) | 指定指令的點。 |
| [getCommandType()](#getCommandType--) | 指定指令類型。 |
| [setCommandType(int value)](#setCommandType-int-) | 指定指令類型。 |
| [isRelative()](#isRelative--) | 判斷指令座標是否相對。 |
| [setRelative(boolean value)](#setRelative-boolean-) | 判斷指令座標是否相對。 |
| [getPointsType()](#getPointsType--) | 指定指令點類型 讀/寫 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype)。 |
| [setPointsType(int value)](#setPointsType-int-) | 指定指令點類型 讀/寫 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype)。 |

### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```

指定指令的點。 讀/寫 android.graphics.PointF[]。

**返回：**
android.graphics.PointF[]

### setPoints(PointF[] value) {#setPoints-android.graphics.PointF---}
```
public abstract void setPoints(PointF[] value)
```

指定指令的點。 讀/寫 android.graphics.PointF[]。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | android.graphics.PointF[] |  |

### getCommandType() {#getCommandType--}
```
public abstract int getCommandType()
```

指定指令類型。 讀/寫 [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype)。

**返回：**
int

### setCommandType(int value) {#setCommandType-int-}
```
public abstract void setCommandType(int value)
```

指定指令類型。 讀/寫 [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### isRelative() {#isRelative--}
```
public abstract boolean isRelative()
```

判斷指令座標是否相對。 讀/寫 boolean。

**返回：**
boolean

### setRelative(boolean value) {#setRelative-boolean-}
```
public abstract void setRelative(boolean value)
```

判斷指令座標是否相對。 讀/寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```

指定指令點類型 讀/寫 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype)。

**返回：**
int

### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```

指定指令點類型 讀/寫 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |