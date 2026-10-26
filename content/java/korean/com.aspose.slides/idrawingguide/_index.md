---
title: IDrawingGuide
second_title: Aspose.Slides for Java API Reference
description: 조정 가능한 그리기 가이드를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

조정 가능한 그리기 가이드를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getOrientation()](#getOrientation--) | 그리기 가이드의 방향을 반환하거나 설정합니다. |
| [setOrientation(byte value)](#setOrientation-byte-) | 그리기 가이드의 방향을 반환하거나 설정합니다. |
| [getPosition()](#getPosition--) | 그리기 가이드를 슬라이드 왼쪽 위 모서리에서 점 단위로 위치를 반환하거나 설정합니다. |
| [setPosition(float value)](#setPosition-float-) | 그리기 가이드를 슬라이드 왼쪽 위 모서리에서 점 단위로 위치를 반환하거나 설정합니다. |
| [getColor()](#getColor--) | 그리기 가이드의 색상을 반환하거나 설정합니다. |
| [setColor(Color value)](#setColor-java.awt.Color-) | 그리기 가이드의 색상을 반환하거나 설정합니다. |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```

그리기 가이드의 방향을 반환하거나 설정합니다. 읽기/쓰기 [Orientation](../../com.aspose.slides/orientation).

**반환:**  
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```

그리기 가이드의 방향을 반환하거나 설정합니다. 읽기/쓰기 [Orientation](../../com.aspose.slides/orientation).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

그리기 가이드를 슬라이드 왼쪽 위 모서리에서 점 단위로 위치를 반환하거나 설정합니다. 읽기/쓰기 float.

--------------------

일반적인 값 범위는 수평 가이드의 경우 0부터 슬라이드 높이까지이며, 수직 가이드의 경우 0부터 슬라이드 너비까지입니다.

**반환:**  
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

그리기 가이드를 슬라이드 왼쪽 위 모서리에서 점 단위로 위치를 반환하거나 설정합니다. 읽기/쓰기 float.

--------------------

일반적인 값 범위는 수평 가이드의 경우 0부터 슬라이드 높이까지이며, 수직 가이드의 경우 0부터 슬라이드 너비까지입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract Color getColor()
```

그리기 가이드의 색상을 반환하거나 설정합니다. 읽기/쓰기 java.awt.Color.

**반환:**  
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

그리기 가이드의 색상을 반환하거나 설정합니다. 읽기/쓰기 java.awt.Color.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.awt.Color |  |