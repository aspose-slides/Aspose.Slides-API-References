---
title: IMotionCmdPath
second_title: Aspose.Slides for Java API Reference
description: Represent one command of a path.
type: docs
url: /ko/com.aspose.slides/imotioncmdpath/
---```
public interface IMotionCmdPath
```

경로의 하나의 명령을 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [getPoints()](#getPoints--) | 명령의 포인트를 지정합니다. |
| [setPoints(Point2D.Float[] value)](#setPoints-java.awt.geom.Point2D.Float---) | 명령의 포인트를 지정합니다. |
| [getCommandType()](#getCommandType--) | 명령 유형을 지정합니다. |
| [setCommandType(int value)](#setCommandType-int-) | 명령 유형을 지정합니다. |
| [isRelative()](#isRelative--) | 명령 좌표가 상대적인지 여부를 결정합니다. |
| [setRelative(boolean value)](#setRelative-boolean-) | 명령 좌표가 상대적인지 여부를 결정합니다. |
| [getPointsType()](#getPointsType--) | 명령 포인트 유형을 지정합니다 읽기/쓰기 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
| [setPointsType(int value)](#setPointsType-int-) | 명령 포인트 유형을 지정합니다 읽기/쓰기 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```

명령의 포인트를 지정합니다. 읽기/쓰기 java.awt.geom.Point2D.Float[].

**반환값:**
java.awt.geom.Point2D.Float[]
### setPoints(Point2D.Float[] value) {#setPoints-java.awt.geom.Point2D.Float---}
```
public abstract void setPoints(Point2D.Float[] value)
```

명령의 포인트를 지정합니다. 읽기/쓰기 java.awt.geom.Point2D.Float[].

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float[] |  |

### getCommandType() {#getCommandType--}
```
public abstract int getCommandType()
```

명령 유형을 지정합니다. 읽기/쓰기 [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**반환값:**
int
### setCommandType(int value) {#setCommandType-int-}
```
public abstract void setCommandType(int value)
```

명령 유형을 지정합니다. 읽기/쓰기 [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### isRelative() {#isRelative--}
```
public abstract boolean isRelative()
```

명령 좌표가 상대적인지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public abstract void setRelative(boolean value)
```

명령 좌표가 상대적인지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```

명령 포인트 유형을 지정합니다 읽기/쓰기 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**반환값:**
int
### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```

명령 포인트 유형을 지정합니다 읽기/쓰기 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |