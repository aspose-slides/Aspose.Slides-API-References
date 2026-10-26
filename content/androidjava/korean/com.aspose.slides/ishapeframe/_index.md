---
title: IShapeFrame
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 모양 프레임 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ishapeframe/
---
**구현된 모든 인터페이스:**
com.aspose.slides.IGenericCloneable
```
public interface IShapeFrame extends IGenericCloneable<IShapeFrame>
```

모양 프레임의 속성을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getX()](#getX--) | 프레임의 왼쪽 위 모서리 X 좌표를 반환합니다. |
| [getY()](#getY--) | 프레임의 왼쪽 위 모서리 Y 좌표를 반환합니다. |
| [getWidth()](#getWidth--) | 프레임의 너비를 반환합니다. |
| [getHeight()](#getHeight--) | 프레임의 높이를 반환합니다. |
| [getRotation()](#getRotation--) | 프레임이 z축을 기준으로 회전한 각도(도)를 반환합니다. |
| [getCenterX()](#getCenterX--) | 프레임 중심의 X 좌표를 반환합니다. |
| [getCenterY()](#getCenterY--) | 프레임 중심의 Y 좌표를 반환합니다. |
| [getFlipH()](#getFlipH--) | 프레임이 가로로 뒤집혔는지 여부를 결정합니다. |
| [getFlipV()](#getFlipV--) | 프레임이 세로로 뒤집혔는지 여부를 결정합니다. |
| [getRectangle()](#getRectangle--) | 프레임의 좌표를 반환합니다. |
### getX() {#getX--}
```
public abstract float getX()
```

프레임의 왼쪽 위 모서리 X 좌표를 반환합니다. 읽기 전용 float.

**Returns:**
float
### getY() {#getY--}
```
public abstract float getY()
```

프레임의 왼쪽 위 모서리 Y 좌표를 반환합니다. 읽기 전용 float.

**Returns:**
float
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

프레임의 너비를 반환합니다. 읽기 전용 float.

**Returns:**
float
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

프레임의 높이를 반환합니다. 읽기 전용 float.

**Returns:**
float
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

프레임이 z축을 기준으로 회전한 각도(도)를 반환합니다. 양수 값은 시계 방향 회전을, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기 전용 float.

**Returns:**
float
### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```

프레임 중심의 X 좌표를 반환합니다. 읽기 전용 float.

**Returns:**
float
### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```

프레임 중심의 Y 좌표를 반환합니다. 읽기 전용 float.

**Returns:**
float
### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```

프레임이 가로로 뒤집혔는지 여부를 결정합니다. 읽기 전용 [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```

프레임이 세로로 뒤집혔는지 여부를 결정합니다. 읽기 전용 [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### getRectangle() {#getRectangle--}
```
public abstract RectF getRectangle()
```

프레임의 좌표를 반환합니다. 읽기 전용 android.graphics.RectF.

**Returns:**
android.graphics.RectF