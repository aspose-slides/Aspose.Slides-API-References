---
title: IReflection
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 반사 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ireflection/
---
**구현된 모든 인터페이스:**  
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject  
```
public interface IReflection extends IImageTransformOperation, IAccessiblePVIObject<IReflectionEffectiveData>
```

반사 효과를 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | 시작 알파 값(퍼센트)의 알파 그라디언트 램프를 따라 시작 위치를 지정합니다. |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | 시작 알파 값(퍼센트)의 알파 그라디언트 램프를 따라 시작 위치를 지정합니다. |
| [getEndPosAlpha()](#getEndPosAlpha--) | 끝 알파 값(퍼센트)의 알파 그라디언트 램프를 따라 끝 위치를 지정합니다. |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | 끝 알파 값(퍼센트)의 알파 그라디언트 램프를 따라 끝 위치를 지정합니다. |
| [getFadeDirection()](#getFadeDirection--) | 반사의 오프셋 방향을 지정합니다. |
| [setFadeDirection(float value)](#setFadeDirection-float-) | 반사의 오프셋 방향을 지정합니다. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | 시작 반사 불투명도. |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | 시작 반사 불투명도. |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | 끝 반사 불투명도. |
| [setEndReflectionOpacity(float value)](#setEndReflectionOpacity-float-) | 끝 반사 불투명도. |
| [getBlurRadius()](#getBlurRadius--) | 블러 반경. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | 블러 반경. |
| [getDirection()](#getDirection--) | 반사 방향. |
| [setDirection(float value)](#setDirection-float-) | 반사 방향. |
| [getDistance()](#getDistance--) | 반사 거리. |
| [setDistance(double value)](#setDistance-double-) | 반사 거리. |
| [getRectangleAlign()](#getRectangleAlign--) | 사각형 정렬. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | 사각형 정렬. |
| [getSkewHorizontal()](#getSkewHorizontal--) | 수평 왜곡 각도를 지정합니다. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | 수평 왜곡 각도를 지정합니다. |
| [getSkewVertical()](#getSkewVertical--) | 수직 왜곡 각도를 지정합니다. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | 수직 왜곡 각도를 지정합니다. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | 모양이 회전된 경우 반사가 모양과 함께 회전해야 하는지 지정합니다. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | 모양이 회전된 경우 반사가 모양과 함께 회전해야 하는지 지정합니다. |
| [getScaleHorizontal()](#getScaleHorizontal--) | 수평 스케일 팩터를 지정합니다. 음수 스케일은 뒤집기를 발생시킵니다. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | 수평 스케일 팩터를 지정합니다. 음수 스케일은 뒤집기를 발생시킵니다. |
| [getScaleVertical()](#getScaleVertical--) | 수직 스케일 팩터를 지정합니다. 음수 스케일은 뒤집기를 발생시킵니다. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | 수직 스케일 팩터를 지정합니다. 음수 스케일은 뒤집기를 발생시킵니다. |

### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```

시작 알파 값(퍼센트)의 알파 그라디언트 램프를 따라 시작 위치를 지정합니다. 읽기/쓰기 float.

**반환:**  
float

### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public abstract void setStartPosAlpha(float value)
```

시작 알파 값(퍼센트)의 알파 그라디언트 램프를 따라 시작 위치를 지정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```

끝 알파 값(퍼센트)의 알파 그라디언트 램프를 따라 끝 위치를 지정합니다. 읽기/쓰기 float.

**반환:**  
float

### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public abstract void setEndPosAlpha(float value)
```

끝 알파 값(퍼센트)의 알파 그라디언트 램프를 따라 끝 위치를 지정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```

반사의 오프셋 방향을 지정합니다. (각도) 읽기/쓰기 float.

**반환:**  
float

### setFadeDirection(float value) {#setFadeDirection-float-}
```
public abstract void setFadeDirection(float value)
```

반사의 오프셋 방향을 지정합니다. (각도) 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```

시작 반사 불투명도. (퍼센트) 읽기/쓰기 float.

**반환:**  
float

### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public abstract void setStartReflectionOpacity(float value)
```

시작 반사 불투명도. (퍼센트) 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```

끝 반사 불투명도. (퍼센트) 읽기/쓰기 float.

**반환:**  
float

### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public abstract void setEndReflectionOpacity(float value)
```

끝 반사 불투명도. (퍼센트) 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

블러 반경. 읽기/쓰기 double.

**반환:**  
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

블러 반경. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

반사 방향. 읽기/쓰기 float.

**반환:**  
float

### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

반사 방향. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

반사 거리. 읽기/쓰기 double.

**반환:**  
double

### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

반사 거리. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

사각형 정렬. 읽기/쓰기 [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**반환:**  
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

사각형 정렬. 읽기/쓰기 [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

수평 왜곡 각도를 지정합니다. 읽기/쓰기 double.

**반환:**  
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

수평 왜곡 각도를 지정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

수직 왜곡 각도를 지정합니다. 읽기/쓰기 double.

**반환:**  
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

수직 왜곡 각도를 지정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

모양이 회전된 경우 반사가 모양과 함께 회전해야 하는지 지정합니다. 읽기/쓰기 boolean.

**반환:**  
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

모양이 회전된 경우 반사가 모양과 함께 회전해야 하는지 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

수평 스케일 팩터를 지정합니다. 음수 스케일은 뒤집기를 발생시킵니다. (퍼센트) 읽기/쓰기 double.

**반환:**  
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

수평 스케일 팩터를 지정합니다. 음수 스케일은 뒤집기를 발생시킵니다. (퍼센트) 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

수직 스케일 팩터를 지정합니다. 음수 스케일은 뒤집기를 발생시킵니다. (퍼센트) 읽기/쓰기 double.

**반환:**  
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

수직 스케일 팩터를 지정합니다. 음수 스케일은 뒤집기를 발생시킵니다. (퍼센트) 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |