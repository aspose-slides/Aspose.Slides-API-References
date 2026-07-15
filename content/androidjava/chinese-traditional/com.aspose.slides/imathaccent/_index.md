---
title: IMathAccent
second_title: Aspose.Slides for Android via Java API 參考
description: 指定由基礎字元和組合變音符號組成的重音功能 示例 ud835udc4eu0301
type: docs
url: /zh-hant/com.aspose.slides/imathaccent/
---
**所有已實作的介面:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

指定重音功能，由基礎和組合附加標記組成 Example: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

## Methods

| 方法 | 說明 |
| --- | --- |
| [getBase()](#getBase--) | 套用重音的引數 |
| [getCharacter()](#getCharacter--) | 重音字元 值應在 (U+0300–U+036F) 或 (U+20D0–U+20EF) 範圍內 預設值：組合抑揚符號 (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | 重音字元 值應在 (U+0300–U+036F) 或 (U+20D0–U+20EF) 範圍內 預設值：組合抑揚符號 (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

套用重音的引數

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**返回值:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

重音字元 值應在 (U+0300–U+036F) 或 (U+20D0–U+20EF) 範圍內 預設值：組合抑揚符號 (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**返回值:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

重音字元 值應在 (U+0300–U+036F) 或 (U+20D0–U+20EF) 範圍內 預設值：組合抑揚符號 (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | char |  |