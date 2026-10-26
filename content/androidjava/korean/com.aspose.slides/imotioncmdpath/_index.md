---
title: IMotionCmdPath
second_title: Aspose.Slides for Android via Java API Reference
description: Represent one command of a path.
type: docs
url: /ko/com.aspose.slides/imotioncmdpath/
---```
public interface IMotionCmdPath
```

경로의 한 명령을 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [getPoints()](#getPoints--) | 명령의 점을 지정합니다. |
| [setPoints(PointF[] value)](#setPoints-android.graphics.PointF---) | 명령의 점을 지정합니다. |
| [getCommandType()](#getCommandType--) | 명령 유형을 지정합니다. |
| [setCommandType(int value)](#setCommandType-int-) | 명령 유형을 지정합니다. |
| [isRelative()](#isRelative--) | 명령 좌표가 상대적인지 여부를 결정합니다. |
| [setRelative(boolean value)](#setRelative-boolean-) | 명령 좌표가 상대적인지 여부를 결정합니다. |
| [getPointsType()](#getPointsType--) | 명령 점 유형을 지정합니다. 읽기/쓰기 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
| [setPointsType(int value)](#setPointsType-int-) | 명령 점 유형을 지정합니다. 읽기/쓰기 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```

명령의 점을 지정합니다. 읽기/쓰기 android.graphics.PointF[].

**반환값:**
android.graphics.PointF[]
### setPoints(PointF[] value) {#setPoints-android.graphics.PointF---}
```
public abstract void setPoints(PointF[] value)
```

명령의 점을 지정합니다. 읽기/쓰기 android.graphics.PointF[].

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | android.graphics.PointF[] |  |
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
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```

명령 점 유형을 지정합니다. 읽기/쓰기 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**반환값:**
int
### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```

명령 점 유형을 지정합니다. 읽기/쓰기 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |