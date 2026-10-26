---
title: IInnerShadow
second_title: Java API를 통한 Android용 Aspose.Slides 참고 문서
description: 내부 그림자 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iinnershadow/
---
**전체 구현된 인터페이스:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IInnerShadow extends IImageTransformOperation, IAccessiblePVIObject<IInnerShadowEffectiveData>
```

내부 그림자 효과를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | 블러 반경. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | 블러 반경. |
| [getDirection()](#getDirection--) | 그림자 방향. |
| [setDirection(float value)](#setDirection-float-) | 그림자 방향. |
| [getDistance()](#getDistance--) | 그림자 거리. |
| [setDistance(double value)](#setDistance-double-) | 그림자 거리. |
| [getShadowColor()](#getShadowColor--) | 그림자 색상. |
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

그림자 방향. 읽기/쓰기 float.

**반환:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

그림자 방향. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

그림자 거리. 읽기/쓰기 double.

**반환:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

그림자 거리. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

그림자 색상. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)