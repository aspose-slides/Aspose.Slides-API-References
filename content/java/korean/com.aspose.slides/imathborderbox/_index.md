---
title: IMathBorderBox
second_title: Aspose.Slides for Java API 레퍼런스
description: IMathElement 주위에 직사각형 또는 기타 형태의 테두리를 그립니다.
type: docs
url: /ko/com.aspose.slides/imathborderbox/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

IMathElement 주위에 직사각형 또는 기타 형태의 테두리를 그립니다.

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
| [getHideTop()](#getHideTop--) | 상단 가장자리 숨김 (기본값은 false) - 테두리 상자의 상단 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | 상단 가장자리 숨김 (기본값은 false) - 테두리 상자의 상단 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [getHideBottom()](#getHideBottom--) | 하단 가장자리 숨김 (기본값은 false) - 테두리 상자의 하단 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | 하단 가장자리 숨김 (기본값은 false) - 테두리 상자의 하단 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [getHideLeft()](#getHideLeft--) | 왼쪽 가장자리 숨김 (기본값은 false) - 테두리 상자의 왼쪽 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | 왼쪽 가장자리 숨김 (기본값은 false) - 테두리 상자의 왼쪽 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [getHideRight()](#getHideRight--) | 오른쪽 가장자리 숨김 (기본값은 false) - 테두리 상자의 오른쪽 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | 오른쪽 가장자리 숨김 (기본값은 false) - 테두리 상자의 오른쪽 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | 가로 취소선 (기본값은 false) - 가로 취소선의 숨김 또는 표시 상태를 지정합니다. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | 가로 취소선 (기본값은 false) - 가로 취소선의 숨김 또는 표시 상태를 지정합니다. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | 세로 취소선 (기본값은 false) - 세로 취소선의 숨김 또는 표시 상태를 지정합니다. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | 세로 취소선 (기본값은 false) - 세로 취소선의 숨김 또는 표시 상태를 지정합니다. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | 좌하단에서 우상단으로 가는 취소선 (기본값은 false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | 좌하단에서 우상단으로 가는 취소선 (기본값은 false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | 좌상단에서 우하단으로 가는 취소선 (기본값은 false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | 좌상단에서 우하단으로 가는 취소선 (기본값은 false). |

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

**반환:**  
[IMathElement](../../com.aspose.slides/imathelement)

### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```

상단 가장자리 숨김 (기본값은 false) - 테두리 상자의 상단 가장자리의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**반환:**  
boolean

### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```

상단 가장자리 숨김 (기본값은 false) - 테두리 상자의 상단 가장자리의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```

하단 가장자리 숨김 (기본값은 false) - 테두리 상자의 하단 가장자리의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**반환:**  
boolean

### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```

하단 가장자리 숨김 (기본값은 false) - 테두리 상자의 하단 가장자리의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```

왼쪽 가장자리 숨김 (기본값은 false) - 테두리 상자의 왼쪽 가장자리의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**반환:**  
boolean

### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```

왼쪽 가장자리 숨김 (기본값은 false) - 테두리 상자의 왼쪽 가장자리의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```

오른쪽 가장자리 숨김 (기본값은 false) - 테두리 상자의 오른쪽 가장자리의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**반환:**  
boolean

### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```

오른쪽 가장자리 숨김 (기본값은 false) - 테두리 상자의 오른쪽 가장자리의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```

가로 취소선 (기본값은 false) - 가로 취소선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**반환:**  
boolean

### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```

가로 취소선 (기본값은 false) - 가로 취소선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```

세로 취소선 (기본값은 false) - 세로 취소선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**반환:**  
boolean

### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```

세로 취소선 (기본값은 false) - 세로 취소선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```

좌하단에서 우상단으로 가는 취소선 (기본값은 false). 테두리 상자의 좌하단 모서리에서 우상단 모서리까지 이어지는 대각선 취소선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**반환:**  
boolean

### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```

좌하단에서 우상단으로 가는 취소선 (기본값은 false). 테두리 상자의 좌하단 모서리에서 우상단 모서리까지 이어지는 대각선 취소선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```

좌상단에서 우하단으로 가는 취소선 (기본값은 false). 테두리 상자의 좌상단 모서리에서 우하단 모서리까지 이어지는 대각선 취소선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**반환:**  
boolean

### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```

좌상단에서 우하단으로 가는 취소선 (기본값은 false). 테두리 상자의 좌상단 모서리에서 우하단 모서리까지 이어지는 대각선 취소선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |