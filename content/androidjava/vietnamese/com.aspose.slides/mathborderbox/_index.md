---
title: MathBorderBox
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Vẽ một đường viền hình chữ nhật hoặc một kiểu viền khác quanh IMathElement.
type: docs
url: /vi/com.aspose.slides/mathborderbox/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

Vẽ một đường viền hình chữ nhật hoặc một kiểu viền khác quanh IMathElement.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | Tạo phần tử MathBorderBox với viền hình chữ nhật |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Tạo phần tử MathBorderBox |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBase()](#getBase--) | Đối số cơ bản |
| [getHideTop()](#getHideTop--) | Ẩn cạnh trên (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh trên của hộp viền. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Ẩn cạnh trên (mặc định là false) - chỉ định trạng thái Ẩn hoặc hiển thị của cạnh trên của hộp viền. |
| [getHideBottom()](#getHideBottom--) | Ẩn cạnh dưới (mặc định là false) - chỉ định trạng thái Ẩn hoặc hiển thị của cạnh dưới của hộp viền. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Ẩn cạnh dưới (mặc định là false) - chỉ định trạng thái Ẩn hoặc hiển thị của cạnh dưới của hộp viền. |
| [getHideLeft()](#getHideLeft--) | Ẩn cạnh trái (mặc định là false) - chỉ định trạng thái Ẩn hoặc hiển thị của cạnh trái của hộp viền. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Ẩn cạnh trái (mặc định là false) - chỉ định trạng thái Ẩn hoặc hiển thị của cạnh trái của hộp viền. |
| [getHideRight()](#getHideRight--) | Ẩn cạnh phải (mặc định là false) - chỉ định trạng thái Ẩn hoặc hiển thị của cạnh phải của hộp viền. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Ẩn cạnh phải (mặc định là false) - chỉ định trạng thái Ẩn hoặc hiển thị của cạnh phải của hộp viền. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Gạch ngang (mặc định là false) - chỉ định trạng thái Ẩn hoặc hiển thị của một đường gạch ngang. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Gạch ngang (mặc định là false) - chỉ định trạng thái Ẩn hoặc hiển thị của một đường gạch ngang. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Gạch dọc (mặc định là false) - chỉ định trạng thái Ẩn hoặc hiển thị của một đường gạch dọc. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Gạch dọc (mặc định là false) - chỉ định trạng thái Ẩn hoặc hiển thị của một đường gạch dọc. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Gạch chéo từ góc trái dưới lên góc phải trên (mặc định là false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Gạch chéo từ góc trái dưới lên góc phải trên (mặc định là false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Gạch chéo từ góc trái trên xuống góc phải dưới (mặc định là false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Gạch chéo từ góc trái trên xuống góc phải dưới (mặc định là false). |
| [getChildren()](#getChildren--) | Lấy các phần tử con |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Thuộc tính ký tự điều khiển |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```

Tạo phần tử MathBorderBox với viền hình chữ nhật

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử cơ bản mà hộp viền được áp dụng. Có thể null. |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Tạo phần tử MathBorderBox

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử cơ bản mà hộp viền được áp dụng |
| hideTop | boolean | Ẩn cạnh trên |
| hideBottom | boolean | Ẩn cạnh dưới |
| hideLeft | boolean | Ẩn cạnh trái |
| hideRight | boolean | Ẩn cạnh phải |
| strikethroughHorizontal | boolean | Gạch ngang |
| strikethroughVertical | boolean | Gạch dọc |
| strikethroughBottomLeftToTopRight | boolean | Gạch chéo từ góc trái dưới lên góc phải trên |
| strikethroughTopLeftToBottomRight | boolean | Gạch chéo từ góc trái trên xuống góc phải dưới |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Đối số cơ bản

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```

Ẩn cạnh trên (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh trên của hộp viền.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Trả về:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```

Ẩn cạnh trên (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh trên của hộp viền.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```

Ẩn cạnh dưới (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh dưới của hộp viền.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Trả về:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```

Ẩn cạnh dưới (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh dưới của hộp viền.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```

Ẩn cạnh trái (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh trái của hộp viền.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Trả về:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```

Ẩn cạnh trái (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh trái của hộp viền.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```

Ẩn cạnh phải (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh phải của hộp viền.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Trả về:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```

Ẩn cạnh phải (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của cạnh phải của hộp viền.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```

Gạch ngang (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của một đường gạch ngang.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Trả về:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```

Gạch ngang (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của một đường gạch ngang.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```

Gạch dọc (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của một đường gạch dọc.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Trả về:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```

Gạch dọc (mặc định là false) - chỉ định trạng thái ẩn hoặc hiển thị của một đường gạch dọc.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```

Gạch chéo từ góc trái dưới lên góc phải trên (mặc định là false). Chỉ định trạng thái ẩn hoặc hiển thị của một đường gạch chéo từ góc trái dưới lên góc phải trên của hộp viền.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Trả về:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```

Gạch chéo từ góc trái dưới lên góc phải trên (mặc định là false). Chỉ định trạng thái ẩn hoặc hiển thị của một đường gạch chéo từ góc trái dưới lên góc phải trên của hộp viền.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```

Gạch chéo từ góc trái trên xuống góc phải dưới (mặc định là false). Chỉ định trạng thái ẩn hoặc hiển thị của một đường gạch chéo từ góc trái trên xuống góc phải dưới của hộp viền.

--------------------

> ```
public final boolean getStrikethroughTopLeftToBottomRight()
```

**Trả về:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```

Gạch chéo từ góc trái trên xuống góc phải dưới (mặc định là false). Chỉ định trạng thái ẩn hoặc hiển thị của một đường gạch chéo từ góc trái trên xuống góc phải dưới của hộp viền.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Lấy các phần tử con

**Trả về:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Thuộc tính ký tự điều khiển

**Trả về:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps