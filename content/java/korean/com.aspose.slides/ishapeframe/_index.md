---
title: IShapeFrame
second_title: Aspose.Slides for Java API 참조
description: 쉐이프 프레임의 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ishapeframe/
---
**모든 구현된 인터페이스:**
com.aspose.slides.IGenericCloneable
```
public interface IShapeFrame extends IGenericCloneable<IShapeFrame>
```

쉐이프 프레임의 속성을 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [getX()](#getX--) | 프레임의 왼쪽 위 모서리의 X 좌표를 반환합니다. |
| [getY()](#getY--) | 프레임의 왼쪽 위 모서리의 Y 좌표를 반환합니다. |
| [getWidth()](#getWidth--) | 프레임의 너비를 반환합니다. |
| [getHeight()](#getHeight--) | 프레임의 높이를 반환합니다. |
| [getRotation()](#getRotation--) | 프레임이 z축을 중심으로 회전된 각도를 반환합니다. |
| [getCenterX()](#getCenterX--) | 프레임 중심의 X 좌표를 반환합니다. |
| [getCenterY()](#getCenterY--) | 프레임 중심의 Y 좌표를 반환합니다. |
| [getFlipH()](#getFlipH--) | 프레임이 수평으로 뒤집혔는지 확인합니다. |
| [getFlipV()](#getFlipV--) | 프레임이 수직으로 뒤집혔는지 확인합니다. |
| [getRectangle()](#getRectangle--) | 프레임의 좌표를 반환합니다. |
### getX() {#getX--}
```
public abstract float getX()
```

프레임의 왼쪽 위 모서리의 X 좌표를 반환합니다. 읽기 전용 float.

**반환값:**
float
### getY() {#getY--}
```
public abstract float getY()
```

프레임의 왼쪽 위 모서리의 Y 좌표를 반환합니다. 읽기 전용 float.

**반환값:**
float
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

프레임의 너비를 반환합니다. 읽기 전용 float.

**반환값:**
float
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

프레임의 높이를 반환합니다. 읽기 전용 float.

**반환값:**
float
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

프레임이 z축을 중심으로 회전된 각도를 반환합니다. 양수 값은 시계 방향 회전을 나타내고, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기 전용 float.

**반환값:**
float
### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```

프레임 중심의 X 좌표를 반환합니다. 읽기 전용 float.

**반환값:**
float
### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```

프레임 중심의 Y 좌표를 반환합니다. 읽기 전용 float.

**반환값:**
float
### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```

프레임이 수평으로 뒤집혔는지 확인합니다. 읽기 전용 [NullableBool](../../com.aspose.slides/nullablebool).

**반환값:**
byte
### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```

프레임이 수직으로 뒤집혔는지 확인합니다. 읽기 전용 [NullableBool](../../com.aspose.slides/nullablebool).

**반환값:**
byte
### getRectangle() {#getRectangle--}
```
public abstract Rectangle2D.Float getRectangle()
```

프레임의 좌표를 반환합니다. 읽기 전용 java.awt.geom.Rectangle2D.Float.

**반환값:**
java.awt.geom.Rectangle2D.Float