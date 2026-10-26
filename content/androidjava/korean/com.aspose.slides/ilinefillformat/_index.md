---
title: ILineFillFormat
second_title: Aspose.Slides for Android용 Java API 참조
description: 선 채우기 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ilinefillformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

선 채우기 속성을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFillType()](#getFillType--) | 채우기 유형을 반환하거나 설정합니다. |
| [setFillType(byte value)](#setFillType-byte-) | 채우기 유형을 반환하거나 설정합니다. |
| [getSolidFillColor()](#getSolidFillColor--) | 단색 채우기의 색상을 반환합니다. |
| [getGradientFormat()](#getGradientFormat--) | 그라디언트 채우기 형식을 반환합니다. |
| [getPatternFormat()](#getPatternFormat--) | 패턴 채우기 형식을 반환합니다. |
| [getRotateWithShape()](#getRotateWithShape--) | 채우기가 도형과 함께 회전해야 하는지 여부를 결정합니다. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | 채우기가 도형과 함께 회전해야 하는지 여부를 결정합니다. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


채우기 유형을 반환하거나 설정합니다. 읽기/쓰기 [FillType](../../com.aspose.slides/filltype).

**반환값:**
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


단색 채우기의 색상을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환값:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


그라디언트 채우기 형식을 반환합니다. 읽기 전용 [IGradientFormat](../../com.aspose.slides/igradientformat).

**반환값:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


패턴 채우기 형식을 반환합니다. 읽기 전용 [IPatternFormat](../../com.aspose.slides/ipatternformat).

**반환값:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


채우기가 도형과 함께 회전해야 하는지 여부를 결정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환값:**
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