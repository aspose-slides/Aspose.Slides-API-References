---
title: LineFillFormat
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 선 채우기 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/linefillformat/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**  
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

선 채우기 속성을 나타냅니다.
## Methods

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | 채우기 유형을 반환하거나 설정합니다. |
| [setFillType(byte value)](#setFillType-byte-) | 채우기 유형을 반환하거나 설정합니다. |
| [getRotateWithShape()](#getRotateWithShape--) | 채우기를 도형과 함께 회전시켜야 하는지 결정합니다. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | 채우기를 도형과 함께 회전시켜야 하는지 결정합니다. |
| [getSolidFillColor()](#getSolidFillColor--) | 단색 채우기의 색상을 반환합니다. |
| [getGradientFormat()](#getGradientFormat--) | 그라디언트 채우기 형식을 반환합니다. |
| [getPatternFormat()](#getPatternFormat--) | 패턴 채우기 형식을 반환합니다. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**Returns:**  
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```

채우기 유형을 반환하거나 설정합니다. 읽기/쓰기 [FillType](../../com.aspose.slides/filltype).

**Returns:**  
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

채우기 유형을 반환하거나 설정합니다. 읽기/쓰기 [FillType](../../com.aspose.slides/filltype).

**Parameters:**  
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

채우기를 도형과 함께 회전시켜야 하는지 결정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**  
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

채우기를 도형과 함께 회전시켜야 하는지 결정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**  
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

단색 채우기의 색상을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

그라디언트 채우기 형식을 반환합니다. 읽기 전용 [IGradientFormat](../../com.aspose.slides/igradientformat).

**Returns:**  
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

패턴 채우기 형식을 반환합니다. 읽기 전용 [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Returns:**  
[IPatternFormat](../../com.aspose.slides/ipatternformat)