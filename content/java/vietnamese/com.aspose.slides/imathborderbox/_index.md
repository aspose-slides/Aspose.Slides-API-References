---
title: IMathBorderBox
second_title: Tham chiếu API Aspose.Slides cho Java
description: Vẽ một đường viền hình chữ nhật hoặc một loại viền khác quanh IMathElement.
type: docs
url: /vi/com.aspose.slides/imathborderbox/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

Vẽ một đường viền hình chữ nhật hoặc loại khác quanh IMathElement.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBase()](#getBase--) | Đối số cơ bản |
| [getHideTop()](#getHideTop--) | Hide Top Edge (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh trên của hộp viền. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Hide Top Edge (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh trên của hộp viền. |
| [getHideBottom()](#getHideBottom--) | Hide Bottom Edge (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh dưới của hộp viền. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Hide Bottom Edge (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh dưới của hộp viền. |
| [getHideLeft()](#getHideLeft--) | Hide Left Edge (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh trái của hộp viền. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Hide Left Edge (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh trái của hộp viền. |
| [getHideRight()](#getHideRight--) | Hide Right Edge (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh phải của hộp viền. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Hide Right Edge (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh phải của hộp viền. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Strikethrough Horizontal (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của một đường gạch ngang. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Strikethrough Horizontal (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của một đường gạch ngang. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Strikethrough Vertical (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của một đường gạch dọc. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Strikethrough Vertical (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của một đường gạch dọc. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Strikethrough Bottom-Left to Top-Right (mặc định là false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Strikethrough Bottom-Left to Top-Right (mặc định là false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Strikethrough Top-Left to Bottom-Right (mặc định là false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Strikethrough Top-Left to Bottom-Right (mặc định là false). |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Đối số cơ bản

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```


Hide Top Edge (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh trên của hộp viền.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Trả về:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```


Hide Top Edge (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh trên của hộp viền.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```


Hide Bottom Edge (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh dưới của hộp viền.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Trả về:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```


Hide Bottom Edge (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh dưới của hộp viền.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```


Hide Left Edge (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh trái của hộp viền.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Trả về:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```


Hide Left Edge (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh trái của hộp viền.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```


Hide Right Edge (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh phải của hộp viền.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Trả về:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```


Hide Right Edge (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh phải của hộp viền.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```


Strikethrough Horizontal (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của một đường gạch ngang.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Trả về:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```


Strikethrough Horizontal (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của một đường gạch ngang.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```


Strikethrough Vertical (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của một đường gạch dọc.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Trả về:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```


Strikethrough Vertical (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của một đường gạch dọc.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```


Strikethrough Bottom-Left to Top-Right (mặc định là false). Chỉ định trạng thái ẩn hoặc hiển thị của một đường gạch chéo từ góc dưới-trái lên góc trên-phải của hộp viền.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Trả về:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```


Strikethrough Bottom-Left to Top-Right (mặc định là false). Chỉ định trạng thái ẩn hoặc hiển thị của một đường gạch chéo từ góc dưới-trái lên góc trên-phải của hộp viền.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```


Strikethrough Top-Left to Bottom-Right (mặc định là false). Chỉ định trạng thái ẩn hoặc hiển thị của một đường gạch chéo từ góc trên-trái xuống góc dưới-phải của hộp viền.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Trả về:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```


Strikethrough Top-Left to Bottom-Right (mặc định là false). Chỉ định trạng thái ẩn hoặc hiển thị của một đường gạch chéo từ góc trên-trái xuống góc dưới-phải của hộp viền.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |