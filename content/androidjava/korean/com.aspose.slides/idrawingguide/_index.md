---
title: IDrawingGuide
second_title: Aspose.Slides for Android via Java API Reference
description: 조정 가능한 그리기 가이드를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

조정 가능한 그리기 가이드를 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [getOrientation()](#getOrientation--) | 그리기 가이드의 방향을 가져오거나 설정합니다. |
| [setOrientation(byte value)](#setOrientation-byte-) | 그리기 가이드의 방향을 가져오거나 설정합니다. |
| [getPosition()](#getPosition--) | 그리기 가이드의 위치를 슬라이드의 왼쪽 위 모서리에서 포인트 단위로 가져오거나 설정합니다. |
| [setPosition(float value)](#setPosition-float-) | 그리기 가이드의 위치를 슬라이드의 왼쪽 위 모서리에서 포인트 단위로 가져오거나 설정합니다. |
| [getColor()](#getColor--) | 그리기 가이드의 색상을 가져오거나 설정합니다. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | 그리기 가이드의 색상을 가져오거나 설정합니다. |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```

그리기 가이드의 방향을 가져오거나 설정합니다. 읽기/쓰기 [Orientation](../../com.aspose.slides/orientation).

**반환값:**
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```

그리기 가이드의 방향을 가져오거나 설정합니다. 읽기/쓰기 [Orientation](../../com.aspose.slides/orientation).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

그리기 가이드의 위치를 슬라이드의 왼쪽 위 모서리에서 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 float.

--------------------

수평 가이드의 경우 0부터 슬라이드 높이까지, 수직 가이드의 경우 0부터 슬라이드 너비까지가 일반적인 값 범위입니다.

**반환값:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

그리기 가이드의 위치를 슬라이드의 왼쪽 위 모서리에서 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 float.

--------------------

수평 가이드의 경우 0부터 슬라이드 높이까지, 수직 가이드의 경우 0부터 슬라이드 너비까지가 일반적인 값 범위입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract Integer getColor()
```

그리기 가이드의 색상을 가져오거나 설정합니다. 읽기/쓰기 java.lang.Integer.

**반환값:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

그리기 가이드의 색상을 가져오거나 설정합니다. 읽기/쓰기 java.lang.Integer.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.Integer |  |