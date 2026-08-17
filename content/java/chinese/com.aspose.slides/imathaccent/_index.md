---
title: IMathAccent
second_title: Aspose.Slides Java API 参考
description: 指定由基字符和组合变音符号组成的重音功能 示例 ud835udc4eu0301
type: docs
url: /zh/com.aspose.slides/imathaccent/
---
**所有实现的接口：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

指定重音功能，由基字符和组合变音符号组成 示例： \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBase()](#getBase--) | 重音所应用的参数 |
| [getCharacter()](#getCharacter--) | Accent Character 值应在 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 范围内 默认值：Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Accent Character 值应在 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 范围内 默认值：Combining Circumflex Accent (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

重音所应用的参数

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**返回值：**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

Accent Character 值应在 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 范围内 默认值：Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**返回值：**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

Accent Character 值应在 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 范围内 默认值：Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char |  |