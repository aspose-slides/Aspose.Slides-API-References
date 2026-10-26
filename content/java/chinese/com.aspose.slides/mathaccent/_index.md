---
title: MathAccent
second_title: Aspose.Slides for Java API 参考
description: 指定由基字符和组合变音符号组成的重音功能 示例 ud835udc4eu0301
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

指定重音功能，由基字符和组合变音符号组成 示例： \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | 创建一个数学重音，应用于指定的数学元素，使用默认的重音字符值 |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | 创建一个数学重音，应用于指定的数学元素 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBase()](#getBase--) | 重音所应用的参数 |
| [getCharacter()](#getCharacter--) | 重音字符，其值应在 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 范围内，默认值：组合抑扬符 (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | 重音字符，其值应在 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 范围内，默认值：组合抑扬符 (U+0302) |
| [getChildren()](#getChildren--) | 获取子元素 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 控制字符属性 |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```


创建一个数学重音，应用于指定的数学元素，使用默认的重音字符值

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 用于应用重音的数学元素 |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```


创建一个数学重音，应用于指定的数学元素

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 用于应用重音的数学元素 |
| accentCharacter | char | 重音字符 |

### getBase() {#getBase--}
```
public final IMathElement getBase()
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
public final char getCharacter()
```


重音字符，其值应在 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 范围内，默认值：组合抑扬符 (U+0302)

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
public final void setCharacter(char value)
```


重音字符，其值应在 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 范围内，默认值：组合抑扬符 (U+0302)

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


获取子元素

**返回值：**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


控制字符属性

**返回值：**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps