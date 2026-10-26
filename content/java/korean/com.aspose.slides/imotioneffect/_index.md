---
title: IMotionEffect
second_title: Aspose.Slides for Java API 참조
description: 효과의 모션 효과 동작을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/imotioneffect/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

효과의 모션 효과 동작을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFrom()](#getFrom--) | 애니메이션을 시작할 x/y 좌표를 지정합니다(백분율 단위). |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | 애니메이션을 시작할 x/y 좌표를 지정합니다(백분율 단위). |
| [getTo()](#getTo--) | 애니메이션 모션 효과의 대상 위치를 지정합니다(백분율 단위). |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | 애니메이션 모션 효과의 대상 위치를 지정합니다(백분율 단위). |
| [getBy()](#getBy--) | 애니메이션의 상대 오프셋 값을 지정합니다(백분율 단위). |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | 애니메이션의 상대 오프셋 값을 지정합니다(백분율 단위). |
| [getRotationCenter()](#getRotationCenter--) | X 각도로 모션 경로를 회전할 때 사용되는 회전 중심을 지정합니다. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | X 각도로 모션 경로를 회전할 때 사용되는 회전 중심을 지정합니다. |
| [getOrigin()](#getOrigin--) | 슬라이드 레이아웃이나 상위 요소와 같이 모션 경로의 기준이 되는 위치를 지정합니다. |
| [setOrigin(int value)](#setOrigin-int-) | 슬라이드 레이아웃이나 상위 요소와 같이 모션 경로의 기준이 되는 위치를 지정합니다. |
| [getPath()](#getPath--) | 애니메이션 모션에 사용되는 경로 프리미티브와 좌표를 지정합니다. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | 애니메이션 모션에 사용되는 경로 프리미티브와 좌표를 지정합니다. |
| [getPathEditMode()](#getPathEditMode--) | 도형이 이동할 때 모션 경로가 어떻게 움직이는지를 지정합니다. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | 도형이 이동할 때 모션 경로가 어떻게 움직이는지를 지정합니다. |
| [getAngle()](#getAngle--) | 모션 경로의 상대 각도를 지정합니다. |
| [setAngle(float value)](#setAngle-float-) | 모션 경로의 상대 각도를 지정합니다. |
### getFrom() {#getFrom--}
```
public abstract Point2D.Float getFrom()
```

애니메이션을 시작할 x/y 좌표를 지정합니다(백분율 단위). 읽기/쓰기 java.awt.geom.Point2D.Float.

**반환값:**
java.awt.geom.Point2D.Float
### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public abstract void setFrom(Point2D.Float value)
```

애니메이션을 시작할 x/y 좌표를 지정합니다(백분율 단위). 읽기/쓰기 java.awt.geom.Point2D.Float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public abstract Point2D.Float getTo()
```

애니메이션 모션 효과의 대상 위치를 지정합니다(백분율 단위). 읽기/쓰기 java.awt.geom.Point2D.Float.

**반환값:**
java.awt.geom.Point2D.Float
### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public abstract void setTo(Point2D.Float value)
```

애니메이션 모션 효과의 대상 위치를 지정합니다(백분율 단위). 읽기/쓰기 java.awt.geom.Point2D.Float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public abstract Point2D.Float getBy()
```

애니메이션의 상대 오프셋 값을 지정합니다(백분율 단위). 읽기/쓰기 java.awt.geom.Point2D.Float.

**반환값:**
java.awt.geom.Point2D.Float
### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public abstract void setBy(Point2D.Float value)
```

애니메이션의 상대 오프셋 값을 지정합니다(백분율 단위). 읽기/쓰기 java.awt.geom.Point2D.Float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract Point2D.Float getRotationCenter()
```

X 각도로 모션 경로를 회전할 때 사용되는 회전 중심을 지정합니다. 읽기/쓰기 java.awt.geom.Point2D.Float.

**반환값:**
java.awt.geom.Point2D.Float
### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public abstract void setRotationCenter(Point2D.Float value)
```

X 각도로 모션 경로를 회전할 때 사용되는 회전 중심을 지정합니다. 읽기/쓰기 java.awt.geom.Point2D.Float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

모션 경로의 기준이 되는 위치를 슬라이드 레이아웃이나 상위 요소와 같이 지정합니다. 읽기/쓰기 [MotionOriginType](../../com.aspose.slides/motionorigintype).

**반환값:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

모션 경로의 기준이 되는 위치를 슬라이드 레이아웃이나 상위 요소와 같이 지정합니다. 읽기/쓰기 [MotionOriginType](../../com.aspose.slides/motionorigintype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

애니메이션 모션에 사용되는 경로 프리미티브와 좌표를 지정합니다. 읽기/쓰기 [IMotionPath](../../com.aspose.slides/imotionpath).

**반환값:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

애니메이션 모션에 사용되는 경로 프리미티브와 좌표를 지정합니다. 읽기/쓰기 [IMotionPath](../../com.aspose.slides/imotionpath).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

도형이 이동할 때 모션 경로가 어떻게 움직이는지를 지정합니다. 읽기/쓰기 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**반환값:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

도형이 이동할 때 모션 경로가 어떻게 움직이는지를 지정합니다. 읽기/쓰기 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

모션 경로의 상대 각도를 지정합니다. 읽기/쓰기 float.

**반환값:**
float
### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

모션 경로의 상대 각도를 지정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |