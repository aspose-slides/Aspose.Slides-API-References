---
title: IMathAccent
second_title: Aspose.Slides for Android via Java API 参考
description: 指定包含基字符和组合变音标的重音功能 示例 ud835udc4eu0301
type: docs
url: /zh/com.aspose.slides/imathaccent/
---
**所有实现的接口:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

指定重音功能，由基字符和组合变音标组成 示例：\\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | The argument to which the accent was applied |
| [getCharacter()](#getCharacter--) | Accent Character The value should be within the range of (U+0300\\u2013U+036F) or(U+20D0\\u2013U+20EF) Default value: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Accent Character The value should be within the range of (U+0300\\u2013U+036F) or(U+20D0\\u2013U+20EF) Default value: Combining Circumflex Accent (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

The argument to which the accent was applied

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
>  ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

Accent Character The value should be within the range of (U+0300\\u2013U+036F) or(U+20D0\\u2013U+20EF) Default value: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
>  ```

**Returns:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)

Accent Character The value should be within the range of (U+0300\\u2013U+036F) or(U+20D0\\u2013U+20EF) Default value: Combining Circumflex Accent (U+0302)


--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char |  |