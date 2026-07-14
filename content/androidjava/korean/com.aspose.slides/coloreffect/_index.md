---
title: ColorEffect
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 애니메이션 동작에 대한 색상 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/coloreffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**All Implemented Interfaces:**
[com.aspose.slides.IColorEffect](../../com.aspose.slides/icoloreffect)
```
public class ColorEffect extends Behavior implements IColorEffect
```

애니메이션 동작에 대한 색상 효과를 나타냅니다.
## 생성자

| Constructor | Description |
| --- | --- |
| [ColorEffect()](#ColorEffect--) | 새 인스턴스를 생성합니다. |
## 메서드

| Method | Description |
| --- | --- |
| [getFrom()](#getFrom--) | 이 값은 동작의 시작 색상을 지정하는 데 사용됩니다. |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | 이 값은 동작의 시작 색상을 지정하는 데 사용됩니다. |
| [getTo()](#getTo--) | 애니메이션 색상 변경에 대한 결과 색상을 설명합니다. |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | 애니메이션 색상 변경에 대한 결과 색상을 설명합니다. |
| [getBy()](#getBy--) | 색상 애니메이션에 대한 상대 오프셋 값을 설명합니다. |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | 색상 애니메이션에 대한 상대 오프셋 값을 설명합니다. |
| [getColorSpace()](#getColorSpace--) | 동작의 색상 공간을 나타냅니다. |
| [setColorSpace(int value)](#setColorSpace-int-) | 동작의 색상 공간을 나타냅니다. |
| [getDirection()](#getDirection--) | 색상 휠을 따라 색조를 순환시키는 방향을 지정합니다. |
| [setDirection(int value)](#setDirection-int-) | 색상 휠을 따라 색조를 순환시키는 방향을 지정합니다. |
### ColorEffect() {#ColorEffect--}
```
public ColorEffect()
```


새 인스턴스를 생성합니다.

### getFrom() {#getFrom--}
```
public final IColorFormat getFrom()
```


이 값은 동작의 시작 색상을 지정하는 데 사용됩니다. 읽기/쓰기 [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public final void setFrom(IColorFormat value)
```


이 값은 동작의 시작 색상을 지정하는 데 사용됩니다. 읽기/쓰기 [IColorFormat](../../com.aspose.slides/icolorformat).

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getTo() {#getTo--}
```
public final IColorFormat getTo()
```


애니메이션 색상 변경에 대한 결과 색상을 설명합니다. 읽기/쓰기 [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public final void setTo(IColorFormat value)
```


애니메이션 색상 변경에 대한 결과 색상을 설명합니다. 읽기/쓰기 [IColorFormat](../../com.aspose.slides/icolorformat).

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getBy() {#getBy--}
```
public final IColorOffset getBy()
```


색상 애니메이션에 대한 상대 오프셋 값을 설명합니다. 읽기/쓰기 [IColorOffset](../../com.aspose.slides/icoloroffset).

**Returns:**
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public final void setBy(IColorOffset value)
```


색상 애니메이션에 대한 상대 오프셋 값을 설명합니다. 읽기/쓰기 [IColorOffset](../../com.aspose.slides/icoloroffset).

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |

### getColorSpace() {#getColorSpace--}
```
public final int getColorSpace()
```


동작의 색상 공간을 나타냅니다. 읽기/쓰기 [ColorSpace](../../com.aspose.slides/colorspace).

**Returns:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public final void setColorSpace(int value)
```


동작의 색상 공간을 나타냅니다. 읽기/쓰기 [ColorSpace](../../com.aspose.slides/colorspace).

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDirection() {#getDirection--}
```
public final int getDirection()
```


색상 휠을 따라 색조를 순환시키는 방향을 지정합니다. 읽기/쓰기 [ColorDirection](../../com.aspose.slides/colordirection).

**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


색상 휠을 따라 색조를 순환시키는 방향을 지정합니다. 읽기/쓰기 [ColorDirection](../../com.aspose.slides/colordirection).

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |