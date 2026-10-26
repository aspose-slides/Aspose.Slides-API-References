---
title: IOuterShadowEffectiveData
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 외부 그림자 효과를 나타내는 불변 객체입니다.
type: docs
url: /ko/com.aspose.slides/ioutershadoweffectivedata/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IOuterShadowEffectiveData extends IEffectEffectiveData
```

외부 그림자 효과를 나타내는 불변 객체입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | 흐림 반경. |
| [getDirection()](#getDirection--) | 그림자의 방향. |
| [getDistance()](#getDistance--) | 그림자의 거리. |
| [getShadowColor()](#getShadowColor--) | 그림자의 색상. |
| [getRectangleAlign()](#getRectangleAlign--) | 사각형 정렬. |
| [getSkewHorizontal()](#getSkewHorizontal--) | 수평 왜곡 각도(도)를 지정합니다. |
| [getSkewVertical()](#getSkewVertical--) | 수직 왜곡 각도(도)를 지정합니다. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | 도형이 회전할 경우 그림자도 함께 회전해야 하는지 지정합니다. |
| [getScaleHorizontal()](#getScaleHorizontal--) | 수평 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 초래합니다. |
| [getScaleVertical()](#getScaleVertical--) | 수직 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 초래합니다. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

흐림 반경. 읽기 전용 double.

**반환:**
double
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

그림자의 방향. 읽기 전용 float.

**반환:**
float
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

그림자의 거리. 읽기 전용 double.

**반환:**
double
### getShadowColor() {#getShadowColor--}
```
public abstract Integer getShadowColor()
```

그림자의 색상. 읽기 전용 java.lang.Integer.

**반환:**
java.lang.Integer
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

사각형 정렬. 읽기 전용 [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**반환:**
byte
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

수평 왜곡 각도(도)를 지정합니다. 읽기 전용 double.

**반환:**
double
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

수직 왜곡 각도(도)를 지정합니다. 읽기 전용 double.

**반환:**
double
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

도형이 회전할 경우 그림자도 함께 회전해야 하는지 지정합니다. 읽기 전용 boolean.

**반환:**
boolean
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

수평 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 초래합니다. 읽기 전용 double.

**반환:**
double
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

수직 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 초래합니다. 읽기 전용 double.

**반환:**
double