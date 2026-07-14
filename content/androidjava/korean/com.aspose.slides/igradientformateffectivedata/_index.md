---
title: IGradientFormatEffectiveData
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 효과적인 그라디언트 채우기 속성을 포함하는 불변 객체입니다.
type: docs
url: /ko/com.aspose.slides/igradientformateffectivedata/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

효과적인 그라디언트 채우기 속성을 포함하는 불변 객체.

--------------------

이 인터페이스는 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)와 [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)의 일부로 사용됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | 그라디언트의 뒤집기 모드를 반환합니다. |
| [getGradientDirection()](#getGradientDirection--) | 그라디언트의 스타일을 반환합니다. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | 그라디언트의 각도를 반환합니다. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | 그라디언트가 스케일링되는지 여부를 결정합니다. |
| [getGradientShape()](#getGradientShape--) | 그라디언트의 모양을 반환합니다. |
| [getGradientStops()](#getGradientStops--) | 그라디언트 정지점들의 컬렉션을 반환합니다. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

그라디언트의 뒤집기 모드를 반환합니다. 읽기 전용 [TileFlip](../../com.aspose.slides/tileflip).

**반환:**
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

그라디언트의 스타일을 반환합니다. 읽기 전용 [GradientDirection](../../com.aspose.slides/gradientdirection).

**반환:**
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

그라디언트의 각도를 반환합니다. 읽기 전용 float.

**반환:**
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```

그라디언트가 스케일링되는지 여부를 결정합니다. 읽기 전용 boolean.

**반환:**
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

그라디언트의 모양을 반환합니다. 읽기 전용 [GradientShape](../../com.aspose.slides/gradientshape).

**반환:**
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```

그라디언트 정지점들의 컬렉션을 반환합니다. 읽기 전용 [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata).

**반환:**
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)