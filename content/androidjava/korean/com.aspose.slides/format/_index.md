---
title: Format
second_title: Aspose.Slides for Android용 Java API 참조
description: 차트 형식 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/format/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IFormat](../../com.aspose.slides/iformat)
```
public final class Format extends PVIObject implements IFormat
```

차트 형식 속성을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFill()](#getFill--) | 차트의 채우기 스타일 속성을 반환합니다. |
| [getLine()](#getLine--) | 차트의 선 스타일 속성을 반환합니다. |
| [getEffect()](#getEffect--) | 차트에 사용되는 효과를 반환합니다. |
| [getEffect3D()](#getEffect3D--) | 차트의 3D 형식을 반환합니다. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


버전. 읽기 전용 long.

**Returns:**
long
### getFill() {#getFill--}
```
public final IFillFormat getFill()
```


차트의 채우기 스타일 속성을 반환합니다. 읽기 전용 [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getLine() {#getLine--}
```
public final ILineFormat getLine()
```


차트의 선 스타일 속성을 반환합니다. 읽기 전용 [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffect() {#getEffect--}
```
public final IEffectFormat getEffect()
```


차트에 사용되는 효과를 반환합니다. 읽기 전용 [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Returns:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getEffect3D() {#getEffect3D--}
```
public final IThreeDFormat getEffect3D()
```


차트의 3D 형식을 반환합니다. 읽기 전용 [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Returns:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)