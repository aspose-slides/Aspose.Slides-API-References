---
title: ShapeFrame
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: shape 프레임의 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/shapeframe/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

shape frame의 속성을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | new shape frame의 속성을 생성합니다. |
## 메서드

| 메서드 | 설명 |
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
| [deepClone()](#deepClone--) | 복제 |
| [cloneT()](#cloneT--) | 복제합니다. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 객체와 같은지 여부를 나타내는 값을 반환합니다. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | 이 인스턴스가 지정된 객체와 같은지 여부를 나타내는 값을 반환합니다. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```


new shape frame의 속성을 생성합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | float | 프레임의 X 좌표. |
| y | float | 프레임의 Y 좌표. |
| width | float | 프레임의 너비. |
| height | float | 프레임의 높이. |
| flipH | byte | 프레임이 수평으로 뒤집힌 경우 True. |
| flipV | byte | 프레임이 수직으로 뒤집힌 경우 True. |
| rotationAngle | float | 프레임이 회전된 각도(도). |
### getX() {#getX--}
```
public final float getX()
```


프레임의 왼쪽 위 모서리의 X 좌표를 반환합니다. 읽기 전용 float.

**반환:**
float
### getY() {#getY--}
```
public final float getY()
```


프레임의 왼쪽 위 모서리의 Y 좌표를 반환합니다. 읽기 전용 float.

**반환:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```


프레임의 너비를 반환합니다. 읽기 전용 float.

**반환:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```


프레임의 높이를 반환합니다. 읽기 전용 float.

**반환:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```


프레임이 z축을 중심으로 회전된 각도(도)를 반환합니다. 양수 값은 시계 방향 회전을 나타내며, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기 전용 float.

**반환:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```


프레임 중심의 X 좌표를 반환합니다. 읽기 전용 float.

**반환:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```


프레임 중심의 Y 좌표를 반환합니다. 읽기 전용 float.

**반환:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```


프레임이 수평으로 뒤집혔는지 확인합니다. 읽기 전용 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```


프레임이 수직으로 뒤집혔는지 확인합니다. 읽기 전용 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**
byte
### getRectangle() {#getRectangle--}
```
public final RectF getRectangle()
```


프레임의 좌표를 반환합니다. 읽기 전용 android.graphics.RectF.

**반환:**
android.graphics.RectF
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


복제

**반환:**
java.lang.Object - 복제된 shape frame.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```


복제합니다.

**반환:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - 복제된 shape frame.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**반환:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스가 지정된 객체와 같은지 여부를 나타내는 값을 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 객체. |

**반환:**
boolean - **true** if obj은 이 인스턴스와 동일한 값을 가진 ShapeFrame인 경우; 그렇지 않으면, **false**.
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```


이 인스턴스가 지정된 객체와 같은지 여부를 나타내는 값을 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | 이 인스턴스와 비교할 ShapeFRameEx. |

**반환:**
boolean - **true** if value는 이 인스턴스와 동일한 값을 가진 ShapeFrame인 경우; 그렇지 않으면, **false**.