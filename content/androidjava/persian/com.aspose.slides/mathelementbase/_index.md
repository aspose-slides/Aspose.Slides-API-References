---
title: MathElementBase
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: کلاس پایه برای IMathElement با پیاده‌سازی برخی متدهایی که برای تمام کلاس‌های ارث‌برده مشترک هستند. فقط برای استفاده داخلی.
type: docs
url: /fa/com.aspose.slides/mathelementbase/
---
**وراثت:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject  
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

کلاس پایه برای IMathElement با پیاده‌سازی برخی متدهایی که برای تمام کلاس‌های ارث‌برده مشترک هستند. فقط برای استفاده داخلی. کلاس ارث‌برده باید IMathElement باشد.

## متدها

| متد | توضیح |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Returns Parent\_Immediate object. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Joins a mathematical element and forms a mathematical block |
| [join(String mathText)](#join-java.lang.String-) | Joins a mathematical text and forms a mathematical block |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Creates a fraction with this numerator and specified denominator |
| [divide(String denominator)](#divide-java.lang.String-) | Creates a fraction with this numerator and specified denominator |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Creates a fraction of the specified type with this numerator and specified denominator |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Creates a fraction of the specified type with this numerator and specified denominator |
| [enclose()](#enclose--) | Encloses a math element in parenthesis |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Encloses a math element in specified characters such as parenthesis or another characters as framing |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Takes a function of an argument using this instance as the function name |
| [function(String functionArgument)](#function-java.lang.String-) | Takes a function of an argument using this instance as the function name |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Takes specified function using this instance as the argument |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Takes specified function using this instance as the argument |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Takes specified function using this instance as the argument |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Takes specified function using this instance as the argument and specified additional argument |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Takes specified function using this instance as the argument and specified additional argument |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Creates subscript |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Creates subscript |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Creates superscript |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Creates superscript |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates subscript and superscript on the right |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Creates subscript and superscript on the right |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates subscript and superscript on the left |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Creates subscript and superscript on the left |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Specifies the mathematical root of the given degree from the specified argument. |
| [radical(String degree)](#radical-java.lang.String-) | Specifies the mathematical root of the given degree from the specified argument. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Takes upper limit |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Takes upper limit |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Takes lower limit |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Takes lower limit |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates a N-ary operator |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Creates a N-ary operator |
| [toMathArray()](#toMathArray--) | Puts in a vertical array |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Takes the integral |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Takes the integral |
| [integral(int integralType)](#integral-int-) | Takes the integral without limits |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Takes the integral |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Takes the integral |
| [accent(char accentCharacter)](#accent-char-) | Sets an accent mark (a character on the top of this element) |
| [overbar()](#overbar--) | Sets a bar on the top of this element |
| [underbar()](#underbar--) | Sets a bar on the bottom of this element |
| [group()](#group--) | Places this element in a group using a bottom curly bracket |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Places this element in a group using a grouping character such as bottom curly bracket or another |
| [toBorderBox()](#toBorderBox--) | Places this element in a border-box |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Places this element in a border-box |
| [toBox()](#toBox--) | Places this element in a non-visual box (logical grouping) which is used to group components of an equation or other instance of mathematical text. |
| [getChildren()](#getChildren--) | Get children elements |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

یک شیء Parent_Immediate برمی‌گرداند. فقط-خواندنی IDOMObject.

**بازگشت:**  
com.aspose.slides.IDOMObject

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

یک عنصر ریاضی را می-پیوندد و یک بلوک ریاضی می‌سازد

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | عنصری که باید پیوست شود |

**بازگشت:**  
[IMathBlock](../../com.aspose.slides/imathblock) - یک IMathBlock جدید حاوی این نمونه و آرگومان مشخص شده

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

یک متن ریاضی را می-پیوندد و یک بلوک ریاضی می‌سازد

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathText | java.lang.String | متن ریاضی که باید پیوست شود |

**بازگشت:**  
[IMathBlock](../../com.aspose.slides/imathblock) - یک IMathBlock جدید حاوی این نمونه و آرگومان مشخص شده

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```

یک کسر با صورت فعلی و مخرج مشخص شده می‌سازد

--------------------

> ```
> مثال:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | مخرج |

**بازگشت:**  
[IMathFraction](../../com.aspose.slides/imathfraction) - کسر جدید

### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```

یک کسر با صورت فعلی و مخرج مشخص شده می‌سازد

--------------------

> ```
> مثال:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| denominator | java.lang.String | مخرج |

**بازگشت:**  
[IMathFraction](../../com.aspose.slides/imathfraction) - کسر جدید

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

یک کسر از نوع مشخص با صورت فعلی و مخرج مشخص شده می‌سازد

--------------------

> ```
> مثال:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | مخرج |
| fractionType | int | نوع کسر: Bar, NoBar, Skewed, Linear |

**بازگشت:**  
[IMathFraction](../../com.aspose.slides/imathfraction) - کسر جدید

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

یک کسر از نوع مشخص با صورت فعلی و مخرج مشخص شده می‌سازد

--------------------

> ```
> مثال:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| denominator | java.lang.String | مخرج |
| fractionType | int | نوع کسر: Bar, NoBar, Skewed, Linear |

**بازگشت:**  
[IMathFraction](../../com.aspose.slides/imathfraction) - کسر جدید

### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

عنصر ریاضی را در پرانتز می‌محوطه می‌کند

--------------------

> ```
> مثال:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**بازگشت:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر ریاضی از نوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) که شامل پرانتز است

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

عنصر ریاضی را در کاراکترهای مشخص‌شده (مانند پرانتز یا سایر کاراکترها) به‌عنوان قاب می‌محوطه می‌کند

--------------------

> ```
> مثال:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| beginningCharacter | char | کاراکتر آغاز (معمولاً پرانتز سمت چپ) |
| endingCharacter | char | کاراکتر پایان (معمولاً پرانتز سمت راست) |

**بازگشت:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر ریاضی از نوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) که شامل کاراکترهای مشخص‌شده به‌عنوان قاب است

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

یک تابع از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع می‌گیرد

--------------------

> ```
> مثال:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | یک آرگومان تابع |

**بازگشت:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)

### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

یک تابع از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع می‌گیرد

--------------------

> ```
> مثال:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionArgument | java.lang.String | یک آرگومان تابع |

**بازگشت:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

تابع مشخص‌شده را با این نمونه به‌عنوان آرگومان می‌گیرد

--------------------

> ```
> مثال:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | نام تابع |

**بازگشت:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

تابع مشخص‌شده را با این نمونه به‌عنوان آرگومان می‌گیرد

--------------------

> ```
> مثال:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionName | java.lang.String | نام تابع |

**بازگشت:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

تابع مشخص‌شده را با این نمونه به‌عنوان آرگومان می‌گیرد

--------------------

> ```
> مثال:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionType | int | یکی از انواع توابع یک‌آرگومانی متداول |

**بازگشت:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

تابع مشخص‌شده را با این نمونه به‌عنوان آرگومان و آرگومان اضافی مشخص می‌گیرد

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // بازمی‌گرداند لگاریتم 'x' به پایه '5'
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionType | int | یکی از انواع توابع دو‌آرگومانی: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان اضافی بسته به نوع تابع |

**بازگشت:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

تابع مشخص‌شده را با این نمونه به‌عنوان آرگومان و آرگومان اضافی مشخص می‌گیرد

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // بازمی‌گرداند لگاریتم 'x' به پایه '5'
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionType | int | یکی از انواع توابع دو‌آرگومانی: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | آرگومان اضافی بسته به نوع تابع |

**بازگشت:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

یک زیرنویس می‌سازد

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | زیرنویس (شاخص پایین سمت راست) |

**بازگشت:**  
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - عنصر ریاضی جدید از نوع [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

یک زیرنویس می‌سازد

--------------------

> ```
> مثال:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | java.lang.String | زیرنویس (شاخص پایین سمت راست) |

**بازگشت:**  
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - عنصر ریاضی جدید از نوع [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

یک فوق‌نویس می‌سازد

--------------------

> ```
> مثال:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | فوق‌نویس (شاخص بالا سمت راست) |

**بازگشت:**  
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

یک فوق‌نویس می‌سازد

--------------------

> ```
> مثال:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| superscript | java.lang.String | فوق‌نویس (شاخص بالا سمت راست) |

**بازگشت:**  
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

زیرنویس و فوق‌نویس را در سمت راست می‌سازد

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | زیرنویس (شاخص پایین سمت راست) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | فوق‌نویس (شاخص بالا سمت راست) |

**بازگشت:**  
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

زیرنویس و فوق‌نویس را در سمت راست می‌سازد

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | java.lang.String | زیرنویس (شاخص پایین سمت راست) |
| superscript | java.lang.String | فوق‌نویس (شاخص بالا سمت راست) |

**بازگشت:**  
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

زیرنویس و فوق‌نویس را در سمت چپ می‌سازد

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | زیرنویس (شاخص پایین سمت چپ) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | فوق‌نویس (شاخص بالا سمت چپ) |

**بازگشت:**  
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)

### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

زیرنویس و فوق‌نویس را در سمت چپ می‌سازد

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | java.lang.String | زیرنویس (شاخص پایین سمت چپ) |
| superscript | java.lang.String | فوق‌نویس (شاخص بالا سمت چپ) |

**بازگشت:**  
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)

### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

ریشه ریاضی درجه داده را از آرگومان مشخص‌شده محاسبه می‌کند

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان رادیکال |

**بازگشت:**  
[IMathRadical](../../com.aspose.slides/imathradical) - نمونه جدید از نوع [IMathRadical](../../com.aspose.slides/imathradical)

### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

ریشه ریاضی درجه داده را از آرگومان مشخص‌شده محاسبه می‌کند

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| degree | java.lang.String | آرگومان رادیکال |

**بازگشت:**  
[IMathRadical](../../com.aspose.slides/imathradical) - نمونه جدید از نوع [IMathRadical](../../com.aspose.slides/imathradical)

### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

حد بالایی را می‌گیرد

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | حد |

**بازگشت:**  
[IMathLimit](../../com.aspose.slides/imathlimit) - نمونه جدید از نوع [IMathLimit](../../com.aspose.slides/imathlimit)

### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

حد بالایی را می‌گیرد

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| limit | java.lang.String | حد |

**بازگشت:**  
[IMathLimit](../../com.aspose.slides/imathlimit) - نمونه جدید از نوع [IMathLimit](../../com.aspose.slides/imathlimit)

### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

حد پایینی را می‌گیرد

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | حد |

**بازگشت:**  
[IMathLimit](../../com.aspose.slides/imathlimit) - نمونه جدید از نوع [IMathLimit](../../com.aspose.slides/imathlimit)

### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

حد پایینی را می‌گیرد

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| limit | java.lang.String | حد |

**بازگشت:**  
[IMathLimit](../../com.aspose.slides/imathlimit) - نمونه جدید از نوع [IMathLimit](../../com.aspose.slides/imathlimit)

### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

یک عملگر N-ary می‌سازد

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | نوع عملگر N-ary |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد پایین |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد بالا |

**بازگشت:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونه جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

یک عملگر N-ary می‌سازد

--------------------

> ```
> مثال:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | نوع عملگر N-ary |
| lowerLimit | java.lang.String | حد پایین |
| upperLimit | java.lang.String | حد بالا |

**بازگشت:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونه جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

در یک آرایه عمودی می‌گذارد

--------------------

> ``` 
> مثال:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
```

**بازگشت:**  
[IMathArray](../../com.aspose.slides/imatharray) - نمونه جدید از نوع [IMathArray](../../com.aspose.slides/imatharray)

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

انتگرال را می‌گیرد

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | int | نوع انتگرال |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد پایین انتگرال |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد بالا انتگرال |
| limitLocations | int | موقعیت حدود |

**بازگشت:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونه جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

انتگرال را می‌گیرد

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | int | نوع انتگرال |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد پایین انتگرال |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد بالا انتگرال |

**بازگشت:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونه جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

انتگرال را بدون حدود می‌گیرد

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | int | نوع انتگرال |

**بازگشت:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونه جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

انتگرال را می‌گیرد

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | int | نوع انتگرال |
| lowerLimit | java.lang.String | حد پایین انتگرال |
| upperLimit | java.lang.String | حد بالا انتگرال |
| limitLocations | int | موقعیت حدود |

**بازگشت:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونه جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

انتگرال را می‌گیرد

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | int | نوع انتگرال |
| lowerLimit | java.lang.String | حد پایین انتگرال |
| upperLimit | java.lang.String | حد بالا انتگرال |

**بازگشت:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونه جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

یک علامت اکسنت (کاراکتر در بالای این عنصر) تنظیم می‌کند

--------------------

> ``` 
> مثال:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| accentCharacter | char | کاراکتر اکسنت. مقدار باید در بازه (U+0300–U+036F) یا (U+20D0–U+20EF) باشد |

**بازگشت:**  
[IMathAccent](../../com.aspose.slides/imathaccent) - نمونه جدید از نوع [IMathAccent](../../com.aspose.slides/imathaccent)

### overbar() {#overbar--}
```
public final IMathBar overbar()
```

یک خط افقی بر بالای این عنصر قرار می‌دهد

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**بازگشت:**  
[IMathBar](../../com.aspose.slides/imathbar) - نمونه جدید از نوع [IMathBar](../../com.aspose.slides/imathbar)

### underbar() {#underbar--}
```
public final IMathBar underbar()
```

یک خط افقی بر پایین این عنصر قرار می‌دهد

--------------------

> ```
> مثال:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```


**بازگشت:**  
[IMathBar](../../com.aspose.slides/imathbar) - نمونه جدید از نوع [IMathBar](../../com.aspose.slides/imathbar)

### group() {#group--}
```
public final IMathGroupingCharacter group()
```

این عنصر را با استفاده از یک پرانتز منحنی پایین در یک گروه قرار می‌دهد

--------------------

> ```
> مثال:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**بازگشت:**  
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - نمونه جدید از نوع [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)

### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

این عنصر را با استفاده از کاراکتر گروهی (مانند پرانتز منحنی پایین یا سایر) در یک گروه قرار می‌دهد

--------------------

> ```
> مثال:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> 
```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| character | char | کاراکتر گروه‌بندی مانند BOTTOM CURLY BRACKET (U+23DF) یا هر کاراکتر دیگر |
| position | int | موقعیت کاراکتر گروه‌بندی |
| verticalJustification | int | توجیه عمودی کاراکتر گروه. تعیین‌کننده موقعیت شیء نسبت به خط پایه است. به عنوان مثال، وقتی کاراکتر گروه بالای شیء باشد، VerticalJustification برابر Top به این معنی است که بالای شیء بر خط پایه قرار می‌گیرد؛ وقتی برابر Bottom باشد، پایین شیء بر خط پایه است. |

**بازگشت:**  
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - نمونه جدید از نوع [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)

### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

این عنصر را در یک border-box قرار می‌دهد

--------------------

> ```
> مثال:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**بازگشت:**  
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - border-box حاوی این عنصر

### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

این عنصر را در یک border-box قرار می‌دهد

--------------------

> ```
> مثال:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hideTop | boolean | پنهان کردن لبه بالا |
| hideBottom | boolean | پنهان کردن لبه پایین |
| hideLeft | boolean | پنهان کردن لبه چپ |
| hideRight | boolean | پنهان کردن لبه راست |
| strikethroughHorizontal | boolean | خط وسط افقی در Border Box |
| strikethroughVertical | boolean | خط وسط عمودی در Border Box |
| strikethroughBottomLeftToTopRight | boolean | خط وسط از پایین چپ به بالا راست در Border Box |
| strikethroughTopLeftToBottomRight | boolean | خط وسط از بالا چپ به پایین راست در Border Box |

**بازگشت:**  
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - border-box حاوی این عنصر

### toBox() {#toBox--}
```
public final IMathBox toBox()
```

این عنصر را در یک جعبه غیر‌دیداری (گروه‌بندی منطقی) که برای گروه‌بندی اجزای یک معادله یا سایر نمونه‌های متن ریاضی استفاده می‌شود، قرار می‌دهد. یک شیء جعبه‌بندی‌شده می‌تواند (به عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز، به‌عنوان نقطهٔ شکست خط یا برای جلوگیری از شکست خط درون گروه‌بندی شود.

--------------------

> ```
> مثال:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**بازگشت:**  
[IMathBox](../../com.aspose.slides/imathbox) - جعبه منطقی حاوی این عنصر

### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

دریافت عناصر فرزند

**بازگشت:**  
com.aspose.slides.IMathElement[] - آرایه‌ای از [IMathElement](../../com.aspose.slides/imathelement)