---
title: MathDelimiter
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: شیء جداکننده را مشخص می‌کند که شامل کاراکترهای باز و بسته نظیر پرانتز، آکولاد، براکت و خطوط عمودی است و یک یا چند عنصر ریاضی در داخل آن که با یک کاراکتر مشخص جدا می‌شوند.
type: docs
url: /fa/com.aspose.slides/mathdelimiter/
---
**وراثت:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

شیء جداکننده را مشخص می‌کند که شامل کاراکترهای باز و بسته (مانند پرانتز، کروشه، براکت و خط عمودی) و یک یا چند عنصر ریاضی در داخل آن است که با کاراکتر مشخصی جدا می‌شوند. نمونه‌ها: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## سازندگان

| سازنده | توضیح |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | مقداردهی اولیه MathDelimiter با عنصر مشخص‌شده به‌عنوان آرگومان پایه تک |

## متدها

| متد | توضیح |
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

مقداردهی اولیه MathDelimiter با عنصر مشخص‌شده به‌عنوان آرگومان پایه تک

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر پایه‌ای که جداکننده برای آن اعمال می‌شود. می‌تواند null باشد. |

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

**مقدار بازگشتی:**
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

**مقدار بازگشتی:**
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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public final char getSeparatorCharacter()
```

Delimiter Separator Character specifies the character that separates arguments in the delimiter object. The default: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**مقدار بازگشتی:**
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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public final char getEndingCharacter()
```

Delimiter Ending Character specifies the ending, or closing, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**مقدار بازگشتی:**
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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter When true, the delimiters grows vertically to match its operand height. The default value is true

--------------------

> ```
> مثال:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**مقدار بازگشتی:**
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

**پارامترها:**
| پارامتر | نوع | توضیح |
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

**مقدار بازگشتی:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```

Specifies the shape of delimiters in the delimiter object. When is MathDelimiterShape.Centered, delimiters are centered around the math axis of the mathematical text and still be made to fit the entire height of their contents. When is MathDelimiterShape.Match, their height and shape are altered to exactly match their contents.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Delimits arguments using the specified delimiter character

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| separatorCharacter | char | delimiter character |

**مقدار بازگشتی:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - This object after applying the delimiter character
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Encloses a math element in specified characters such as parenthesis or another characters as framing

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| beginningCharacter | char | Beginning character (usually left bracket) |
| endingCharacter | char | Ending character (usually right bracket) |

**مقدار بازگشتی:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - If beginningCharacter and endingCharacter are null, corresponding properties are assigned values only and no new object is created (returns this instance). Otherwise, returns new math element of type Delimiter which includes specified characters as framing and this instance of [MathDelimiter](../../com.aspose.slides/mathdelimiter) framed inside.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Get children elements

**مقدار بازگشتی:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**مقدار بازگشتی:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps