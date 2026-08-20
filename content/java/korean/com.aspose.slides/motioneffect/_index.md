---
title: MotionEffect
second_title: Aspose.Slides Java API 레퍼런스
description: 효과의 움직임 효과 동작을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/motioneffect/
---
**상속:**  
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IMotionEffect](../../com.aspose.slides/imotioneffect)  
```
public class MotionEffect extends Behavior implements IMotionEffect
```

효과의 움직임 효과 동작을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFrom()](#getFrom--) | 애니메이션을 시작할 x/y 좌표를 지정합니다 (퍼센트 단위). |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | 애니메이션을 시작할 x/y 좌표를 지정합니다 (퍼센트 단위). |
| [getTo()](#getTo--) | 애니메이션 움직임 효과의 대상 위치를 지정합니다 (퍼센트 단위). |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | 애니메이션 움직임 효과의 대상 위치를 지정합니다 (퍼센트 단위). |
| [getBy()](#getBy--) | 애니메이션의 상대 오프셋 값을 지정합니다 (퍼센트 단위). |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | 애니메이션의 상대 오프셋 값을 지정합니다 (퍼센트 단위). |
| [getRotationCenter()](#getRotationCenter--) | X 각도로 움직임 경로를 회전시키는 회전 중심을 지정합니다. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | X 각도로 움직임 경로를 회전시키는 회전 중심을 지정합니다. |
| [getOrigin()](#getOrigin--) | 슬라이드 레이아웃이나 상위 요소와 같이 움직임 경로의 기준이 되는 원점을 지정합니다. |
| [setOrigin(int value)](#setOrigin-int-) | 슬라이드 레이아웃이나 상위 요소와 같이 움직임 경로의 기준이 되는 원점을 지정합니다. |
| [getPath()](#getPath--) | 애니메이션 동작을 위한 경로 원시 요소와 좌표를 지정합니다. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | 애니메이션 동작을 위한 경로 원시 요소와 좌표를 지정합니다. |
| [getPathEditMode()](#getPathEditMode--) | 도형이 이동할 때 움직임 경로가 어떻게 이동하는지를 지정합니다. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | 도형이 이동할 때 움직임 경로가 어떻게 이동하는지를 지정합니다. |
| [getAngle()](#getAngle--) | 움직임 경로의 상대 각도를 지정합니다. |
| [setAngle(float value)](#setAngle-float-) | 움직임 경로의 상대 각도를 지정합니다. |

### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```

### getFrom() {#getFrom--}
```
public final Point2D.Float getFrom()
```

애니메이션을 시작할 x/y 좌표를 지정합니다 (퍼센트 단위). 읽기/쓰기 java.awt.geom.Point2D.Float.

**반환:**
java.awt.geom.Point2D.Float

### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public final void setFrom(Point2D.Float value)
```

애니메이션을 시작할 x/y 좌표를 지정합니다 (퍼센트 단위). 읽기/쓰기 java.awt.geom.Point2D.Float.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public final Point2D.Float getTo()
```

애니메이션 움직임 효과의 대상 위치를 지정합니다 (퍼센트 단위). 읽기/쓰기 java.awt.geom.Point2D.Float.

**반환:**
java.awt.geom.Point2D.Float

### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public final void setTo(Point2D.Float value)
```

애니메이션 움직임 효과의 대상 위치를 지정합니다 (퍼센트 단위). 읽기/쓰기 java.awt.geom.Point2D.Float.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public final Point2D.Float getBy()
```

애니메이션의 상대 오프셋 값을 지정합니다 (퍼센트 단위). 읽기/쓰기 java.awt.geom.Point2D.Float.

**반환:**
java.awt.geom.Point2D.Float

### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public final void setBy(Point2D.Float value)
```

애니메이션의 상대 오프셋 값을 지정합니다 (퍼센트 단위). 읽기/쓰기 java.awt.geom.Point2D.Float.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public final Point2D.Float getRotationCenter()
```

X 각도로 움직임 경로를 회전시키는 회전 중심을 지정합니다. 읽기/쓰기 java.awt.geom.Point2D.Float.

**반환:**
java.awt.geom.Point2D.Float

### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public final void setRotationCenter(Point2D.Float value)
```

X 각도로 움직임 경로를 회전시키는 회전 중심을 지정합니다. 읽기/쓰기 java.awt.geom.Point2D.Float.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```

슬라이드 레이아웃이나 상위 요소와 같이 움직임 경로의 기준이 되는 원점을 지정합니다. 읽기/쓰기 [MotionOriginType](../../com.aspose.slides/motionorigintype).

**반환:**
int

### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```

슬라이드 레이아웃이나 상위 요소와 같이 움직임 경로의 기준이 되는 원점을 지정합니다. 읽기/쓰기 [MotionOriginType](../../com.aspose.slides/motionorigintype).

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```

애니메이션 동작을 위한 경로 원시 요소와 좌표를 지정합니다. 읽기/쓰기 [IMotionPath](../../com.aspose.slides/imotionpath).

**반환:**
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```

애니메이션 동작을 위한 경로 원시 요소와 좌표를 지정합니다. 읽기/쓰기 [IMotionPath](../../com.aspose.slides/imotionpath).

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```

도형이 이동할 때 움직임 경로가 어떻게 이동하는지를 지정합니다. 읽기/쓰기 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**반환:**
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```

도형이 이동할 때 움직임 경로가 어떻게 이동하는지를 지정합니다. 읽기/쓰기 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```

움직임 경로의 상대 각도를 지정합니다. 읽기/쓰기 float.

**반환:**
float

### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```

움직임 경로의 상대 각도를 지정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | float |  |