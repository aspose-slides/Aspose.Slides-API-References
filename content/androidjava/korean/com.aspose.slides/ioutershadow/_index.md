---
title: IOuterShadow
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 외부 그림자 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ioutershadow/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

외부 그림자 효과를 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | 블러 반경, 포인트 단위. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | 블러 반경, 포인트 단위. |
| [getDirection()](#getDirection--) | 그림자 방향, 도 단위. |
| [setDirection(float value)](#setDirection-float-) | 그림자 방향, 도 단위. |
| [getDistance()](#getDistance--) | 그림자와 객체 사이 거리, 포인트 단위. |
| [setDistance(double value)](#setDistance-double-) | 그림자와 객체 사이 거리, 포인트 단위. |
| [getShadowColor()](#getShadowColor--) | 그림자 색상. |
| [getRectangleAlign()](#getRectangleAlign--) | 사각형 정렬. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | 사각형 정렬. |
| [getSkewHorizontal()](#getSkewHorizontal--) | 수평 기울기 각도, 도 단위. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | 수평 기울기 각도, 도 단위. |
| [getSkewVertical()](#getSkewVertical--) | 수직 기울기 각도, 도 단위. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | 수직 기울기 각도, 도 단위. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | 그림자 회전이 도형과 함께 회전하는지 여부를 나타냅니다. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | 그림자 회전이 도형과 함께 회전하는지 여부를 나타냅니다. |
| [getScaleHorizontal()](#getScaleHorizontal--) | 수평 스케일링 비율, 원본 크기의 백분율. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | 수평 스케일링 비율, 원본 크기의 백분율. |
| [getScaleVertical()](#getScaleVertical--) | 수직 스케일링 비율, 원본 크기의 백분율. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | 수직 스케일링 비율, 원본 크기의 백분율. |

### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

블러 반경, 포인트 단위. 기본값 - 0 pt. 읽기/쓰기 double.

**반환:**
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

블러 반경, 포인트 단위. 기본값 - 0 pt. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

그림자 방향, 도 단위. 기본값 - 0 ° (좌→우). 읽기/쓰기 float.

**반환:**
float

### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

그림자 방향, 도 단위. 기본값 - 0 ° (좌→우). 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

그림자와 객체 사이 거리, 포인트 단위. 기본값 - 0 pt. 읽기/쓰기 double.

**반환:**
double

### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

그림자와 객체 사이 거리, 포인트 단위. 기본값 - 0 pt. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

그림자 색상. 기본값 - 자동 검정(테마 의존). 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

사각형 정렬. 기본값 - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). 읽기/쓰기 [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**반환:**
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

사각형 정렬. 기본값 - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). 읽기/쓰기 [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

수평 기울기 각도, 도 단위. 기본값 - 0 °. 읽기/쓰기 double.

**반환:**
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

수평 기울기 각도, 도 단위. 기본값 - 0 °. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

수직 기울기 각도, 도 단위. 기본값 - 0 °. 읽기/쓰기 double.

**반환:**
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

수직 기울기 각도, 도 단위. 기본값 - 0 °. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

그림자 회전이 도형과 함께 회전하는지 여부를 나타냅니다. 기본값 - true. 읽기/쓰기 boolean.

**반환:**
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

그림자 회전이 도형과 함께 회전하는지 여부를 나타냅니다. 기본값 - true. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

수평 스케일링 비율, 원본 크기의 백분율. 음수 스케일링은 뒤집기를 일으킵니다. 기본값 - 100 %. 읽기/쓰기 double.

**반환:**
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

수평 스케일링 비율, 원본 크기의 백분율. 음수 스케일링은 뒤집기를 일으킵니다. 기본값 - 100 %. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

수직 스케일링 비율, 원본 크기의 백분율. 음수 스케일링은 뒤집기를 일으킵니다. 기본값 - 100 %. 읽기/쓰기 double.

**반환:**
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

수직 스케일링 비율, 원본 크기의 백분율. 음수 스케일링은 뒤집기를 일으킵니다. 기본값 - 100 %. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |