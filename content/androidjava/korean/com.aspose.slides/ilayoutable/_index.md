---
title: ILayoutable
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 차트 요소의 정확한 위치를 지정합니다.
type: docs
url: /ko/com.aspose.slides/ilayoutable/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface ILayoutable extends IChartComponent
```

차트 요소의 정확한 위치를 지정합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getX()](#getX--) | 차트 요소의 x 위치(왼쪽)를 차트 너비의 비율로 지정합니다. |
| [setX(float value)](#setX-float-) | 차트 요소의 x 위치(왼쪽)를 차트 너비의 비율로 지정합니다. |
| [getY()](#getY--) | 차트 요소의 위쪽을 차트 높이의 비율로 지정합니다. |
| [setY(float value)](#setY-float-) | 차트 요소의 위쪽을 차트 높이의 비율로 지정합니다. |
| [getWidth()](#getWidth--) | 차트 요소의 너비를 차트 너비의 비율로 지정합니다. |
| [setWidth(float value)](#setWidth-float-) | 차트 요소의 너비를 차트 너비의 비율로 지정합니다. |
| [getHeight()](#getHeight--) | 차트 요소의 높이를 차트 높이의 비율로 지정합니다. |
| [setHeight(float value)](#setHeight-float-) | 차트 요소의 높이를 차트 높이의 비율로 지정합니다. |
| [getRight()](#getRight--) | 차트 요소의 오른쪽을 차트 너비의 비율로 가져옵니다. |
| [getBottom()](#getBottom--) | 차트 요소의 위쪽을 차트 높이의 비율로 가져옵니다. |
### getX() {#getX--}
```
public abstract float getX()
```

차트 요소의 x 위치(왼쪽)를 차트 너비의 비율로 지정합니다. 읽기/쓰기 float.

**반환:**
float
### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

차트 요소의 x 위치(왼쪽)를 차트 너비의 비율로 지정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

차트 요소의 위쪽을 차트 높이의 비율로 지정합니다. 읽기/쓰기 float.

**반환:**
float
### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

차트 요소의 위쪽을 차트 높이의 비율로 지정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

차트 요소의 너비를 차트 너비의 비율로 지정합니다. 읽기/쓰기 float.

**반환:**
float
### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

차트 요소의 너비를 차트 너비의 비율로 지정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

차트 요소의 높이를 차트 높이의 비율로 지정합니다. 읽기/쓰기 float.

**반환:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

차트 요소의 높이를 차트 높이의 비율로 지정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public abstract float getRight()
```

차트 요소의 오른쪽을 차트 너비의 비율로 가져옵니다. 읽기 전용 float.

**반환:**
float
### getBottom() {#getBottom--}
```
public abstract float getBottom()
```

차트 요소의 위쪽을 차트 높이의 비율로 가져옵니다. 읽기 전용 float.

**반환:**
float