---
title: MotionCmdPath
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 경로의 하나의 명령을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/motioncmdpath/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)  
```
public class MotionCmdPath implements IMotionCmdPath
```

경로의 하나의 명령을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPoints()](#getPoints--) | 명령의 포인트를 지정합니다. |
| [setPoints(PointF[] value)](#setPoints-android.graphics.PointF---) | 명령의 포인트를 지정합니다. |
| [getCommandType()](#getCommandType--) | 명령 유형을 지정합니다. |
| [setCommandType(int value)](#setCommandType-int-) | 명령 유형을 지정합니다. |
| [isRelative()](#isRelative--) | 명령 좌표가 상대적인지 여부를 결정합니다. |
| [setRelative(boolean value)](#setRelative-boolean-) | 명령 좌표가 상대적인지 여부를 결정합니다. |
| [getPointsType()](#getPointsType--) | 명령 포인트 유형을 지정합니다. 읽기/쓰기 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
| [setPointsType(int value)](#setPointsType-int-) | 명령 포인트 유형을 지정합니다. 읽기/쓰기 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |

### getPoints() {#getPoints--}
```
public final PointF[] getPoints()
```

명령의 포인트를 지정합니다. 읽기/쓰기 android.graphics.PointF[].

**반환:**  
android.graphics.PointF[]

### setPoints(PointF[] value) {#setPoints-android.graphics.PointF---}
```
public final void setPoints(PointF[] value)
```

명령의 포인트를 지정합니다. 읽기/쓰기 android.graphics.PointF[].

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | android.graphics.PointF[] |  |

### getCommandType() {#getCommandType--}
```
public final int getCommandType()
```

명령 유형을 지정합니다. 읽기/쓰기 [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**반환:**  
int

### setCommandType(int value) {#setCommandType-int-}
```
public final void setCommandType(int value)
```

명령 유형을 지정합니다. 읽기/쓰기 [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### isRelative() {#isRelative--}
```
public final boolean isRelative()
```

명령 좌표가 상대적인지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**  
boolean

### setRelative(boolean value) {#setRelative-boolean-}
```
public final void setRelative(boolean value)
```

명령 좌표가 상대적인지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getPointsType() {#getPointsType--}
```
public final int getPointsType()
```

명령 포인트 유형을 지정합니다. 읽기/쓰기 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**반환:**  
int

### setPointsType(int value) {#setPointsType-int-}
```
public final void setPointsType(int value)
```

명령 포인트 유형을 지정합니다. 읽기/쓰기 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |