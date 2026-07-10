---
title: IMathDelimiter
second_title: Aspose.Slides for Android via Java API 参考
description: 指定分隔符对象，由起始和结束字符（如括号、花括号、方括号和竖线）组成，并在内部包含一个或多个通过指定字符分隔的数学元素。
type: docs
url: /zh/com.aspose.slides/imathdelimiter/
---
**所有实现的接口：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

指定分隔符对象，由起始和结束字符（例如括号、花括号、方括号和竖线）组成，并在内部包含一个或多个数学元素，这些元素通过指定字符分隔。示例：(\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
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
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
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
public abstract char getBeginningCharacter()
```

Delimiter Beginning Character specifies the beginning, or opening, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default value: '('.

--------------------

> ```
> 示例：
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Returns:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public abstract void setBeginningCharacter(char value)
```

Delimiter Beginning Character specifies the beginning, or opening, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default value: '('.

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
public abstract char getSeparatorCharacter()
```

分隔符分隔字符指定在分隔符对象中分隔参数的字符。默认值：'|'.

--------------------

> ```
> 示例：
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**返回值：**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public abstract void setSeparatorCharacter(char value)
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
public abstract char getEndingCharacter()
```

Delimiter Ending Character 指定结束，或闭合的分隔符字符。Mathematical delimiters 是包围字符，例如括号、方括号和大括号。默认值: ')'.

--------------------

> ```
> 示例：
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**返回值：**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public abstract void setEndingCharacter(char value)
```

Delimiter Ending Character 指定结束，或闭合的分隔符字符。Mathematical delimiters 是包围字符，例如括号、方括号和大括号。默认值: ')'.

--------------------

> ```
> 示例：
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的增长。当为 true 时，分隔符垂直增长以匹配其操作数高度。默认值为 true

--------------------

> ```
> 示例：
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**返回值：**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```

指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的增长。当为 true 时，分隔符垂直增长以匹配其操作数高度。默认值为 true

--------------------

> ```
> 示例：
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public abstract int getDelimiterShape()
```

指定分隔符对象中分隔符的形状。当形状为 MathDelimiterShape.Centered 时，分隔符居中于数学文本的数学轴，并仍然适配其内容的整体高度。当形状为 MathDelimiterShape.Match 时，它们的高度和形状会被更改以完全匹配其内容。

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
public abstract void setDelimiterShape(int value)
```

指定分隔符对象中分隔符的形状。当形状为 MathDelimiterShape.Centered 时，分隔符居中于数学文本的数学轴，并仍然适配其内容的整体高度。当形状为 MathDelimiterShape.Match 时，它们的高度和形状会被更改以完全匹配其内容。

--------------------

> ```
> 示例：
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)


使用指定的分隔符字符对参数进行分隔

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| separatorCharacter | char | 定界符字符 |

**返回值：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 应用定界符字符后的此对象