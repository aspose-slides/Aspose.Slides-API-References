---
title: Reflection
second_title: Aspose.Slides for Java API 레퍼런스
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
| [getStartPosAlpha()](#getStartPosAlpha--) | 시작 알파 값(퍼센트)의 알파 그라데이션 램프를 따라 시작 위치를 지정합니다. |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | 시작 알파 값(퍼센트)의 알파 그라데이션 램프를 따라 시작 위치를 지정합니다. |
| [getEndPosAlpha()](#getEndPosAlpha--) | 끝 알파 값(퍼센트)의 알파 그라데이션 램프를 따라 끝 위치를 지정합니다. |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | 끝 알파 값(퍼센트)의 알파 그라데이션 램프를 따라 끝 위치를 지정합니다. |
| [getFadeDirection()](#getFadeDirection--) | Reflection을 오프셋할 방향을 지정합니다. (각도) |
| [setFadeDirection(float value)](#setFadeDirection-float-) | Reflection을 오프셋할 방향을 지정합니다. (각도) |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | 시작 반사 불투명도. (퍼센트) |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | 시작 반사 불투명도. (퍼센트) |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | 끝 반사 불투명도. (퍼센트) |
| [setEndReflectionOpacity(float value)](#setEndReflectionOpacity-float-) | 끝 반사 불투명도. (퍼센트) |
| [getBlurRadius()](#getBlurRadius--) | 블러 반경. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | 블러 반경. |
| [getDirection()](#getDirection--) | Reflection 방향. |
| [setDirection(float value)](#setDirection-float-) | Reflection 방향. |
| [getDistance()](#getDistance--) | Reflection 거리. |
| [setDistance(double value)](#setDistance-double-) | Reflection 거리. |
| [getRectangleAlign()](#getRectangleAlign--) | 사각형 정렬. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | 사각형 정렬. |
| [getSkewHorizontal()](#getSkewHorizontal--) | 수평 왜곡 각도를 지정합니다. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | 수평 왜곡 각도를 지정합니다. |
| [getSkewVertical()](#getSkewVertical--) | 수직 왜곡 각도를 지정합니다. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | 수직 왜곡 각도를 지정합니다. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | 형상이 회전된 경우 Reflection이 형상과 함께 회전하도록 지정합니다. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | 형상이 회전된 경우 Reflection이 형상과 함께 회전하도록 지정합니다. |
| [getScaleHorizontal()](#getScaleHorizontal--) | 수평 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 일으킵니다. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | 수평 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 일으킵니다. |
| [getScaleVertical()](#getScaleVertical--) | 수직 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 일으킵니다. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | 수직 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 일으킵니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 Reflection 데이터를 가져옵니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 [Reflection](../../com.aspose.slides/reflection)가 현재 [Reflection](../../com.aspose.slides/reflection)와 동일한지 여부를 결정합니다. |
| [hashCode()](#hashCode--) | 특정 유형에 대한 해시 함수를 제공합니다. |

### getStartPosAlpha() {#getStartPosAlpha--}
```
public final float getStartPosAlpha()
```

시작 알파 값(퍼센트)의 알파 그라데이션 램프를 따라 시작 위치를 지정합니다. 읽기/쓰기 float.

**반환:**  
float

### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public final void setStartPosAlpha(float value)
```

시작 알파 값(퍼센트)의 알파 그라데이션 램프를 따라 시작 위치를 지정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getEndPosAlpha() {#getEndPosAlpha--}
```
public final float getEndPosAlpha()
```

끝 알파 값(퍼센트)의 알파 그라데이션 램프를 따라 끝 위치를 지정합니다. 읽기/쓰기 float.

**반환:**  
float

### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public final void setEndPosAlpha(float value)
```

끝 알파 값(퍼센트)의 알파 그라데이션 램프를 따라 끝 위치를 지정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getFadeDirection() {#getFadeDirection--}
```
public final float getFadeDirection()
```

Reflection을 오프셋할 방향을 지정합니다. (각도) 읽기/쓰기 float.

**반환:**  
float

### setFadeDirection(float value) {#setFadeDirection-float-}
```
public final void setFadeDirection(float value)
```

Reflection을 오프셋할 방향을 지정합니다. (각도) 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public final float getStartReflectionOpacity()
```

시작 반사 불투명도. (퍼센트) 읽기/쓰기 float.

**반환:**  
float

### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public final void setStartReflectionOpacity(float value)
```

시작 반사 불투명도. (퍼센트) 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public final float getEndReflectionOpacity()
```

끝 반사 불투명도. (퍼센트) 읽기/쓰기 float.

**반환:**  
float

### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public final void setEndReflectionOpacity(float value)
```

끝 반사 불투명도. (퍼센트) 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

블러 반경. 읽기/쓰기 double.

**반환:**  
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

블러 반경. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

Reflection 방향. 읽기/쓰기 float.

**반환:**  
float

### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Reflection 방향. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

Reflection 거리. 읽기/쓰기 double.

**반환:**  
double

### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Reflection 거리. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```

사각형 정렬. 읽기/쓰기 [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**반환:**  
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```

사각형 정렬. 읽기/쓰기 [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```

수평 왜곡 각도를 지정합니다. 읽기/쓰기 double.

**반환:**  
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```

수평 왜곡 각도를 지정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```

수직 왜곡 각도를 지정합니다. 읽기/쓰기 double.

**반환:**  
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```

수직 왜곡 각도를 지정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```

형상이 회전된 경우 Reflection이 형상과 함께 회전하도록 지정합니다. 읽기/쓰기 boolean.

**반환:**  
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```

형상이 회전된 경우 Reflection이 형상과 함께 회전하도록 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```

수평 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 일으킵니다. (퍼센트) 읽기/쓰기 double.

**반환:**  
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```

수평 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 일으킵니다. (퍼센트) 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```

수직 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 일으킵니다. (퍼센트) 읽기/쓰기 double.

**반환:**  
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```

수직 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 일으킵니다. (퍼센트) 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final IReflectionEffectiveData getEffective()
```

상속이 적용된 효과적인 Reflection 데이터를 가져옵니다.

**반환:**  
[IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata) - A [IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**  
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

버전. 읽기 전용 long.

**반환:**  
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

부모 IPresentationComponent를 반환합니다. 읽기 전용 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**반환:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

지정된 [Reflection](../../com.aspose.slides/reflection)가 현재 [Reflection](../../com.aspose.slides/reflection)와 동일한지 여부를 결정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [Reflection](../../com.aspose.slides/reflection). |

**반환:**  
boolean - 객체가 동일하면 true; 그렇지 않으면 false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

특정 유형에 대한 해시 함수 역할을 합니다.

**반환:**  
int - 현재 객체에 대한 해시 코드.