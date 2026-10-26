---
title: IMathAccent
second_title: Aspose.Slides for Java API 參考
description: 指定由基底和組合附加符號組成的重音功能 示例 ud835udc4eu0301
type: docs
url: /zh-hant/com.aspose.slides/imathaccent/
---
**所有已實作的介面：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

指定重音功能，包含基底與結合附加符號 Example: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

## 方法

| 方法 | 說明 |
| --- | --- |
| [getBase()](#getBase--) | 套用重音的參數 |
| [getCharacter()](#getCharacter--) | 重音字符，值應在 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 範圍內，預設值：Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | 重音字符，值應在 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 範圍內，預設值：Combining Circumflex Accent (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


套用重音的參數

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**傳回值：**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```


重音字符，值應在 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 範圍內，預設值：Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**傳回值：**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```


重音字符，值應在 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 範圍內，預設值：Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | char |  |