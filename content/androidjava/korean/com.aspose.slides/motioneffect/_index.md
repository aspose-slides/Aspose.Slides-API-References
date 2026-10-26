---
title: MotionEffect
second_title: Java API 레퍼런스를 통한 Aspose.Slides for Android
description: 효과의 모션 효과 동작을 나타냅니다.
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

효과의 모션 효과 동작을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFrom()](#getFrom--) | 애니메이션을 시작할 x/y 좌표를 지정합니다 (백분율). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | 애니메이션을 시작할 x/y 좌표를 지정합니다 (백분율). |
| [getTo()](#getTo--) | 애니메이션 모션 효과의 목표 위치를 지정합니다 (백분율). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | 애니메이션 모션 효과의 목표 위치를 지정합니다 (백분율). |
| [getBy()](#getBy--) | 애니메이션의 상대 오프셋 값을 설명합니다 (백분율). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | 애니메이션의 상대 오프셋 값을 설명합니다 (백분율). |
| [getRotationCenter()](#getRotationCenter--) | X 각도로 모션 경로를 회전시키는 데 사용되는 회전 중심을 설명합니다. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | X 각도로 모션 경로를 회전시키는 데 사용되는 회전 중심을 설명합니다. |
| [getOrigin()](#getOrigin--) | 슬라이드 레이아웃이나 부모 등과 같은 기준에 대해 모션 경로의 원점을 지정합니다. |
| [setOrigin(int value)](#setOrigin-int-) | 슬라이드 레이아웃이나 부모 등과 같은 기준에 대해 모션 경로의 원점을 지정합니다. |
| [getPath()](#getPath--) | 애니메이션 모션을 위한 좌표와 함께 경로 프리미티브를 지정합니다. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | 애니메이션 모션을 위한 좌표와 함께 경로 프리미티브를 지정합니다. |
| [getPathEditMode()](#getPathEditMode--) | 도형이 이동할 때 모션 경로가 어떻게 움직이는지를 지정합니다. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | 도형이 이동할 때 모션 경로가 어떻게 움직이는지를 지정합니다. |
| [getAngle()](#getAngle--) | 모션 경로의 상대 각도를 설명합니다. |
| [setAngle(float value)](#setAngle-float-) | 모션 경로의 상대 각도를 설명합니다. |
### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```

### getFrom() {#getFrom--}
```
public final PointF getFrom()
```

애니메이션을 시작할 x/y 좌표를 지정합니다 (백분율). 읽기/쓰기 android.graphics.PointF.

**반환:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public final void setFrom(PointF value)
```

애니메이션을 시작할 x/y 좌표를 지정합니다 (백분율). 읽기/쓰기 android.graphics.PointF.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public final PointF getTo()
```

애니메이션 모션 효과의 목표 위치를 지정합니다 (백분율). 읽기/쓰기 android.graphics.PointF.

**반환:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public final void setTo(PointF value)
```

애니메이션 모션 효과의 목표 위치를 지정합니다 (백분율). 읽기/쓰기 android.graphics.PointF.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public final PointF getBy()
```

애니메이션의 상대 오프셋 값을 설명합니다 (백분율). 읽기/쓰기 android.graphics.PointF.

**반환:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public final void setBy(PointF value)
```

애니메이션의 상대 오프셋 값을 설명합니다 (백분율). 읽기/쓰기 android.graphics.PointF.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public final PointF getRotationCenter()
```

X 각도로 모션 경로를 회전시키는 데 사용되는 회전 중심을 설명합니다. 읽기/쓰기 android.graphics.PointF.

**반환:**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public final void setRotationCenter(PointF value)
```

X 각도로 모션 경로를 회전시키는 데 사용되는 회전 중심을 설명합니다. 읽기/쓰기 android.graphics.PointF.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```

슬라이드 레이아웃이나 부모 등과 같은 기준에 대해 모션 경로의 원점을 지정합니다. 읽기/쓰기 [MotionOriginType](../../com.aspose.slides/motionorigintype).

**반환:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```

슬라이드 레이아웃이나 부모 등과 같은 기준에 대해 모션 경로의 원점을 지정합니다. 읽기/쓰기 [MotionOriginType](../../com.aspose.slides/motionorigintype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```

애니메이션 모션을 위한 좌표와 함께 경로 프리미티브를 지정합니다. 읽기/쓰기 [IMotionPath](../../com.aspose.slides/imotionpath).

**반환:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```

애니메이션 모션을 위한 좌표와 함께 경로 프리미티브를 지정합니다. 읽기/쓰기 [IMotionPath](../../com.aspose.slides/imotionpath).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```

도형이 이동할 때 모션 경로가 어떻게 움직이는지를 지정합니다. 읽기/쓰기 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**반환:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```

도형이 이동할 때 모션 경로가 어떻게 움직이는지를 지정합니다. 읽기/쓰기 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```

모션 경로의 상대 각도를 설명합니다. 읽기/쓰기 float.

**반환:**
float
### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```

모션 경로의 상대 각도를 설명합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |