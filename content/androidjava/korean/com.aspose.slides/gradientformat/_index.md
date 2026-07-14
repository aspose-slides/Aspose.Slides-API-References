---
title: GradientFormat
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 그라디언트 형식을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/gradientformat/
---
**상속:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IGradientFormat](../../com.aspose.slides/igradientformat)
```
public final class GradientFormat extends PVIObject implements IGradientFormat
```

그라디언트 형식을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTileFlip()](#getTileFlip--) | 그라디언트의 플리핑 모드를 반환하거나 설정합니다. |
| [setTileFlip(int value)](#setTileFlip-int-) | 그라디언트의 플리핑 모드를 반환하거나 설정합니다. |
| [getGradientDirection()](#getGradientDirection--) | 그라디언트의 스타일을 반환하거나 설정합니다. |
| [setGradientDirection(int value)](#setGradientDirection-int-) | 그라디언트의 스타일을 반환하거나 설정합니다. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | 그라디언트의 각도를 반환하거나 설정합니다. |
| [setLinearGradientAngle(float value)](#setLinearGradientAngle-float-) | 그라디언트의 각도를 반환하거나 설정합니다. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | 그라디언트가 스케일되는지 여부를 결정합니다. |
| [setLinearGradientScaled(byte value)](#setLinearGradientScaled-byte-) | 그라디언트가 스케일되는지 여부를 결정합니다. |
| [getGradientShape()](#getGradientShape--) | 그라디언트의 모양을 반환하거나 설정합니다. |
| [setGradientShape(byte value)](#setGradientShape-byte-) | 그라디언트의 모양을 반환하거나 설정합니다. |
| [getGradientStops()](#getGradientStops--) | 그라디언트 정지점들의 컬렉션을 반환합니다. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. 읽기 전용 long.

**반환:**
long
### getTileFlip() {#getTileFlip--}
```
public final int getTileFlip()
```

그라디언트의 플리핑 모드를 반환하거나 설정합니다. 읽기/쓰기 [TileFlip](../../com.aspose.slides/tileflip).

**반환:**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public final void setTileFlip(int value)
```

그라디언트의 플리핑 모드를 반환하거나 설정합니다. 읽기/쓰기 [TileFlip](../../com.aspose.slides/tileflip).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getGradientDirection() {#getGradientDirection--}
```
public final int getGradientDirection()
```

그라디언트의 스타일을 반환하거나 설정합니다. 읽기/쓰기 [GradientDirection](../../com.aspose.slides/gradientdirection).

**반환:**
int
### setGradientDirection(int value) {#setGradientDirection-int-}
```
public final void setGradientDirection(int value)
```

그라디언트의 스타일을 반환하거나 설정합니다. 읽기/쓰기 [GradientDirection](../../com.aspose.slides/gradientdirection).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public final float getLinearGradientAngle()
```

그라디언트의 각도를 반환하거나 설정합니다. 읽기/쓰기 float.

**반환:**
float
### setLinearGradientAngle(float value) {#setLinearGradientAngle-float-}
```
public final void setLinearGradientAngle(float value)
```

그라디언트의 각도를 반환하거나 설정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public final byte getLinearGradientScaled()
```

그라디언트가 스케일되는지 여부를 결정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**
byte
### setLinearGradientScaled(byte value) {#setLinearGradientScaled-byte-}
```
public final void setLinearGradientScaled(byte value)
```

그라디언트가 스케일되는지 여부를 결정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getGradientShape() {#getGradientShape--}
```
public final byte getGradientShape()
```

그라디언트의 모양을 반환하거나 설정합니다. 읽기/쓰기 [GradientShape](../../com.aspose.slides/gradientshape).

**반환:**
byte
### setGradientShape(byte value) {#setGradientShape-byte-}
```
public final void setGradientShape(byte value)
```

그라디언트의 모양을 반환하거나 설정합니다. 읽기/쓰기 [GradientShape](../../com.aspose.slides/gradientshape).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getGradientStops() {#getGradientStops--}
```
public final IGradientStopCollection getGradientStops()
```

그라디언트 정지점들의 컬렉션을 반환합니다. 읽기 전용 [IGradientStopCollection](../../com.aspose.slides/igradientstopcollection).

**반환:**
[IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)