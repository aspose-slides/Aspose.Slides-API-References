---
title: IMathAccent
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Xác định chức năng dấu nhấn gồm một cơ sở và một dấu kết hợp. Ví dụ ud835udc4eu0301
type: docs
url: /vi/com.aspose.slides/imathaccent/
---
**Tất cả các Interface đã thực thi:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

Chỉ định chức năng dấu nhấn, bao gồm một phần cơ sở và một dấu kết hợp. Ví dụ: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBase()](#getBase--) | Đối số mà dấu nhấn được áp dụng |
| [getCharacter()](#getCharacter--) | Ký tự dấu nhấn Giá trị nên nằm trong phạm vi (U+0300\\u2013U+036F) hoặc (U+20D0\\u2013U+20EF) Giá trị mặc định: Dấu Nhấn Đầu Mũ Kết Hợp (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Ký tự dấu nhấn Giá trị nên nằm trong phạm vi (U+0300\\u2013U+036F) hoặc (U+20D0\\u2013U+20EF) Giá trị mặc định: Dấu Nhấn Đầu Mũ Kết Hợp (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Đối số mà dấu nhấn được áp dụng

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```


Ký tự dấu nhấn Giá trị nên nằm trong phạm vi (U+0300\\u2013U+036F) hoặc (U+20D0\\u2013U+20EF) Giá trị mặc định: Dấu Nhấn Đầu Mũ Kết Hợp (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Trả về:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```


Ký tự dấu nhấn Giá trị nên nằm trong phạm vi (U+0300\\u2013U+036F) hoặc (U+20D0\\u2013U+20EF) Giá trị mặc định: Dấu Nhấn Đầu Mũ Kết Hợp (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | char |  |