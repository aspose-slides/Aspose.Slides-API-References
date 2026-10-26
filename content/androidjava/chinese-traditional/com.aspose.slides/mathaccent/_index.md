---
title: MathAccent
second_title: Aspose.Slides for Android 之 Java API 參考
description: 指定由基底和組合變音標記組成的重音功能 示例 ud835udc4eu0301
type: docs
url: /zh-hant/com.aspose.slides/mathaccent/
---
**繼承：**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有已實作的介面：**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

指定重音功能，包含基礎與組合變音標記 範例：\\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | 建立一個應用於特定數學元素的數學重音，使用預設的重音字元值 |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | 建立一個應用於特定數學元素的數學重音 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getBase()](#getBase--) | 套用重音的參數 |
| [getCharacter()](#getCharacter--) | Accent Character 值應位於 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 範圍內 預設值：Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Accent Character 值應位於 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 範圍內 預設值：Combining Circumflex Accent (U+0302) |
| [getChildren()](#getChildren--) | 取得子元素 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```

建立一個應用於特定數學元素的數學重音，使用預設的重音字元值

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要套用重音的數學元素 |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```

建立一個應用於特定數學元素的數學重音

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**參數：**
| 參數 | 型別 | 說明 |
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

**回傳值：**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

Accent Character 值應位於 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 範圍內 預設值：Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**回傳值：**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

Accent Character 值應位於 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 範圍內 預設值：Combining Circumflex Accent (U+0302)

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

取得子元素

**回傳值：**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**回傳值：**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps