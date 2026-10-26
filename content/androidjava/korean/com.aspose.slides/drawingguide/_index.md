---
title: DrawingGuide
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 조정 가능한 그리기 가이드를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/drawingguide/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IDrawingGuide](../../com.aspose.slides/idrawingguide)  
```
public final class DrawingGuide implements IDrawingGuide
```

조정 가능한 그리기 가이드를 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getOrientation()](#getOrientation--) | 그리기 가이드의 방향을 가져오거나 설정합니다. |
| [setOrientation(byte value)](#setOrientation-byte-) | 그리기 가이드의 방향을 가져오거나 설정합니다. |
| [getPosition()](#getPosition--) | 슬라이드의 왼쪽 상단 모서리에서 포인트 단위로 그리기 가이드의 위치를 가져오거나 설정합니다. |
| [setPosition(float value)](#setPosition-float-) | 슬라이드의 왼쪽 상단 모서리에서 포인트 단위로 그리기 가이드의 위치를 가져오거나 설정합니다. |
| [getColor()](#getColor--) | 그리기 가이드의 색상을 가져오거나 설정합니다. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | 그리기 가이드의 색상을 가져오거나 설정합니다. |

### getOrientation() {#getOrientation--}
```
public final byte getOrientation()
```

그리기 가이드의 방향을 가져오거나 설정합니다. 읽기/쓰기 [Orientation](../../com.aspose.slides/orientation).

**반환:**  
byte

### setOrientation(byte value) {#setOrientation-byte-}
```
public final void setOrientation(byte value)
```

그리기 가이드의 방향을 가져오거나 설정합니다. 읽기/쓰기 [Orientation](../../com.aspose.slides/orientation).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getPosition() {#getPosition--}
```
public final float getPosition()
```

슬라이드의 왼쪽 상단 모서리에서 포인트 단위로 그리기 가이드의 위치를 가져오거나 설정합니다. 읽기/쓰기 float.

--------------------

일반적인 값 범위는 가로 가이드의 경우 0부터 슬라이드 높이까지, 세로 가이드의 경우 0부터 슬라이드 너비까지입니다.

**반환:**  
float

### setPosition(float value) {#setPosition-float-}
```
public final void setPosition(float value)
```

슬라이드의 왼쪽 상단 모서리에서 포인트 단위로 그리기 가이드의 위치를 가져오거나 설정합니다. 읽기/쓰기 float.

--------------------

일반적인 값 범위는 가로 가이드의 경우 0부터 슬라이드 높이까지, 세로 가이드의 경우 0부터 슬라이드 너비까지입니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final Integer getColor()
```

그리기 가이드의 색상을 가져오거나 설정합니다. 읽기/쓰기 java.lang.Integer.

**반환:**  
java.lang.Integer

### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```

그리기 가이드의 색상을 가져오거나 설정합니다. 읽기/쓰기 java.lang.Integer.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.Integer |  |