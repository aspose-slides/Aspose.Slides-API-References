---
title: IMathDelimiter
second_title: Aspose.Slides for Android via Java API Reference
description: Specifies the delimiter object consisting of opening and closing characters such as parentheses  braces brackets and vertical bars and one or more mathematical elements inside separated by a specified character.
type: docs
url: /com.aspose.slides/imathdelimiter/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Specifies the delimiter object, consisting of opening and closing characters (such as parentheses, braces, brackets, and vertical bars), and one or more mathematical elements inside, separated by a specified character. Examples: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

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
> Example:
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


Delimiter Separator Character specifies the character that separates arguments in the delimiter object. The default: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Returns:**
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


Delimiter Ending Character specifies the ending, or closing, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Returns:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public abstract void setEndingCharacter(char value)
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
public abstract boolean getGrowToMatchOperandHeight()
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
public abstract void setGrowToMatchOperandHeight(boolean value)
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
public abstract int getDelimiterShape()
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
public abstract void setDelimiterShape(int value)
```


Specifies the shape of delimiters in the delimiter object. When is MathDelimiterShape.Centered, delimiters are centered around the math axis of the mathematical text and still be made to fit the entire height of their contents. When is MathDelimiterShape.Match, their height and shape are altered to exactly match their contents.

--------------------

> ```
> Example:
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
public abstract IMathDelimiter delimit(char separatorCharacter)
```


Delimits arguments using the specified delimiter character

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| separatorCharacter | char | delimiter character |

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - This object after applying the delimiter character
