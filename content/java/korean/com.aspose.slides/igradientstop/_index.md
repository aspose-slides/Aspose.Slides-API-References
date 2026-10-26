---
title: IGradientStop
second_title: Aspose.Slides for Java API Reference
description: 그라디언트 형식을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/igradientstop/
---```
public interface IGradientStop
```

그라디언트 형식을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPosition()](#getPosition--) | 그라디언트 정지점의 위치(0..1)를 반환하거나 설정합니다. |
| [setPosition(float value)](#setPosition-float-) | 그라디언트 정지점의 위치(0..1)를 반환하거나 설정합니다. |
| [getColor()](#getColor--) | 그라디언트 정지점의 색상을 반환합니다. |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```


그라디언트 정지점의 위치(0..1)를 반환하거나 설정합니다. 읽기/쓰기 float.

**반환:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```


그라디언트 정지점의 위치(0..1)를 반환하거나 설정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


그라디언트 정지점의 색상을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)