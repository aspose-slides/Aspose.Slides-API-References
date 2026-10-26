---
title: IMathBorderBox
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: IMathElement 주위에 직사각형 또는 다른 테두리를 그립니다.
type: docs
url: /ko/com.aspose.slides/imathborderbox/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

IMathElement 주위에 직사각형 또는 기타 테두리를 그립니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBase()](#getBase--) | 기본 인수 |
| [getHideTop()](#getHideTop--) | Hide Top Edge (default is false) - 테두리 상자의 상단 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Hide Top Edge (default is false) - 테두리 상자의 상단 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [getHideBottom()](#getHideBottom--) | Hide Bottom Edge (default is false) - 테두리 상자의 하단 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Hide Bottom Edge (default is false) - 테두리 상자의 하단 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [getHideLeft()](#getHideLeft--) | Hide Left Edge (default is false) - 테두리 상자의 왼쪽 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Hide Left Edge (default is false) - 테두리 상자의 왼쪽 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [getHideRight()](#getHideRight--) | Hide Right Edge (default is false) - 테두리 상자의 오른쪽 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Hide Right Edge (default is false) - 테두리 상자의 오른쪽 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Strikethrough Horizontal (default is false) - 가로 횡단선의 숨김 또는 표시 상태를 지정합니다. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Strikethrough Horizontal (default is false) - 가로 횡단선의 숨김 또는 표시 상태를 지정합니다. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Strikethrough Vertical (default is false) - 세로 횡단선의 숨김 또는 표시 상태를 지정합니다. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Strikethrough Vertical (default is false) - 세로 횡단선의 숨김 또는 표시 상태를 지정합니다. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Strikethrough Bottom-Left to Top-Right (default is false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Strikethrough Bottom-Left to Top-Right (default is false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Strikethrough Top-Left to Bottom-Right (default is false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Strikethrough Top-Left to Bottom-Right (default is false). |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


기본 인수

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
> ```

**반환값:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```


Hide Top Edge (default is false) - 테두리 상자의 상단 가장자리의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**반환값:**  
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```


Hide Top Edge (default is false) - 테두리 상자의 상단 가장자리의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```


Hide Bottom Edge (default is false) - 테두리 상자의 하단 가장자리의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**반환값:**  
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```


Hide Bottom Edge (default is false) - 테두리 상자의 하단 가장자리의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```


Hide Left Edge (default is false) - 테두리 상자의 왼쪽 가장자리의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**반환값:**  
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```


Hide Left Edge (default is false) - 테두리 상자의 왼쪽 가장자리의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```


Hide Right Edge (default is false) - 테두리 상자의 오른쪽 가장자리의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**반환값:**  
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```


Hide Right Edge (default is false) - 테두리 상자의 오른쪽 가장자리의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```


Strikethrough Horizontal (default is false) - 가로 횡단선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**반환값:**  
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```


Strikethrough Horizontal (default is false) - 가로 횡단선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```


Strikethrough Vertical (default is false) - 세로 횡단선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**반환값:**  
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```


Strikethrough Vertical (default is false) - 세로 횫단선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```


Strikethrough Bottom-Left to Top-Right (default is false). 테두리 상자의 좌하단 모서리에서 우상단 모서리까지 대각선 횡단선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**반환값:**  
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```


Strikethrough Bottom-Left to Top-Right (default is false). 테두리 상자의 좌하단 모서리에서 우상단 모서리까지 대각선 횡단선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```


Strikethrough Top-Left to Bottom-Right (default is false). 테두리 상자의 좌상단 모서리에서 우하단 모서리까지 대각선 횡단선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**반환값:**  
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```


Strikethrough Top-Left to Bottom-Right (default is false). 테두리 상자의 좌상단 모서리에서 우하단 모서리까지 대각선 횡단선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |