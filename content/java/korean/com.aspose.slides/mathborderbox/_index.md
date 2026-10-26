---
title: MathBorderBox
second_title: Aspose.Slides for Java API 레퍼런스
description: IMathElement 주위에 직사각형 또는 기타 경계선을 그립니다.
type: docs
url: /ko/com.aspose.slides/mathborderbox/
---
**상속:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

IMMathElement 주위에 직사각형 또는 기타 경계선을 그립니다.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | 직사각형 테두리가 있는 MathBorderBox 요소를 생성합니다 |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | MathBorderBox 요소를 생성합니다 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBase()](#getBase--) | 기본 인수 |
| [getHideTop()](#getHideTop--) | Hide Top Edge (default is false) - 테두리 상자 상단 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Hide Top Edge (default is false) - 테두리 상자 상단 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [getHideBottom()](#getHideBottom--) | Hide Bottom Edge (default is false) - 테두리 상자 하단 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Hide Bottom Edge (default is false) - 테두리 상자 하단 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [getHideLeft()](#getHideLeft--) | Hide Left Edge (default is false) - 테두리 상자 왼쪽 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Hide Left Edge (default is false) - 테두리 상자 왼쪽 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [getHideRight()](#getHideRight--) | Hide Right Edge (default is false) - 테두리 상자 오른쪽 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Hide Right Edge (default is false) - 테두리 상자 오른쪽 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Strikethrough Horizontal (default is false) - 가로 취소선의 숨김 또는 표시 상태를 지정합니다. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Strikethrough Horizontal (default is false) - 가로 취소선의 숨김 또는 표시 상태를 지정합니다. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Strikethrough Vertical (default is false) - 세로 취소선의 숨김 또는 표시 상태를 지정합니다. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Strikethrough Vertical (default is false) - 세로 취소선의 숨김 또는 표시 상태를 지정합니다. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | 좌하단에서 우상단까지 취소선 (default is false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | 좌하단에서 우상단까지 취소선 (default is false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | 좌상단에서 우하단까지 취소선 (default is false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | 좌상단에서 우하단까지 취소선 (default is false). |
| [getChildren()](#getChildren--) | 자식 요소를 가져옵니다 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 제어 문자 속성 |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```

직사각형 테두리가 있는 MathBorderBox 요소를 생성합니다

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 테두리 상자가 적용되는 기본 요소입니다. null일 수 있습니다. |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

MathBorderBox 요소를 생성합니다

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 테두리 상자가 적용되는 기본 요소 |
| hideTop | boolean | 상단 가장자리 숨기기 |
| hideBottom | boolean | 하단 가장자리 숨기기 |
| hideLeft | boolean | 왼쪽 가장자리 숨기기 |
| hideRight | boolean | 오른쪽 가장자리 숨기기 |
| strikethroughHorizontal | boolean | 가로 취소선 |
| strikethroughVertical | boolean | 세로 취소선 |
| strikethroughBottomLeftToTopRight | boolean | 좌하단에서 우상단까지 취소선 |
| strikethroughTopLeftToBottomRight | boolean | 좌상단에서 우하단까지 취소선 |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

기본 인수

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**반환값:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```

Hide Top Edge (default is false) - 테두리 상자 상단 가장자리의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```

Hide Bottom Edge (default is false) - 테두리 상자 하단 가장자리의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**반환값:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```

Hide Bottom Edge (default is false) - 테두리 상자 하단 가장자리의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```

Hide Left Edge (default is false) - 테두리 상자 왼쪽 가장자리의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**반환값:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```

Hide Left Edge (default is false) - 테두리 상자 왼쪽 가장자리의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```

Hide Right Edge (default is false) - 테두리 상자 오른쪽 가장자리의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**반환값:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```

Hide Right Edge (default is false) - 테두리 상자 오른쪽 가장자리의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```

Strikethrough Horizontal (default is false) - 가로 취소선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**반환값:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```

Strikethrough Horizontal (default is false) - 가로 취소선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```

Strikethrough Vertical (default is false) - 세로 취소선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**반환값:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```

Strikethrough Vertical (default is false) - 세로 취소선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```

Strikethrough Bottom-Left to Top-Right (default is false). 테두리 상자 왼쪽 아래 모서리에서 오른쪽 위 모서리까지의 대각선 취소선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**반환값:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```

Strikethrough Bottom-Left to Top-Right (default is false). 테두리 상자 왼쪽 아래 모서리에서 오른쪽 위 모서리까지의 대각선 취소선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```

Strikethrough Top-Left to Bottom-Right (default is false). 테두리 상자 왼쪽 위 모서리에서 오른쪽 아래 모서리까지의 대각선 취소선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**반환값:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```

Strikethrough Top-Left to Bottom-Right (default is false). 테두리 상자 왼쪽 위 모서리에서 오른쪽 아래 모서리까지의 대각선 취소선의 숨김 또는 표시 상태를 지정합니다.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

자식 요소를 가져옵니다

**반환값:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

제어 문자 속성

**반환값:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps