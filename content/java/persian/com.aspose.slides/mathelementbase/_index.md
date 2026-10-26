---
title: MathElementBase
second_title: مرجع API Aspose.Slides برای Java
description: کلاس پایه برای IMathElement با پیاده‌سازی برخی متدهایی که برای تمام کلاس‌های ارث‌بری مشترک هستند. فقط برای استفاده داخلی.
type: docs
url: /fa/com.aspose.slides/mathelementbase/
---
**ارث‌بری:**
java.lang.Object

**همهٔ رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

کلاس پایه برای IMathElement با پیاده‌سازی برخی متدهایی که برای تمام کلاس‌های ارث‌برده مشترک است. فقط برای استفاده داخلی. کلاس ارث‌برده باید IMathElement باشد.
## متدها

| متد | توضیح |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | شی Parent_Immediate را برمی‌گرداند. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی ایجاد می‌کند. |
| [join(String mathText)](#join-java.lang.String-) | یک متن ریاضی را می‌پیوندد و یک بلوک ریاضی ایجاد می‌کند. |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | کسر را با این صورت و مخرج مشخص‌شده ایجاد می‌کند. |
| [divide(String denominator)](#divide-java.lang.String-) | کسر را با این صورت و مخرج مشخص‌شده ایجاد می‌کند. |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | کسر از نوع مشخص‌شده را با این صورت و مخرج مشخص‌شده ایجاد می‌کند. |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | کسر از نوع مشخص‌شده را با این صورت و مخرج مشخص‌شده ایجاد می‌کند. |
| [enclose()](#enclose--) | یک عنصر ریاضی را در پرانتز می‌گیرد. |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | یک عنصر ریاضی را در کاراکترهای مشخص‌شده مانند پرانتز یا کاراکترهای دیگر به‌عنوان قاب می‌گیرد. |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | تابعی از یک آرگومان می‌گیرد که این نمونه به‌عنوان نام تابع استفاده می‌شود. |
| [function(String functionArgument)](#function-java.lang.String-) | تابعی از یک آرگومان می‌گیرد که این نمونه به‌عنوان نام تابع استفاده می‌شود. |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | تابع مشخص‌شده‌ای را می‌گیرد که این نمونه به‌عنوان آرگومان استفاده می‌شود. |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | تابع مشخص‌شده‌ای را می‌گیرد که این نمونه به‌عنوان آرگومان استفاده می‌شود. |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | تابع مشخص‌شده‌ای را می‌گیرد که این نمونه به‌عنوان آرگومان استفاده می‌شود. |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | تابع مشخص‌شده‌ای را می‌گیرد که این نمونه به‌عنوان آرگومان و آرگومان اضافهٔ مشخص‌شده استفاده می‌شود. |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | تابع مشخص‌شده‌ای را می‌گیرد که این نمونه به‌عنوان آرگومان و آرگومان اضافهٔ مشخص‌شده استفاده می‌شود. |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | زیرنویس ایجاد می‌کند. |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | زیرنویس ایجاد می‌کند. |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | بالانویس ایجاد می‌کند. |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | بالانویس ایجاد می‌کند. |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند. |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند. |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند. |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند. |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | ریشهٔ ریاضیاتی از درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| [radical(String degree)](#radical-java.lang.String-) | ریشهٔ ریاضیاتی از درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | حد بالایی را می‌گیرد. |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | حد بالایی را می‌گیرد. |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | حد پایینی را می‌گیرد. |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | حد پایینی را می‌گیرد. |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | یک عملگر N-آری ایجاد می‌کند. |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | یک عملگر N-آری ایجاد می‌کند. |
| [toMathArray()](#toMathArray--) | در یک آرایهٔ عمودی قرار می‌دهد. |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | انتگرال را می‌گیرد. |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | انتگرال را می‌گیرد. |
| [integral(int integralType)](#integral-int-) | انتگرال بدون حد را می‌گیرد. |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | انتگرال را می‌گیرد. |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | انتگرال را می‌گیرد. |
| [accent(char accentCharacter)](#accent-char-) | یک علامت اکسنت (کاراکتر در بالای این عنصر) تنظیم می‌کند. |
| [overbar()](#overbar--) | یک خط در بالای این عنصر تنظیم می‌کند. |
| [underbar()](#underbar--) | یک خط در پایین این عنصر تنظیم می‌کند. |
| [group()](#group--) | این عنصر را با استفاده از قلاب‌کلفت پایین در یک گروه قرار می‌دهد. |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | این عنصر را با استفاده از کاراکتر گروه‌بندی مانند قلاب‌کلفت پایین یا کاراکتر دیگر در یک گروه قرار می‌دهد. |
| [toBorderBox()](#toBorderBox--) | این عنصر را در یک جعبهٔ حاشیه‌ای قرار می‌دهد. |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | این عنصر را در یک جعبهٔ حاشیه‌ای قرار می‌دهد. |
| [toBox()](#toBox--) | این عنصر را در یک جعبهٔ غیرقابل مشاهده (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی مؤلفه‌های یک معادله یا سایر نمونه‌های متن ریاضی استفاده می‌شود. |
| [getChildren()](#getChildren--) | دریافت عناصر فرزند |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```


شی Parent_Immediate را برمی‌گرداند. IDOMObject فقط‌خواندنی.

**بازگشت:**
com.aspose.slides.IDOMObject
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```


یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی ایجاد می‌کند.

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
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | عنصری که باید پیوسته شود |

**بازگشت:**
[IMathBlock](../../com.aspose.slides/imathblock) - یک IMathBlock جدید که این نمونه و آرگومان مشخص‌شده را شامل می‌شود
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```


یک متن ریاضی را می‌پیوندد و یک بلوک ریاضی ایجاد می‌کند.

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
| mathText | java.lang.String | متن ریاضی که باید پیوسته شود |

**بازگشت:**
[IMathBlock](../../com.aspose.slides/imathblock) - یک IMathBlock جدید که این نمونه و آرگومان مشخص‌شده را شامل می‌شود
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```


کسر را با این صورت و مخرج مشخص‌شده ایجاد می‌کند.

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
public final IMathFraction divide(String denominator)
```


کسر را با این صورت و مخرج مشخص‌شده ایجاد می‌کند.

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
public final IMathFraction divide(IMathElement denominator, int fractionType)
```


کسر از نوع مشخص‌شده را با این صورت و مخرج مشخص‌شده ایجاد می‌کند.

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
public final IMathFraction divide(String denominator, int fractionType)
```


کسر از نوع مشخص‌شده را با این صورت و مخرج مشخص‌شده ایجاد می‌کند.

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
public final IMathDelimiter enclose()
```


یک عنصر ریاضی را در پرانتز می‌گیرد.

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
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```


یک عنصر ریاضی را در کاراکترهای مشخص‌شده مانند پرانتز یا کاراکترهای دیگر به‌عنوان قاب می‌گیرد.

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| beginningCharacter | char | کاراکتر شروع (معمولاً پرانتز چپ) |
| endingCharacter | char | کاراکتر پایان (معمولاً پرانتز راست) |

**بازگشت:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر ریاضی از نوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) که شامل کاراکترهای مشخص‌شده به‌عنوان قاب است
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```


تابعی از یک آرگومان می‌گیرد که این نمونه به‌عنوان نام تابع استفاده می‌شود.

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان تابع |

**بازگشت:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)
### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```


تابعی از یک آرگومان می‌گیرد که این نمونه به‌عنوان نام تابع استفاده می‌شود.

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
| functionArgument | java.lang.String | آرگومان تابع |

**بازگشت:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```


تابع مشخص‌شده‌ای را می‌گیرد که این نمونه به‌عنوان آرگومان استفاده می‌شود.

--------------------

> ```
> Example:
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


تابع مشخص‌شده‌ای را می‌گیرد که این نمونه به‌عنوان آرگومان استفاده می‌شود.

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


تابع مشخص‌شده‌ای را می‌گیرد که این نمونه به‌عنوان آرگومان استفاده می‌شود.

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
| functionType | int | یکی از انواع توابع مشترک تک آرگومان |

**بازگشت:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```


تابع مشخص‌شده‌ای را می‌گیرد که این نمونه به‌عنوان آرگومان و آرگومان اضافهٔ مشخص‌شده استفاده می‌شود.

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // مقدار لگاریتم 'x' به پایه '5' را برمی‌گرداند
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionType | int | یکی از انواع توابع مشترک دو آرگومان: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان اضافه بسته به نوع تابع |

**بازگشت:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```


تابع مشخص‌شده‌ای را می‌گیرد که این نمونه به‌عنوان آرگومان و آرگومان اضافهٔ مشخص‌شده استفاده می‌شود.

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // مقدار لگاریتم 'x' به پایه '5' را برمی‌گرداند
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionType | int | یکی از انواع توابع مشترک دو آرگومان: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | آرگومان اضافه بسته به نوع تابع |

**بازگشت:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```


زیرنویس ایجاد می‌کند.

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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | زیرنویس (نمایهٔ پایین سمت راست) |

**بازگشت:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - عنصر ریاضی جدید از نوع [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```


زیرنویس ایجاد می‌کند.

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
| subscript | java.lang.String | زیرنویس (نمایهٔ پایین سمت راست) |

**بازگشت:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - عنصر ریاضی جدید از نوع [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```


بالانویس ایجاد می‌کند.

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
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | بالانویس (نمایهٔ بالا سمت راست) |

**بازگشت:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```


بالانویس ایجاد می‌کند.

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
| superscript | java.lang.String | بالانویس (نمایهٔ بالا سمت راست) |

**بازگشت:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```


زیرنویس و بالانویس را در سمت راست ایجاد می‌کند.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | زیرنویس (نمایهٔ پایین سمت راست) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | بالانویس (نمایهٔ بالا سمت راست) |

**بازگشت:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```
> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | java.lang.String | پایین‌نویس (اندیس پایین سمت راست) |
| superscript | java.lang.String | بالا‌نویس (اندیس بالا سمت راست) |

**بازگشت:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

پایین‌نویس و بالا‌نویس را در سمت چپ ایجاد می‌کند

---

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | پایین‌نویس (اندیس پایین سمت چپ) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | بالا‌نویس (اندیس بالا سمت چپ) |

**بازگشت:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

پایین‌نویس و بالا‌نویس را در سمت چپ ایجاد می‌کند

---

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | java.lang.String | پایین‌نویس (اندیس پایین سمت چپ) |
| superscript | java.lang.String | بالا‌نویس (اندیس بالا سمت چپ) |

**بازگشت:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

ریشه ریاضی برای درجه‌ی داده‌شده از آرگومان مشخص‌شده را تعیین می‌کند.

---

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

ریشه ریاضی برای درجه‌ی داده‌شده از آرگومان مشخص‌شده را تعیین می‌کند.

---

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

---

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

---

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
[IMathLimit](../../com.aspose.slides/imathlimit) - نمونه جدید از نوع [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

حد پایین را می‌گیرد

---

> ```
public final IMathLimit setLowerLimit(IMathElement limit)
```

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

حد پایین را می‌گیرد

---

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

یک اپراتور N-ary ایجاد می‌کند

---

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | نوع اپراتور N-ary |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد پایین |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد بالا |

**بازگشت:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونه جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

یک اپراتور N-ary ایجاد می‌کند

---

> ```
> مثال:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | نوع اپراتور N-ary |
| lowerLimit | java.lang.String | حد پایین |
| upperLimit | java.lang.String | حد بالا |

**بازگشت:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونه جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

یک آرایه عمودی قرار می‌دهد

---

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**بازگشت:**
[IMathArray](../../com.aspose.slides/imatharray) - نمونه جدید از نوع [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

انتگرال را می‌گیرد

---

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
| limitLocations | int | محل محدودیت‌ها |

**بازگشت:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونه جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

انتگرال را می‌گیرد

---

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
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونه جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

انتگرال را بدون حد می‌گیرد

---

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

---

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
| limitLocations | int | محل محدودیت‌ها |

**بازگشت:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونه جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

انتگرال را می‌گیرد

---

> ```
> Example:
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

یک علامت حواشی (یک کاراکتر در بالای این عنصر) تنظیم می‌کند

---

> ```
> مثال:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| accentCharacter | char | کاراکتر حواشی. مقدار باید در بازه (U+0300\\u2013U+036F) یا (U+20D0\\u2013U+20EF) باشد |

**بازگشت:**
[IMathAccent](../../com.aspose.slides/imathaccent) - نمونه جدید از نوع [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public final IMathBar overbar()
```

یک خط بالا را بر روی این عنصر تنظیم می‌کند

---

> ```
public final IMathBar overbar()
```

**بازگشت:**
[IMathBar](../../com.aspose.slides/imathbar) - نمونه جدید از نوع [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public final IMathBar underbar()
```

یک خط زیر را بر روی این عنصر تنظیم می‌کند

---

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

این عنصر را با استفاده از کروشه‌ی منحنی پایین در یک گروه قرار می‌دهد

---

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

این عنصر را با استفاده از کاراکتر گروه‌بندی مانند کروشه‌ی منحنی پایین یا دیگر در یک گروه قرار می‌دهد

---

> ```
> مثال:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| character | char | کاراکتر گروه‌بندی مانند کروشه‌ی منحنی پایین (U+23DF) یا هر کاراکتر دیگر |
| position | int | موقعیت کاراکتر گروه‌بندی |
| verticalJustification | int | تسطیح عمودی کاراکتر گروه. محل‌گذاری شیء نسبت به خط پایه را مشخص می‌کند. به عنوان مثال، وقتی کاراکتر گروه بالای شیء باشد، VerticalJustification مقدار Top نشان می‌دهد که بالای شیء بر خط پایه قرار می‌گیرد؛ وقتی VerticalJustification مقدار Bottom باشد، پایین شیء بر خط پایه قرار می‌گیرد |

**بازگشت:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - نمونه جدید از نوع [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

این عنصر را در یک جعبه‌ی مرزی قرار می‌دهد

---

> ```
> مثال:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```


**بازگشت:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - جعبه‌ی مرزی با این عنصر داخل آن
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

جعبه‌ی مرزی با این عنصر داخل آن

---

> ```
> مثال:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hideTop | boolean | پنهان کردن لبه بالایی |
| hideBottom | boolean | پنهان کردن لبه پایینی |
| hideLeft | boolean | پنهان کردن لبه چپ |
| hideRight | boolean | پنهان کردن لبه راست |
| strikethroughHorizontal | boolean | خط‌خورده افقی جعبه‌ی مرزی |
| strikethroughVertical | boolean | خط‌خورده عمودی جعبه‌ی مرزی |
| strikethroughBottomLeftToTopRight | boolean | خط‌خورده از پایین چپ به بالا راست جعبه‌ی مرزی |
| strikethroughTopLeftToBottomRight | boolean | خط‌خورده از بالا چپ به پایین راست جعبه‌ی مرزی |

**بازگشت:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - جعبه‌ی مرزی با این عنصر داخل آن
### toBox() {#toBox--}
```
public final IMathBox toBox()
```

این عنصر را در یک جعبه‌ی غیر‌نمایشی (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی مؤلفه‌های یک معادله یا سایر متن‌های ریاضی استفاده می‌شود. یک شیء داخل جعبه می‌تواند (به عنوان مثال) به عنوان شبیه‌ساز عملگر با یا بدون نقطه تراز عمل کند، به عنوان نقطه شکست خط عمل کند، یا به گونه‌ای گروه‌بندی شود که از شکست خط داخل آن جلوگیری شود.

---

> ```
> مثال:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**بازگشت:**
[IMathBox](../../com.aspose.slides/imathbox) - جعبه‌ی منطقی با این عنصر داخل آن
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

دریافت عناصر فرزند

**بازگشت:**
com.aspose.slides.IMathElement[] - آرایه‌ای از [IMathElement](../../com.aspose.slides/imathelement)