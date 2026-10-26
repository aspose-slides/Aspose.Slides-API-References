---
title: IFillFormatEffectiveData
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 유효한 채우기 서식 속성을 포함하는 불변 객체입니다.
type: docs
url: /ko/com.aspose.slides/ifillformateffectivedata/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

유효한 채우기 서식 속성을 포함하는 불변 객체입니다.

--------------------

이 인터페이스는 [IFillFormat](../../com.aspose.slides/ifillformat) 인터페이스와 함께 사용되어 상속이 적용된 유효한 서식 값을 반환합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFillType()](#getFillType--) | 채우기 유형을 반환합니다. |
| [getSolidFillColor()](#getSolidFillColor--) | 채우기 색상을 반환합니다. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | 색 구성표에 정의된 채우기 색상을 가져옵니다. |
| [getGradientFormat()](#getGradientFormat--) | 그라디언트 채우기 형식을 반환합니다. |
| [getPatternFormat()](#getPatternFormat--) | 패턴 채우기 형식을 반환합니다. |
| [getPictureFillFormat()](#getPictureFillFormat--) | 그림 채우기 형식을 반환합니다. |
| [getRotateWithShape()](#getRotateWithShape--) | 채우기를 도형과 함께 회전시켜야 하는지 여부를 결정합니다. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


채우기 유형을 반환합니다. 읽기 전용 [FillType](../../com.aspose.slides/filltype).

**반환:** 
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


채우기 색상을 반환합니다. 읽기 전용 java.lang.Integer.

**반환:** 
java.lang.Integer
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```


색 구성표에 정의된 채우기 색상을 가져옵니다. [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) 값은 SolidFillColor (\#getSolidFillColor.getSolidFillColor) 가 스킴 색상이 아님을 나타냅니다. 읽기 전용 [SchemeColor](../../com.aspose.slides/schemecolor).

**반환:** 
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


그라디언트 채우기 형식을 반환합니다. 읽기 전용 [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**반환:** 
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


패턴 채우기 형식을 반환합니다. 읽기 전용 [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**반환:** 
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```


그림 채우기 형식을 반환합니다. 읽기 전용 [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**반환:** 
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


채우기를 도형과 함께 회전시켜야 하는지 여부를 결정합니다. 읽기 전용 boolean.

**반환:** 
boolean