---
title: IColorEffect
second_title: Aspose.Slides for Android용 Java API 참조
description: 애니메이션 동작에 대한 색 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icoloreffect/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IColorEffect extends IBehavior
```

애니메이션 동작에 대한 색 효과를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFrom()](#getFrom--) | 이 값은 동작의 시작 색을 지정하는 데 사용됩니다. |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | 이 값은 동작의 시작 색을 지정하는 데 사용됩니다. |
| [getTo()](#getTo--) | 애니메이션 색상 변경에 대한 결과 색을 설명합니다. |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | 애니메이션 색상 변경에 대한 결과 색을 설명합니다. |
| [getBy()](#getBy--) | 색상 애니메이션에 대한 상대 오프셋 값을 설명합니다. |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | 색상 애니메이션에 대한 상대 오프셋 값을 설명합니다. |
| [getColorSpace()](#getColorSpace--) | 동작의 색 공간을 나타냅니다. |
| [setColorSpace(int value)](#setColorSpace-int-) | 동작의 색 공간을 나타냅니다. |
| [getDirection()](#getDirection--) | 색상 휠을 따라 색조를 순환시킬 방향을 지정합니다. |
| [setDirection(int value)](#setDirection-int-) | 색상 휠을 따라 색조를 순환시킬 방향을 지정합니다. |
### getFrom() {#getFrom--}
```
public abstract IColorFormat getFrom()
```

이 값은 동작의 시작 색을 지정하는 데 사용됩니다. 읽기/쓰기 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public abstract void setFrom(IColorFormat value)
```

이 값은 동작의 시작 색을 지정하는 데 사용됩니다. 읽기/쓰기 [IColorFormat](../../com.aspose.slides/icolorformat).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getTo() {#getTo--}
```
public abstract IColorFormat getTo()
```

애니메이션 색상 변경에 대한 결과 색을 설명합니다. 읽기/쓰기 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public abstract void setTo(IColorFormat value)
```

애니메이션 색상 변경에 대한 결과 색을 설명합니다. 읽기/쓰기 [IColorFormat](../../com.aspose.slides/icolorformat).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getBy() {#getBy--}
```
public abstract IColorOffset getBy()
```

색상 애니메이션에 대한 상대 오프셋 값을 설명합니다. 읽기/쓰기 [IColorOffset](../../com.aspose.slides/icoloroffset).

**반환:**
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public abstract void setBy(IColorOffset value)
```

색상 애니메이션에 대한 상대 오프셋 값을 설명합니다. 읽기/쓰기 [IColorOffset](../../com.aspose.slides/icoloroffset).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |

### getColorSpace() {#getColorSpace--}
```
public abstract int getColorSpace()
```

동작의 색 공간을 나타냅니다. 읽기/쓰기 [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**반환:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public abstract void setColorSpace(int value)
```

동작의 색 공간을 나타냅니다. 읽기/쓰기 [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

색상 휠을 따라 색조를 순환시킬 방향을 지정합니다. 읽기/쓰기 [ColorDirection](../../com.aspose.slides/colordirection).

**반환:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

색상 휠을 따라 색조를 순환시킬 방향을 지정합니다. 읽기/쓰기 [ColorDirection](../../com.aspose.slides/colordirection).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |