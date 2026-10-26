---
title: LineFillFormat
second_title: Aspose.Slides for Java API 레퍼런스
description: 선 채우기 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/linefillformat/
---
**상속:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**구현된 모든 인터페이스:**
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

선 채우기 속성을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | 채우기 유형을 반환하거나 설정합니다. |
| [setFillType(byte value)](#setFillType-byte-) | 채우기 유형을 반환하거나 설정합니다. |
| [getRotateWithShape()](#getRotateWithShape--) | 채우기를 도형과 함께 회전시켜야 하는지 여부를 결정합니다. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | 채우기를 도형과 함께 회전시켜야 하는지 여부를 결정합니다. |
| [getSolidFillColor()](#getSolidFillColor--) | 단색 채우기의 색상을 반환합니다. |
| [getGradientFormat()](#getGradientFormat--) | 그라디언트 채우기 형식을 반환합니다. |
| [getPatternFormat()](#getPatternFormat--) | 패턴 채우기 형식을 반환합니다. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


버전. 읽기 전용 long.

**반환:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```


채우기 유형을 반환하거나 설정합니다. 읽기/쓰기 [FillType](../../com.aspose.slides/filltype).

**반환:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```


채우기 유형을 반환하거나 설정합니다. 읽기/쓰기 [FillType](../../com.aspose.slides/filltype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```


채우기를 도형과 함께 회전시켜야 하는지 여부를 결정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```


채우기를 도형과 함께 회전시켜야 하는지 여부를 결정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```


단색 채우기의 색상을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```


그라디언트 채우기 형식을 반환합니다. 읽기 전용 [IGradientFormat](../../com.aspose.slides/igradientformat).

**반환:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```


패턴 채우기 형식을 반환합니다. 읽기 전용 [IPatternFormat](../../com.aspose.slides/ipatternformat).

**반환:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)