---
title: IMathElement
second_title: Aspose.Slides for Java API Reference
description: رابط پایه هر عنصر ریاضی شامل کسر، متن ریاضی، تابع، عبارت با چند عنصر و غیره
type: docs
url: /fa/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

رابط پایه هر عنصر ریاضی: کسر، متن ریاضی، تابع، عبارت با چند عنصر و غیره

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
> ```

## متدها

| متد | توضیح |
| --- | --- |
| [getChildren()](#getChildren--) | دریافت عناصر فرزند |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| [join(String mathText)](#join-java.lang.String-) | یک متن ریاضی را می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | یک کسر با صورت این و مخرج مشخص ایجاد می‌کند |
| [divide(String denominator)](#divide-java.lang.String-) | یک کسر با صورت این و مخرج مشخص ایجاد می‌کند |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | یک کسر از نوع مشخص با صورت این و مخرج مشخص ایجاد می‌کند |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | یک کسر از نوع مشخص با صورت این و مخرج مشخص ایجاد می‌کند |
| [enclose()](#enclose--) | یک عنصر ریاضی را در پرانتز می‌گذارد |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | این عنصر را در کاراکترهای مشخص مانند پرانتز یا کاراکترهای دیگر به عنوان قاب می‌گذارد |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | یک تابع از یک آرگومان می‌گیرد که این نمونه به عنوان نام تابع استفاده می‌شود |
| [function(String functionArgument)](#function-java.lang.String-) | یک تابع از یک آرگومان می‌گیرد که این نمونه به عنوان نام تابع استفاده می‌شود |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | یک تابع مشخص را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | یک تابع مشخص را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | یک تابع مشخص را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | یک تابع مشخص را می‌گیرد که این نمونه به عنوان آرگومان و آرگومان اضافی مشخص استفاده می‌شود |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | یک تابع مشخص را می‌گیرد که این نمونه به عنوان آرگومان و آرگومان اضافی مشخص استفاده می‌شود |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | زیرنویس ایجاد می‌کند |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | زیرنویس ایجاد می‌کند |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | بالانویس ایجاد می‌کند |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | بالانویس ایجاد می‌کند |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | زیرنویس و بالا نویس را در سمت راست ایجاد می‌کند |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | زیرنویس و بالا نویس را در سمت راست ایجاد می‌کند |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | زیرنویس و بالا نویس را در سمت چپ ایجاد می‌کند |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | زیرنویس و بالا نویس را در سمت چپ ایجاد می‌کند |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | ریشه ریاضی از درجهٔ داده‌شده را از آرگومان مشخص تعیین می‌کند |
| [radical(String degree)](#radical-java.lang.String-) | ریشه ریاضی از درجهٔ داده‌شده را از آرگومان مشخص تعیین می‌کند |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | حد بالا را می‌گیرد |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | حد بالا را می‌گیرد |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | حد پایین را می‌گیرد |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | حد پایین را می‌گیرد |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | یک عملگر N-آری ایجاد می‌کند |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | یک عملگر N-آری ایجاد می‌کند |
| [toMathArray()](#toMathArray--) | یک آرایه عمودی قرار می‌دهد |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | انتگرال را می‌گیرد |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | انتگرال را می‌گیرد |
| [integral(int integralType)](#integral-int-) | انتگرال را بدون حدود می‌گیرد |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | انتگرال را می‌گیرد |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | انتگرال را می‌گیرد |
| [accent(char accentCharacter)](#accent-char-) | یک علامت لهجه (کاراکتر در بالای این عنصر) تنظیم می‌کند |
| [overbar()](#overbar--) | یک خط در بالای این عنصر تنظیم می‌کند |
| [underbar()](#underbar--) | یک خط در پایین این عنصر تنظیم می‌کند |
| [group()](#group--) | این عنصر را در یک گروه با استفاده از پرانتز خم پایین قرار می‌دهد |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | این عنصر را در یک گروه با استفاده از کاراکتر گروه‌بندی مانند پرانتز خم پایین یا دیگر کاراکترها قرار می‌دهد |
| [toBorderBox()](#toBorderBox--) | این عنصر را در یک جعبه حاشیه‌ای قرار می‌دهد |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | این عنصر را در یک جعبه حاشیه‌ای قرار می‌دهد |
| [toBox()](#toBox--) | این عنصر را در یک جعبه غیر بصری (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی مؤلفه‌های یک معادله یا نمونهٔ دیگر متن ریاضی استفاده می‌شود |

### getChildren() {#getChildren--}
```
public abstract IMathElement[] getChildren()
```

دریافت عناصر فرزند

**بازگشت:**
com.aspose.slides.IMathElement[]

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock join(IMathElement mathElement)
```

یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد

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
[IMathBlock](../../com.aspose.slides/imathblock) - یک IMathBlock جدید که شامل این نمونه و آرگومان مشخص است

### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
```

یک متن ریاضی را می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد

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
[IMathBlock](../../com.aspose.slides/imathblock) - یک IMathBlock جدید که شامل این نمونه و آرگومان مشخص است

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction divide(IMathElement denominator)
```

یک کسر با صورت این و مخرج مشخص ایجاد می‌کند

--------------------

> ```
> Example:
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
public abstract IMathFraction divide(String denominator)
```

یک کسر با صورت این و مخرج مشخص ایجاد می‌کند

--------------------

> ```
> Example:
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
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
```

یک کسر از نوع مشخص با صورت این و مخرج مشخص ایجاد می‌کند

--------------------

> ```
> Example:
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
public abstract IMathFraction divide(String denominator, int fractionType)
```

یک کسر از نوع مشخص با صورت این و مخرج مشخص ایجاد می‌کند

--------------------

> ```
> Example:
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
public abstract IMathDelimiter enclose()
```

یک عنصر ریاضی را در پرانتز می‌گذارد

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```


**بازگشت:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر ریاضی از نوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) که شامل پرانتز است

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

این عنصر را در کاراکترهای مشخص مانند پرانتز یا کاراکترهای دیگر به عنوان قاب می‌گذارد

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
| beginningCharacter | char | کاراکتر ابتدایی (معمولاً پرانتز باز) |
| endingCharacter | char | کاراکتر انتهایی (معمولاً پرانتز بسته) |

**بازگشت:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر ریاضی از نوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) که شامل کاراکترهای مشخص به عنوان قاب است

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```

یک تابع از یک آرگومان می‌گیرد که این نمونه به عنوان نام تابع استفاده می‌شود

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
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | یک آرگومان از تابع |

**بازگشت:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)

### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```

یک تابع از یک آرگومان می‌گیرد که این نمونه به عنوان نام تابع استفاده می‌شود

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
| functionArgument | java.lang.String | یک آرگومان از تابع |

**بازگشت:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
```

یک تابع مشخص را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود

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
public abstract IMathFunction asArgumentOfFunction(String functionName)
```

یک تابع مشخص را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود

--------------------

> ```
> Example:
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
public abstract IMathFunction asArgumentOfFunction(int functionType)
```

یک تابع مشخص را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود

--------------------

> ```
> مثال:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionType | int | یکی از انواع توابع عمومی با یک آرگومان |

**بازگشت:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

یک تابع مشخص را می‌گیرد که این نمونه به عنوان آرگومان و آرگومان اضافی بسته به نوع تابع استفاده می‌شود

--------------------

> ```
> مثال:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // لگاریتم 'x' به پایه '5' را بر می‌گرداند
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionType | int | یکی از انواع توابع عمومی با دو آرگومان: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان اضافی بسته به نوع تابع |

**بازگشت:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

یک تابع مشخص را می‌گیرد که این نمونه به عنوان آرگومان و آرگومان اضافی بسته به نوع تابع استفاده می‌شود

--------------------

> ```
> مثال:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // لگاریتم 'x' به پایه '5' را بر می‌گرداند
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionType | int | یکی از انواع توابع عمومی با دو آرگومان: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | آرگومان اضافی بسته به نوع تابع |

**بازگشت:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
```

زیرنویس ایجاد می‌کند

--------------------

> ```
> مثال:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | زیرنویس (اندیس پایین سمت راست) |

**بازگشت:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - عنصر ریاضی جدید از نوع [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
```

زیرنویس ایجاد می‌کند

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
| subscript | java.lang.String | زیرنویس (اندیس پایین سمت راست) |

**بازگشت:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - عنصر ریاضی جدید از نوع [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

بالانویس ایجاد می‌کند

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
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | بالانویس (اندیس بالا سمت راست) |

**بازگشت:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
```

بالانویس ایجاد می‌کند

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
| superscript | java.lang.String | بالانویس (اندیس بالا سمت راست) |

**بازگشت:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

زیرنویس و بالا نویس را در سمت راست ایجاد می‌کند

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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | زیرنویس (اندیس پایین سمت راست) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | بالانویس (اندیس بالا سمت راست) |

**بازگشت:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```
Creates subscript and superscript on the right
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
| subscript | java.lang.String | زیرنویس (اندیس پایین سمت راست) |
| superscript | java.lang.String | بالانویس (اندیس بالا سمت راست) |

**بازگشت:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Creates subscript and superscript on the left
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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | زیرنویس (اندیس پایین سمت چپ) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | بالانویس (اندیس بالا سمت چپ) |

**بازگشت:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Creates subscript and superscript on the left
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
| subscript | java.lang.String | زیرنویس (اندیس پایین سمت چپ) |
| superscript | java.lang.String | بالانویس (اندیس بالا سمت چپ) |

**بازگشت:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```

Specifies the mathematical root of the given degree from the specified argument.
--------------------

> ```
> Example:
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
[IMathRadical](../../com.aspose.slides/imathradical) - نمونهٔ جدید از نوع [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```

Specifies the mathematical root of the given degree from the specified argument.
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
[IMathRadical](../../com.aspose.slides/imathradical) - نمونهٔ جدید از نوع [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```

Takes upper limit
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
[IMathLimit](../../com.aspose.slides/imathlimit) - نمونهٔ جدید از نوع [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```

Takes upper limit
--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| limit | java.lang.String | حد |

**بازگشت:**
[IMathLimit](../../com.aspose.slides/imathlimit) - نمونهٔ جدید از نوع [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```

Takes lower limit
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
[IMathLimit](../../com.aspose.slides/imathlimit) - نمونهٔ جدید از نوع [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```

Takes lower limit
--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| limit | java.lang.String | حد |

**بازگشت:**
[IMathLimit](../../com.aspose.slides/imathlimit) - نمونهٔ جدید از نوع [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Creates a N-ary operator
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
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونهٔ جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Creates a N-ary operator
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
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونهٔ جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```

Puts in a vertical array
--------------------

> ```
> مثال:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```


**بازگشت:**
[IMathArray](../../com.aspose.slides/imatharray) - نمونهٔ جدید از نوع [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Takes the integral
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
| limitLocations | int | مکان حدود |

**بازگشت:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونهٔ جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Takes the integral
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

**بازگشت:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونهٔ جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```

Takes the integral without limits
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
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونهٔ جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Takes the integral
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
| limitLocations | int | مکان حدود |

**بازگشت:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونهٔ جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Takes the integral
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
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونهٔ جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```

Sets an accent mark (a character on the top of this element)
--------------------

> ```
> مثال:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| accentCharacter | char | کاراکتر آکسنت. مقدار باید در بازهٔ (U+0300\u2013U+036F) یا (U+20D0\u2013U+20EF) باشد |

**بازگشت:**
[IMathAccent](../../com.aspose.slides/imathaccent) - نمونهٔ جدید از نوع [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```

Sets a bar on the top of this element
--------------------

> ```
> مثال:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**بازگشت:**
[IMathBar](../../com.aspose.slides/imathbar) - نمونهٔ جدید از نوع [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```

Sets a bar on the bottom of this element
--------------------

> ```
> مثال:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**بازگشت:**
[IMathBar](../../com.aspose.slides/imathbar) - نمونهٔ جدید از نوع [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```

Places this element in a group using a bottom curly bracket
--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**بازگشت:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - نمونهٔ جدید از نوع [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Places this element in a group using a grouping character such as bottom curly bracket or another
--------------------

> ```
> مثال:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| character | char | کاراکتر گروه‌بندی مانند BOTTOM CURLY BRACKET (U+23DF) یا هر کاراکتر دیگر |
| position | int | موقعیت کاراکتر گروه‌بندی |
| verticalJustification | int | تراست عمودی کاراکتر گروه. تنظیم تراز شیء نسبت به خط پایه را مشخص می‌کند. به عنوان مثال، وقتی کاراکتر گروه بالای شیء باشد، VerticalJustification مقدار Top نشان می‌دهد که بالای شیء بر خط پایه قرار می‌گیرد؛ وقتی VerticalJustification مقدار Bottom باشد، پایین شیء بر خط پایه خواهد بود |

**بازگشت:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - نمونهٔ جدید از نوع [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```

Places this element in a border-box
--------------------

> ```
> مثال:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**بازگشت:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box with this element placed inside
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Places this element in a border-box
--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hideTop | boolean | مخفی‌سازی لبهٔ بالا |
| hideBottom | boolean | مخفی‌سازی لبهٔ پایین |
| hideLeft | boolean | مخفی‌سازی لبهٔ چپ |
| hideRight | boolean | مخفی‌سازی لبهٔ راست |
| strikethroughHorizontal | boolean | خط‌خورده افقی Border Box |
| strikethroughVertical | boolean | خط‌خورده عمودی Border Box |
| strikethroughBottomLeftToTopRight | boolean | خط‌خورده از پایین چپ به بالا راست Border Box |
| strikethroughTopLeftToBottomRight | boolean | خط‌خورده از بالا چپ به پایین راست Border Box |

**بازگشت:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box with this element placed inside
### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```

Places this element in a non-visual box (logical grouping) which is used to group components of an equation or other instance of mathematical text. A boxed object can (for example) serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within.
--------------------

> ```
> مثال:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```


**بازگشت:**
[IMathBox](../../com.aspose.slides/imathbox) - Logical box with this element placed inside