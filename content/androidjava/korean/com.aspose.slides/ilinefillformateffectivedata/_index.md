---
title: ILineFillFormatEffectiveData
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 효과적인 라인 채우기 속성을 포함하는 불변 객체.
type: docs
url: /ko/com.aspose.slides/ilinefillformateffectivedata/
---
**전체 구현된 인터페이스:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

효과적인 라인 채우기 속성을 포함하는 불변 객체.

--------------------

이 인터페이스는 [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)의 일부로 사용됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFillType()](#getFillType--) | 채우기 유형을 반환합니다. |
| [getSolidFillColor()](#getSolidFillColor--) | 고체 채우기의 색상을 반환합니다. |
| [getGradientFormat()](#getGradientFormat--) | 그라디언트 채우기 형식을 반환합니다. |
| [getPatternFormat()](#getPatternFormat--) | 패턴 채우기 형식을 반환합니다. |
| [getRotateWithShape()](#getRotateWithShape--) | 채우기가 도형과 함께 회전되어야 하는지 여부를 결정합니다. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

채우기 유형을 반환합니다. 읽기 전용 [FillType](../../com.aspose.slides/filltype).

**반환값:**
byte

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```

고체 채우기의 색상을 반환합니다. 읽기 전용 java.lang.Integer.

**반환값:**
java.lang.Integer

### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

그라디언트 채우기 형식을 반환합니다. 읽기 전용 [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**반환값:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)

### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

패턴 채우기 형식을 반환합니다. 읽기 전용 [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**반환값:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)

### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

채우기가 도형과 함께 회전되어야 하는지 여부를 결정합니다. 읽기 전용 boolean.

**반환값:**
boolean