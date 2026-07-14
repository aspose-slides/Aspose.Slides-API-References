---
title: IMotionEffect
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 효과의 모션 효과 동작을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/imotioneffect/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

효과의 모션 효과 동작을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFrom()](#getFrom--) | 애니메이션을 시작할 x/y 좌표를 지정합니다(퍼센트 단위). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | 애니메이션을 시작할 x/y 좌표를 지정합니다(퍼센트 단위). |
| [getTo()](#getTo--) | 애니메이션 모션 효과의 목표 위치를 지정합니다(퍼센트 단위). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | 애니메이션 모션 효과의 목표 위치를 지정합니다(퍼센트 단위). |
| [getBy()](#getBy--) | 애니메이션에 대한 상대 오프셋 값을 설명합니다(퍼센트 단위). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | 애니메이션에 대한 상대 오프셋 값을 설명합니다(퍼센트 단위). |
| [getRotationCenter()](#getRotationCenter--) | X 각도만큼 모션 경로를 회전시키는 데 사용되는 회전 중심을 설명합니다. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | X 각도만큼 모션 경로를 회전시키는 데 사용되는 회전 중심을 설명합니다. |
| [getOrigin()](#getOrigin--) | 모션 경로의 원점이 슬라이드 레이아웃이나 상위 요소와 같은 무엇에 상대적인지 지정합니다. |
| [setOrigin(int value)](#setOrigin-int-) | 모션 경로의 원점이 슬라이드 레이아웃이나 상위 요소와 같은 무엇에 상대적인지 지정합니다. |
| [getPath()](#getPath--) | 애니메이션 모션을 위한 좌표가 뒤따르는 경로 원시값을 지정합니다. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | 애니메이션 모션을 위한 좌표가 뒤따르는 경로 원시값을 지정합니다. |
| [getPathEditMode()](#getPathEditMode--) | 형상이 움직일 때 모션 경로가 어떻게 이동하는지 지정합니다. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | 형상이 움직일 때 모션 경로가 어떻게 이동하는지 지정합니다. |
| [getAngle()](#getAngle--) | 모션 경로의 상대 각도를 설명합니다. |
| [setAngle(float value)](#setAngle-float-) | 모션 경로의 상대 각도를 설명합니다. |
### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

애니메이션을 시작할 x/y 좌표를 지정합니다(퍼센트 단위). 읽기/쓰기 android.graphics.PointF.

**반환값:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

애니메이션을 시작할 x/y 좌표를 지정합니다(퍼센트 단위). 읽기/쓰기 android.graphics.PointF.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public abstract PointF getTo()
```

애니메이션 모션 효과의 목표 위치를 지정합니다(퍼센트 단위). 읽기/쓰기 android.graphics.PointF.

**반환값:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

애니메이션 모션 효과의 목표 위치를 지정합니다(퍼센트 단위). 읽기/쓰기 android.graphics.PointF.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public abstract PointF getBy()
```

애니메이션에 대한 상대 오프셋 값을 설명합니다(퍼센트 단위). 읽기/쓰기 android.graphics.PointF.

**반환값:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

애니메이션에 대한 상대 오프셋 값을 설명합니다(퍼센트 단위). 읽기/쓰기 android.graphics.PointF.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract PointF getRotationCenter()
```

X 각도만큼 모션 경로를 회전시키는 데 사용되는 회전 중심을 설명합니다. 읽기/쓰기 android.graphics.PointF.

**반환값:**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public abstract void setRotationCenter(PointF value)
```

X 각도만큼 모션 경로를 회전시키는 데 사용되는 회전 중심을 설명합니다. 읽기/쓰기 android.graphics.PointF.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

모션 경로의 원점이 슬라이드 레이아웃이나 상위 요소와 같은 무엇에 상대적인지 지정합니다. 읽기/쓰기 [MotionOriginType](../../com.aspose.slides/motionorigintype).

**반환값:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

모션 경로의 원점이 슬라이드 레이아웃이나 상위 요소와 같은 무엇에 상대적인지 지정합니다. 읽기/쓰기 [MotionOriginType](../../com.aspose.slides/motionorigintype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

애니메이션 모션을 위한 좌표가 뒤따르는 경로 원시값을 지정합니다. 읽기/쓰기 [IMotionPath](../../com.aspose.slides/imotionpath).

**반환값:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

애니메이션 모션을 위한 좌표가 뒤따르는 경로 원시값을 지정합니다. 읽기/쓰기 [IMotionPath](../../com.aspose.slides/imotionpath).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

형상이 움직일 때 모션 경로가 어떻게 이동하는지 지정합니다. 읽기/쓰기 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**반환값:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

형상이 움직일 때 모션 경로가 어떻게 이동하는지 지정합니다. 읽기/쓰기 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

모션 경로의 상대 각도를 설명합니다. 읽기/쓰기 float.

**반환값:**
float
### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

모션 경로의 상대 각도를 설명합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
