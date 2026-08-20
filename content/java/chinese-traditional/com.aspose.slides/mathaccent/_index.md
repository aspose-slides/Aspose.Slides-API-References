---
title: MathAccent
second_title: Aspose.Slides for Java API 參考文件
description: 指定由基底和組合變音符號組成的重音功能 範例 ud835udc4eu0301
type: docs
url: /zh-hant/com.aspose.slides/mathaccent/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

指定重音功能，由基底和組合變音符號組成 範例： \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
>  ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | 建立一個套用於指定數學元素且使用預設重音字元值的數學重音 |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | 建立一個套用於指定數學元素的數學重音 |
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | 套用重音的參數 |
| [getCharacter()](#getCharacter--) | Accent Character The value should be within the range of (U+0300\\u2013U+036F) or(U+20D0\\u2013U+20EF) Default value: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Accent Character The value should be within the range of (U+0300\\u2013U+036F) or(U+20D0\\u2013U+20EF) Default value: Combining Circumflex Accent (U+0302) |
| [getChildren()](#getChildren--) | 取得子元素 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```

建立一個套用於指定數學元素且使用預設重音字元值的數學重音

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
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要套用重音的數學元素 |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```

建立一個套用於指定數學元素的數學重音

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要套用重音的數學元素 |
| accentCharacter | char | 重音字元 |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

套用重音的參數

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
public final void setCharacter(char value)
```

Accent Character The value should be within the range of (U+0300\\u2013U+036F) or(U+20D0\\u2013U+20EF) Default value: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

取得子元素

**Returns:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**Returns:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps