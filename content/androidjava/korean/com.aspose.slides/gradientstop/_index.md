---
title: GradientStop
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 그라디언트 형식을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/gradientstop/
---
**상속:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**구현된 모든 인터페이스:**
[com.aspose.slides.IGradientStop](../../com.aspose.slides/igradientstop)
```
public final class GradientStop extends PVIObject implements IGradientStop
```

그라디언트 형식을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | 그라디언트 스톱의 위치(0..1)를 반환하거나 설정합니다. |
| [setPosition(float value)](#setPosition-float-) | 그라디언트 스톱의 위치(0..1)를 반환하거나 설정합니다. |
| [getColor()](#getColor--) | 그라디언트 스톱의 색상을 반환합니다. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환:**
long
### getPosition() {#getPosition--}
```
public final float getPosition()
```

그라디언트 스톱의 위치(0..1)를 반환하거나 설정합니다. 읽기/쓰기 float .

**반환:**
float
### setPosition(float value) {#setPosition-float-}
```
public final void setPosition(float value)
```

그라디언트 스톱의 위치(0..1)를 반환하거나 설정합니다. 읽기/쓰기 float .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

그라디언트 스톱의 색상을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)