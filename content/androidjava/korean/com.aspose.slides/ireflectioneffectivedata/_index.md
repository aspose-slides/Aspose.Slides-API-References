---
title: IReflectionEffectiveData
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: Reflection 효과를 나타내는 불변 객체.
type: docs
url: /ko/com.aspose.slides/ireflectioneffectivedata/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IReflectionEffectiveData extends IEffectEffectiveData
```

Immutable object which represents a Reflection effect.
## Methods

| Method | Description |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | 시작 알파 값의 시작 위치(알파 그라디언트 램프를 따라, 백분율)를 지정합니다. |
| [getEndPosAlpha()](#getEndPosAlpha--) | 끝 알파 값의 끝 위치(알파 그라디언트 램프를 따라, 백분율)를 지정합니다. |
| [getFadeDirection()](#getFadeDirection--) | 반사를 오프셋할 방향을 지정합니다. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | 시작 반사 불투명도. |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | 끝 반사 불투명도. |
| [getBlurRadius()](#getBlurRadius--) | 흐림 반경. |
| [getDirection()](#getDirection--) | 반사의 방향. |
| [getDistance()](#getDistance--) | 반사의 거리. |
| [getRectangleAlign()](#getRectangleAlign--) | 사각형 정렬. |
| [getSkewHorizontal()](#getSkewHorizontal--) | 수평 기울기 각도를 지정합니다. |
| [getSkewVertical()](#getSkewVertical--) | 수직 기울기 각도를 지정합니다. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | 도형이 회전될 경우 반사도 도형과 함께 회전하도록 지정합니다. |
| [getScaleHorizontal()](#getScaleHorizontal--) | 수평 스케일링 팩터를 지정합니다. 음수 스케일링은 뒤집기를 발생시킵니다. |
| [getScaleVertical()](#getScaleVertical--) | 수직 스케일링 팩터를 지정합니다. 음수 스케일링은 뒤집기를 발생시킵니다. |
### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```


시작 알파 값의 시작 위치(알파 그라디언트 램프를 따라, 백분율)를 지정합니다. 읽기 전용 float.

**반환값:**
float
### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```


끝 알파 값의 끝 위치(알파 그라디언트 램프를 따라, 백분율)를 지정합니다. 읽기 전용 float.

**반환값:**
float
### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```


반사를 오프셋할 방향을 지정합니다(각도). 읽기 전용 float.

**반환값:**
float
### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```


시작 반사 불투명도(백분율)를 지정합니다. 읽기 전용 float.

**반환값:**
float
### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```


끝 반사 불투명도(백분율)를 지정합니다. 읽기 전용 float.

**반환값:**
float
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```


흐림 반경을 지정합니다. 읽기 전용 double.

**반환값:**
double
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


반사의 방향을 지정합니다. 읽기 전용 float.

**반환값:**
float
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


반사의 거리를 지정합니다. 읽기 전용 double.

**반환값:**
double
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```


사각형 정렬을 지정합니다. 읽기 전용 [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**반환값:**
byte
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```


수평 기울기 각도를 지정합니다. 읽기 전용 double.

**반환값:**
double
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```


수직 기울기 각도를 지정합니다. 읽기 전용 double.

**반환값:**
double
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```


도형이 회전될 경우 반사도 도형과 함께 회전하도록 지정합니다. 읽기 전용 boolean.

**반환값:**
boolean
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```


수평 스케일링 팩터를 지정합니다(백분율). 음수 스케일링은 뒤집기를 발생시킵니다. 읽기 전용 double.

**반환값:**
double
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```


수직 스케일링 팩터를 지정합니다(백분율). 음수 스케일링은 뒤집기를 발생시킵니다. 읽기 전용 double.

**반환값:**
double