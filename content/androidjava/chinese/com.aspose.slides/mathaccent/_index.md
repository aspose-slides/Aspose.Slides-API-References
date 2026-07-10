---
title: MathAccent
second_title: Aspose.Slides Android Java API 参考
description: 指定由基元素和组合变音标组成的重音功能 示例 ud835udc4eu0301
type: docs
url: /zh/com.aspose.slides/mathaccent/
---
**继承：**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有实现的接口：**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

指定重音功能，由基元素和组合变音标组成 示例：\\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | Creates a math accent applying to a specified math element with the default accent character value |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | Creates a math accent applying to a specified math element |
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | The argument to which the accent was applied |
| [getCharacter()](#getCharacter--) | Accent Character The value should be within the range of (U+0300\u2013U+036F) or(U+20D0\u2013U+20EF) Default value: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Accent Character The value should be within the range of (U+0300\u2013U+036F) or(U+20D0\u2013U+20EF) Default value: Combining Circumflex Accent (U+0302) |
| [getChildren()](#getChildren--) | Get children elements |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```

Creates a math accent applying to a specified math element with the default accent character value

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | a math element to apply accent |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```

Creates a math accent applying to a specified math element

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element to apply accent |
| accentCharacter | char | accent character |

### getBase() {#getBase--}
```
public final IMathElement getBase()
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
public final char getCharacter()
```

Accent Character The value should be within the range of (U+0300\u2013U+036F) or(U+20D0\u2013U+20EF) Default value: Combining Circumflex Accent (U+0302)

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
public final void setCharacter(char value)
```

Accent Character The value should be within the range of (U+0300\u2013U+036F) or(U+20D0\u2013U+20EF) Default value: Combining Circumflex Accent (U+0302)

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Get children elements

**Returns:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()

控制字符属性

**返回：**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps