---
title: IFillFormat
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 채우기 서식 옵션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ifillformat/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

채우기 서식 옵션을 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [getFillType()](#getFillType--) | 채우기 유형을 반환하거나 설정합니다. |
| [setFillType(byte value)](#setFillType-byte-) | 채우기 유형을 반환하거나 설정합니다. |
| [getSolidFillColor()](#getSolidFillColor--) | 채우기 색상을 반환합니다. |
| [getGradientFormat()](#getGradientFormat--) | 그라디언트 채우기 형식을 반환합니다. |
| [getPatternFormat()](#getPatternFormat--) | 패턴 채우기 형식을 반환합니다. |
| [getPictureFillFormat()](#getPictureFillFormat--) | 그림 채우기 형식을 반환합니다. |
| [getRotateWithShape()](#getRotateWithShape--) | 채우기가 도형과 함께 회전해야 하는지 여부를 결정합니다. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | 채우기가 도형과 함께 회전해야 하는지 여부를 결정합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 유효한 채우기 서식 데이터를 가져옵니다. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

채우기 유형을 반환하거나 설정합니다. 읽기/쓰기 [FillType](../../com.aspose.slides/filltype).

**반환:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

채우기 유형을 반환하거나 설정합니다. 읽기/쓰기 [FillType](../../com.aspose.slides/filltype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

채우기 색상을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

그라디언트 채우기 형식을 반환합니다. 읽기 전용 [IGradientFormat](../../com.aspose.slides/igradientformat).

**반환:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

패턴 채우기 형식을 반환합니다. 읽기 전용 [IPatternFormat](../../com.aspose.slides/ipatternformat).

**반환:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```

그림 채우기 형식을 반환합니다. 읽기 전용 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**반환:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

채우기가 도형과 함께 회전해야 하는지 여부를 결정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

채우기가 도형과 함께 회전해야 하는지 여부를 결정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```

상속이 적용된 유효한 채우기 서식 데이터를 가져옵니다.

**반환:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - 하나의 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).