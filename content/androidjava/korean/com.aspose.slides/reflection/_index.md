---
title: Reflection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: Reflection 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/reflection/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IReflection](../../com.aspose.slides/ireflection), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Reflection implements IReflection, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Reflection 효과를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | 시작 알파 값(퍼센트)의 알파 그라디언트 램프를 따라 시작 위치를 지정합니다. |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | 시작 알파 값(퍼센트)의 알파 그라디언트 램프를 따라 시작 위치를 지정합니다. |
| [getEndPosAlpha()](#getEndPosAlpha--) | 끝 알파 값(퍼센트)의 알파 그라디언트 램프를 따라 끝 위치를 지정합니다. |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | 끝 알파 값(퍼센트)의 알파 그라디언트 램프를 따라 끝 위치를 지정합니다. |
| [getFadeDirection()](#getFadeDirection--) | 반사를 오프셋할 방향을 지정합니다. |
| [setFadeDirection(float value)](#setFadeDirection-float-) | 반사를 오프셋할 방향을 지정합니다. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | 시작 반사 불투명도입니다. |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | 시작 반사 불투명도입니다. |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | 끝 반사 불투명도입니다. |
| [setEndReflectionOpacity(float value)](#setEndReflectionOpacity-float-) | 끝 반사 불투명도입니다. |
| [getBlurRadius()](#getBlurRadius--) | 블러 반경입니다. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | 블러 반경입니다. |
| [getDirection()](#getDirection--) | 반사의 방향입니다. |
| [setDirection(float value)](#setDirection-float-) | 반사의 방향입니다. |
| [getDistance()](#getDistance--) | 반사의 거리입니다. |
| [setDistance(double value)](#setDistance-double-) | 반사의 거리입니다. |
| [getRectangleAlign()](#getRectangleAlign--) | Rectangle 정렬입니다. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Rectangle 정렬입니다. |
| [getSkewHorizontal()](#getSkewHorizontal--) | 가로 왜곡 각도를 지정합니다. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | 가로 왜곡 각도를 지정합니다. |
| [getSkewVertical()](#getSkewVertical--) | 세로 왜곡 각도를 지정합니다. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | 세로 왜곡 각도를 지정합니다. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | 도형이 회전될 경우 반사도 회전해야 하는지 여부를 지정합니다. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | 도형이 회전될 경우 반사도 회전해야 하는지 여부를 지정합니다. |
| [getScaleHorizontal()](#getScaleHorizontal--) | 가로 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 초래합니다. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | 가로 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 초래합니다. |
| [getScaleVertical()](#getScaleVertical--) | 세로 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 초래합니다. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | 세로 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 초래합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 Reflection 효과 데이터를 가져옵니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 [Reflection](../../com.aspose.slides/reflection)이 현재 [Reflection](../../com.aspose.slides/reflection)와 같은지 여부를 결정합니다. |
| [hashCode()](#hashCode--) | 특정 유형에 대한 해시 함수 역할을 합니다. |

### getStartPosAlpha() {#getStartPosAlpha--}
```
public final float getStartPosAlpha()
```

시작 알파 값(퍼센트)의 알파 그라디언트 램프를 따라 시작 위치를 지정합니다. 읽기/쓰기 float.

**반환값:**
float

### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public final void setStartPosAlpha(float value)
```

시작 알파 값(퍼센트)의 알파 그라디언트 램프를 따라 시작 위치를 지정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getEndPosAlpha() {#getEndPosAlpha--}
```
public final float getEndPosAlpha()
```

끝 알파 값(퍼센트)의 알파 그라디언트 램프를 따라 끝 위치를 지정합니다. 읽기/쓰기 float.

**반환값:**
float

### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public final void setEndPosAlpha(float value)
```

끝 알파 값(퍼센트)의 알파 그라디언트 램프를 따라 끝 위치를 지정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getFadeDirection() {#getFadeDirection--}
```
public final float getFadeDirection()
```

반사를 오프셋할 방향을 지정합니다. (각도). 읽기/쓰기 float.

**반환값:**
float

### setFadeDirection(float value) {#setFadeDirection-float-}
```
public final void setFadeDirection(float value)
```

반사를 오프셋할 방향을 지정합니다. (각도). 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public final float getStartReflectionOpacity()
```

시작 반사 불투명도입니다. (퍼센트). 읽기/쓰기 float.

**반환값:**
float

### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public final void setStartReflectionOpacity(float value)
```

시작 반사 불투명도입니다. (퍼센트). 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public final float getEndReflectionOpacity()
```

끝 반사 불투명도입니다. (퍼센트). 읽기/쓰기 float.

**반환값:**
float

### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public final void setEndReflectionOpacity(float value)
```

끝 반사 불투명도입니다. (퍼센트). 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

블러 반경입니다. 읽기/쓰기 double.

**반환값:**
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

블러 반경입니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

반사의 방향입니다. 읽기/쓰기 float.

**반환값:**
float

### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

반사의 방향입니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

반사의 거리입니다. 읽기/쓰기 double.

**반환값:**
double

### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

반사의 거리입니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```

Rectangle 정렬입니다. 읽기/쓰기 [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**반환값:**
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```

Rectangle 정렬입니다. 읽기/쓰기 [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```

가로 왜곡 각도를 지정합니다. 읽기/쓰기 double.

**반환값:**
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```

가로 왜곡 각도를 지정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```

세로 왜곡 각도를 지정합니다. 읽기/쓰기 double.

**반환값:**
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```

세로 왜곡 각도를 지정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```

도형이 회전될 경우 반사도 회전해야 하는지 여부를 지정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```

도형이 회전될 경우 반사도 회전해야 하는지 여부를 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```

가로 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 초래합니다. (퍼센트) 읽기/쓰기 double.

**반환값:**
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```

가로 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 초래합니다. (퍼센트) 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```

세로 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 초래합니다. (퍼센트) 읽기/쓰기 double.

**반환값:**
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```

세루 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 초래합니다. (퍼센트) 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final IReflectionEffectiveData getEffective()
```

상속이 적용된 효과적인 Reflection 효과 데이터를 가져옵니다.

**반환값:**
[IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata) - A [IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환값:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

버전입니다. 읽기 전용 long.

**반환값:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

부모 IPresentationComponent를 반환합니다. 읽기 전용 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**반환값:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

지정된 [Reflection](../../com.aspose.slides/reflection)이 현재 [Reflection](../../com.aspose.slides/reflection)와 같은지 여부를 결정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [Reflection](../../com.aspose.slides/reflection). |

**반환값:**
boolean - 객체가 동일하면 true; 그렇지 않으면 false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

특정 유형에 대한 해시 함수 역할을 합니다.

**반환값:**
int - 현재 객체에 대한 해시 코드.