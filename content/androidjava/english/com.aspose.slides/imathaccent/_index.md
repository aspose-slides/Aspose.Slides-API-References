---
title: IMathAccent
second_title: Aspose.Slides for Android via Java API Reference
description: Specifies the accent function consisting of a base and a combining diacritical mark Example ud835udc4eu0301
type: docs
url: /com.aspose.slides/imathaccent/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

Specifies the accent function, consisting of a base and a combining diacritical mark Example: \\ud835\\udc4e\\u0301

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
> ```

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
> ```

**Returns:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```


Accent Character The value should be within the range of (U+0300\\u2013U+036F) or(U+20D0\\u2013U+20EF) Default value: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

