---
title: IMathDelimiter
second_title: Aspose.Slides for Java API 参考
description: 指定由括号、花括号、方括号和竖线等开闭字符组成的分隔符对象，并在内部包含一个或多个通过指定字符分隔的数学元素。
type: docs
url: /zh/com.aspose.slides/imathdelimiter/
---
**所有实现的接口：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

指定分隔符对象，由开闭字符（例如圆括号、花括号、方括号和竖线）组成，并在内部包含一个或多个数学元素，以指定字符分隔。示例：(\\ud835\\udc652)；[\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
## 方法

| 方法 | 描述 |
| --- | --- |
| [getArguments()](#getArguments--) | 一个或多个数学元素由分隔符字符分隔 |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character 指定起始或开启的分隔符字符。 |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character 指定起始或开启的分隔符字符。 |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character 指定分隔符对象中分隔参数的字符。 |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character 指定分隔符对象中分隔参数的字符。 |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character 指定结束或关闭的分隔符字符。 |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character 指定结束或关闭的分隔符字符。 |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | 指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的增长。当为 true 时，分隔符会垂直增长以匹配其操作数的高度。 |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | 指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的增长。当为 true 时，分隔符会垂直增长以匹配其操作数的高度。 |
| [getDelimiterShape()](#getDelimiterShape--) | 指定分隔符对象中分隔符的形状。 |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | 指定分隔符对象中分隔符的形状。 |
| [delimit(char separatorCharacter)](#delimit-char-) | 使用指定的分隔符字符对参数进行分隔。 |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```


一个或多个数学元素由分隔符字符分隔

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**返回：**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public abstract char getBeginningCharacter()
```


Delimiter Beginning Character 指定起始或开启的分隔符字符。数学分隔符是诸如圆括号、方括号和花括号之类的包围字符。默认值：'('。

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**返回：**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public abstract void setBeginningCharacter(char value)
```


Delimiter Beginning Character 指定起始或开启的分隔符字符。数学分隔符是诸如圆括号、方括号和花括号之类的包围字符。默认值：'('。

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public abstract char getSeparatorCharacter()
```


Delimiter Separator Character 指定分隔符对象中分隔参数的字符。默认值：'|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**返回：**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public abstract void setSeparatorCharacter(char value)
```


Delimiter Separator Character 指定分隔符对象中分隔参数的字符。默认值：'|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public abstract char getEndingCharacter()
```


Delimiter Ending Character 指定结束或关闭的分隔符字符。数学分隔符是诸如圆括号、方括号和花括号之类的包围字符。默认值：')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**返回：**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public abstract void setEndingCharacter(char value)
```


Delimiter Ending Character 指定结束或关闭的分隔符字符。数学分隔符是诸如圆括号、方括号和花括号之类的包围字符。默认值：')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```


指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的增长。当为 true 时，分隔符会垂直增长以匹配其操作数的高度。默认值为 true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**返回：**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```


指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的增长。当为 true 时，分隔符会垂直增长以匹配其操作数的高度。默认值为 true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public abstract int getDelimiterShape()
```


指定分隔符对象中分隔符的形状。当为 MathDelimiterShape.Centered 时，分隔符在数学文本的数学轴上居中，并仍然适应其内容的整体高度。当为 MathDelimiterShape.Match 时，其高度和形状会被修改以完全匹配其内容。

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**返回：**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public abstract void setDelimiterShape(int value)
```


指定分隔符对象中分隔符的形状。当为 MathDelimiterShape.Centered 时，分隔符在数学文本的数学轴上居中，并仍然适应其内容的整体高度。当为 MathDelimiterShape.Match 时，其高度和形状会被修改以完全匹配其内容。

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```


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
| separatorCharacter | char | 分隔符字符 |

**返回：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 应用分隔符字符后的此对象