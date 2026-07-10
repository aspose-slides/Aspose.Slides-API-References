---
title: MathDelimiter
second_title: Aspose.Slides Android 版 Java API 参考
description: 指定分隔符对象，由一对开闭字符（例如圆括号、花括号、方括号和竖线）组成，内部包含一个或多个数学元素，这些元素由指定字符分隔。
type: docs
url: /zh/com.aspose.slides/mathdelimiter/
---
**继承:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有实现的接口:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

指定分隔符对象，由开括号和闭括号字符（例如圆括号、花括号、方括号和竖线）组成，内部包含一个或多个数学元素，这些元素由指定字符分隔。示例：(\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Initializes MathDelimiter with the specified element as single base argument |
## Methods

| Method | Description |
| --- | --- |
| [getArguments()](#getArguments--) | One or more mathematical elements separated by delimiter characters |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character specifies the beginning, or opening, delimiter character. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character specifies the beginning, or opening, delimiter character. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character specifies the character that separates arguments in the delimiter object. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character specifies the character that separates arguments in the delimiter object. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character specifies the ending, or closing, delimiter character. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character specifies the ending, or closing, delimiter character. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter When true, the delimiters grows vertically to match its operand height. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter When true, the delimiters grows vertically to match its operand height. |
| [getDelimiterShape()](#getDelimiterShape--) | Specifies the shape of delimiters in the delimiter object. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Specifies the shape of delimiters in the delimiter object. |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimits arguments using the specified delimiter character |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Encloses a math element in specified characters such as parenthesis or another characters as framing |
| [getChildren()](#getChildren--) | Get children elements |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

Initializes MathDelimiter with the specified element as single base argument

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | The base element to which the delimiter is applied. Can be null. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

One or more mathematical elements separated by delimiter characters

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**Returns:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```

Delimiter Beginning Character specifies the beginning, or opening, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Returns:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public final void setBeginningCharacter(char value)
```

Delimiter Beginning Character specifies the beginning, or opening, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public final char getSeparatorCharacter()
```

分隔符分隔字符指定在分隔符对象中分隔参数的字符。默认值: '|'.

--------------------

> ```
> 示例:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**返回:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public final void setSeparatorCharacter(char value)
```

Delimiter Separator Character specifies the character that separates arguments in the delimiter object. The default: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public final char getEndingCharacter()
```

分隔符结束字符指定结束或闭合的分隔符字符。数学分隔符是包围字符，例如圆括号、方括号和花括号。默认值: ')'.

--------------------

> ```
> 示例:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**返回:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public final void setEndingCharacter(char value)
```

Delimiter Ending Character specifies the ending, or closing, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter When true, the delimiters grows vertically to match its operand height. The default value is true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Returns:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter When true, the delimiters grows vertically to match its operand height. The default value is true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public final int getDelimiterShape()
```

Specifies the shape of delimiters in the delimiter object. When is MathDelimiterShape.Centered, delimiters are centered around the math axis of the mathematical text and still be made to fit the entire height of their contents. When is MathDelimiterShape.Match, their height and shape are altered to exactly match their contents.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Returns:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```

指定分隔符对象中分隔符的形状。当为 MathDelimiterShape.Centered 时，分隔符在数学文本的数学轴上居中，并且仍然要适应其内容的整体高度。当为 MathDelimiterShape.Match 时，它们的高度和形状会被更改，以精确匹配其内容。

--------------------

> ```
> 示例:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

使用指定的分隔符字符划分参数

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| separatorCharacter | char | 分隔字符 |

**返回：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 应用分隔符字符后的对象
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

在指定字符（例如括号或其他字符）中将数学元素进行框定

--------------------

> ```
> 示例:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char | Beginning character (usually left bracket) |
| endingCharacter | char | Ending character (usually right bracket) |

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 如果 beginningCharacter 和 endingCharacter 为 null，只会为相应属性赋值，不会创建新对象（返回此实例）。否则，返回类型为 Delimiter 的新数学元素，其中包含指定的字符作为框架，并且在其中嵌入此 [MathDelimiter](../../com.aspose.slides/mathdelimiter) 实例。

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

获取子元素

**Returns:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()

控制字符属性

**返回:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps