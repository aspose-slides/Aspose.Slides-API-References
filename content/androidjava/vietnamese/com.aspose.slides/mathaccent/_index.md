---
title: MathAccent
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Xác định chức năng dấu nhấn bao gồm một cơ sở và một ký tự kết hợp. Ví dụ ud835udc4eu0301
type: docs
url: /vi/com.aspose.slides/mathaccent/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

Xác định chức năng dấu nhấn, bao gồm một cơ sở và một dấu ký tự kết hợp. Ví dụ: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```
## Hàm khởi tạo

| Constructor | Description |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | Tạo một dấu nhấn toán học áp dụng cho một phần tử toán học được chỉ định với giá trị ký tự dấu nhấn mặc định |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | Tạo một dấu nhấn toán học áp dụng cho một phần tử toán học được chỉ định |
## Phương thức

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Đối số mà dấu nhấn đã được áp dụng |
| [getCharacter()](#getCharacter--) | Accent Character Giá trị phải nằm trong phạm vi (U+0300\\u2013U+036F) hoặc (U+20D0\\u2013U+20EF) Giá trị mặc định: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Accent Character Giá trị phải nằm trong phạm vi (U+0300\\u2013U+036F) hoặc (U+20D0\\u2013U+20EF) Giá trị mặc định: Combining Circumflex Accent (U+0302) |
| [getChildren()](#getChildren--) | Lấy các phần tử con |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Thuộc tính ký tự điều khiển |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```

Tạo một dấu nhấn toán học áp dụng cho một phần tử toán học được chỉ định với giá trị ký tự dấu nhấn mặc định

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | một phần tử toán học để áp dụng dấu nhấn |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```

Tạo một dấu nhấn toán học áp dụng cho một phần tử toán học được chỉ định

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | phần tử toán học để áp dụng dấu nhấn |
| accentCharacter | char | ký tự dấu nhấn |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Đối số mà dấu nhấn đã được áp dụng

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**Giá trị trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

Accent Character Giá trị phải nằm trong phạm vi (U+0300\\u2013U+036F) hoặc (U+20D0\\u2013U+20EF) Giá trị mặc định: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Giá trị trả về:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

Accent Character Giá trị phải nằm trong phạm vi (U+0300\\u2013U+036F) hoặc (U+20D0\\u2013U+20EF) Giá trị mặc định: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Lấy các phần tử con

**Giá trị trả về:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Thuộc tính ký tự điều khiển

**Giá trị trả về:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps