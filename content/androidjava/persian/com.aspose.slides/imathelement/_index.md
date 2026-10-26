---
title: IMathElement
second_title: Aspose.Slides for Android via Java API Reference
description: رابط پایهٔ هر عنصر ریاضی شامل کسر، متن ریاضی، تابع، عبارت با عناصر متعدد و غیره
type: docs
url: /fa/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

رابط پایهٔ هر عنصر ریاضی: کسر، متن ریاضی، تابع، عبارت با عناصر متعدد و غیره

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
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | ترکیب یک عنصر ریاضی و ایجاد یک بلوک ریاضی |
| [join(String mathText)](#join-java.lang.String-) | ترکیب یک متن ریاضی و ایجاد یک بلوک ریاضی |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | ایجاد یک کسر با صورت فعلی و مخرج مشخص |
| [divide(String denominator)](#divide-java.lang.String-) | ایجاد یک کسر با صورت فعلی و مخرج مشخص |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | ایجاد یک کسر از نوع مشخص با صورت فعلی و مخرج مشخص |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | ایجاد یک کسر از نوع مشخص با صورت فعلی و مخرج مشخص |
| [enclose()](#enclose--) | محاط کردن یک عنصر ریاضی در پرانتز |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | محاط کردن این عنصر در کاراکترهای مشخص شده مانند پرانتز یا کاراکترهای دیگر به عنوان قاب |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | دریافت یک تابع برای آرگومان با استفاده از این نمونه به عنوان نام تابع |
| [function(String functionArgument)](#function-java.lang.String-) | دریافت یک تابع برای آرگومان با استفاده از این نمونه به عنوان نام تابع |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | دریافت تابع مشخص شده با استفاده از این نمونه به عنوان آرگومان |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | دریافت تابع مشخص شده با استفاده از این نمونه به عنوان آرگومان |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | دریافت تابع مشخص شده با استفاده از این نمونه به عنوان آرگومان |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | دریافت تابع مشخص شده با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافی مشخص |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | دریافت تابع مشخص شده با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافی مشخص |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | ایجاد زیرنویس |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | ایجاد زیرنویس |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | ایجاد بالانویس |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | ایجاد بالانویس |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ایجاد زیرنویس و بالانویس در سمت راست |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | ایجاد زیرنویس و بالانویس در سمت راست |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ایجاد زیرنویس و بالانویس در سمت چپ |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | ایجاد زیرنویس و بالانویس در سمت چپ |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | تعیین ریشهٔ ریاضی از درجهٔ داده شده برای آرگومان مشخص شده |
| [radical(String degree)](#radical-java.lang.String-) | تعیین ریشهٔ ریاضی از درجهٔ داده شده برای آرگومان مشخص شده |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | دریافت حد بالا |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | دریافت حد بالا |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | دریافت حد پایین |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | دریافت حد پایین |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ایجاد یک عملگر N-ary |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | ایجاد یک عملگر N-ary |
| [toMathArray()](#toMathArray--) | قرار دادن در آرایهٔ عمودی |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | دریافت انتگرال |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | دریافت انتگرال |
| [integral(int integralType)](#integral-int-) | دریافت انتگرال بدون حد |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | دریافت انتگرال |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | دریافت انتگرال |
| [accent(char accentCharacter)](#accent-char-) | تنظیم یک علامت لهجه (کاراکتر در بالای این عنصر) |
| [overbar()](#overbar--) | تنظیم یک خط بالا بر روی این عنصر |
| [underbar()](#underbar--) | تنظیم یک خط پایین بر روی این عنصر |
| [group()](#group--) | قرار دادن این عنصر در یک گروه با استفاده از براکت منحنی پایین |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | قرار دادن این عنصر در یک گروه با استفاده از کاراکتر گروه‌بندی مانند براکت منحنی پایین یا کاراکتر دیگر |
| [toBorderBox()](#toBorderBox--) | قرار دادن این عنصر در یک جعبه‌حاشیه‌ای |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | قرار دادن این عنصر در یک جعبه‌حاشیه‌ای |
| [toBox()](#toBox--) | قرار دادن این عنصر در یک جعبه غیر‌دیداری (گروه‌بندی منطقی) که برای گروه‌بندی اجزای یک معادله یا نمونه دیگر متن ریاضی استفاده می‌شود |
### getChildren() {#getChildren--}
```
public abstract IMathElement[] getChildren()
```

دریافت عناصر فرزند

**بازمی‌گرداند:**
com.aspose.slides.IMathElement[]
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock join(IMathElement mathElement)
```

ترکیب یک عنصر ریاضی و ایجاد یک بلوک ریاضی

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
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | عنصری که باید ترکیب شود |

**بازمی‌گرداند:**
[IMathBlock](../../com.aspose.slides/imathblock) - یک IMathBlock جدید حاوی این نمونه و آرگومان مشخص شده
### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
```

ترکیب یک متن ریاضی و ایجاد یک بلوک ریاضی

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
| mathText | java.lang.String | متن ریاضی که باید ترکیب شود |

**بازمی‌گرداند:**
[IMathBlock](../../com.aspose.slides/imathblock) - یک IMathBlock جدید حاوی این نمونه و آرگومان مشخص شده
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction divide(IMathElement denominator)
```

ایجاد یک کسر با صورت فعلی و مخرج مشخص

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

**بازمی‌گرداند:**
[IMathFraction](../../com.aspose.slides/imathfraction) - کسر جدید
### divide(String denominator) {#divide-java.lang.String-}
```
public abstract IMathFraction divide(String denominator)
```

ایجاد یک کسر با صورت فعلی و مخرج مشخص

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

**بازمی‌گرداند:**
[IMathFraction](../../com.aspose.slides/imathfraction) - کسر جدید
### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
```

ایجاد یک کسر از نوع مشخص با صورت فعلی و مخرج مشخص

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

**بازمی‌گرداند:**
[IMathFraction](../../com.aspose.slides/imathfraction) - کسر جدید
### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public abstract IMathFraction divide(String denominator, int fractionType)
```

ایجاد یک کسر از نوع مشخص با صورت فعلی و مخرج مشخص

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

**بازمی‌گرداند:**
[IMathFraction](../../com.aspose.slides/imathfraction) - کسر جدید
### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
```

محاط کردن یک عنصر ریاضی در پرانتز

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**بازمی‌گرداند:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر ریاضی از نوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) که شامل پرانتز است
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

محاط کردن این عنصر در کاراکترهای مشخص شده مانند پرانتز یا کاراکترهای دیگر به عنوان قاب

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
| beginningCharacter | char | کاراکتر شروع (معمولاً براکت سمت چپ) |
| endingCharacter | char | کاراکتر پایان (معمولاً براکت سمت راست) |

**بازمی‌گرداند:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر ریاضی از نوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) که شامل کاراکترهای مشخص شده به عنوان قاب است
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```

دریافت تابعی برای آرگومان با استفاده از این نمونه به عنوان نام تابع

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
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | یک آرگومان برای تابع |

**بازمی‌گرداند:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)
### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```

دریافت تابعی برای آرگومان با استفاده از این نمونه به عنوان نام تابع

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionArgument | java.lang.String | یک آرگومان برای تابع |

**بازمی‌گرداند:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
```

دریافت تابع مشخص شده با استفاده از این نمونه به عنوان آرگومان

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

**بازمی‌گرداند:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(String functionName)
```

دریافت تابع مشخص شده با استفاده از این نمونه به عنوان آرگومان

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

**بازمی‌گرداند:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType)
```

دریافت تابع مشخص شده با استفاده از این نمونه به عنوان آرگومان

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
| functionType | int | یکی از نوع‌های رایج تابع با یک آرگومان |

**بازمی‌گرداند:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

دریافت تابع مشخص شده با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافی مشخص

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // بازگشت لگاریتم 'x' به پایه '5'
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionType | int | یکی از نوع‌های رایج تابع با دو آرگومان: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان اضافی بسته به نوع تابع |

**بازمی‌گرداند:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

دریافت تابع مشخص شده با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافی مشخص

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // لگاریتم 'x' به پایه '5' را برمی‌گرداند
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionType | int | یکی از نوع‌های رایج تابع با دو آرگومان: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | آرگومان اضافی بسته به نوع تابع |

**بازمی‌گرداند:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر ریاضی جدید از نوع [IMathFunction](../../com.aspose.slides/imathfunction)
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
```

ایجاد زیرنویس

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

**بازمی‌گرداند:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - عنصر ریاضی جدید از نوع [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
```

ایجاد زیرنویس

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | java.lang.String | زیرنویس (نمایهٔ پایین سمت راست) |

**بازمی‌گرداند:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - عنصر ریاضی جدید از نوع [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

ایجاد بالانویس

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | بالانویس (نمایهٔ بالا سمت راست) |

**بازمی‌گرداند:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
```

ایجاد بالانویس

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| superscript | java.lang.String | بالانویس (نمایهٔ بالا سمت راست) |

**بازمی‌گرداند:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

ایجاد زیرنویس و بالانویس در سمت راست

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

**بازمی‌گرداند:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

ایجاد زیرنویس و بالانویس در سمت راست

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | java.lang.String | زیرنویس (نمایهٔ پایین سمت راست) |
| superscript | java.lang.String | بالانویس (نمایهٔ بالا سمت راست) |

**بازمی‌گرداند:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

ایجاد زیرنویس و بالانویس در سمت چپ

--------------------

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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | زیرنویس (نمایهٔ پایین سمت چپ) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | بالانویس (نمایهٔ بالا سمت چپ) |

**بازمی‌گرداند:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

ایجاد زیرنویس و بالانویس در سمت چپ

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | java.lang.String | زیرنویس (نمایهٔ پایین سمت چپ) |
| superscript | java.lang.String | بالانویس (نمایهٔ بالا سمت چپ) |

**بازمی‌گرداند:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - عنصر ریاضی جدید از نوع [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```

تعیین ریشهٔ ریاضی از درجهٔ داده شده برای آرگومان مشخص شده

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

**بازمی‌گرداند:**
[IMathRadical](../../com.aspose.slides/imathradical) - نمونه جدید از نوع [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```

تعیین ریشهٔ ریاضی از درجهٔ داده شده برای آرگومان مشخص شده

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| degree | java.lang.String | آرگومان رادیکال |

**بازمی‌گرداند:**
[IMathRadical](../../com.aspose.slides/imathradical) - نمونه جدید از نوع [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```

دریافت حد بالا

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | حد |

**بازمی‌گرداند:**
[IMathLimit](../../com.aspose.slides/imathlimit) - نمونه جدید از نوع [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```

دریافت حد بالا

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

**بازمی‌گرداند:**
[IMathLimit](../../com.aspose.slides/imathlimit) - نمونه جدید از نوع [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```

دریافت حد پایین

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | حد |

**بازمی‌گرداند:**
[IMathLimit](../../com.aspose.slides/imathlimit) - نمونه جدید از نوع [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```

دریافت حد پایین

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

**بازمی‌گرداند:**
[IMathLimit](../../com.aspose.slides/imathlimit) - نمونه جدید از نوع [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

ایجاد یک عملگر N-ary

--------------------

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
| type | int | نوع عملگر N-ary |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد پایین |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد بالا |

**بازمی‌گرداند:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونه جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

ایجاد یک عملگر N-ary

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | نوع عملگر N-ary |
| lowerLimit | java.lang.String | حد پایین |
| upperLimit | java.lang.String | حد بالا |

**بازمی‌گرداند:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونه جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```

قرار دادن در آرایهٔ عمودی

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**بازمی‌گرداند:**
[IMathArray](../../com.aspose.slides/imatharray) - نمونه جدید از نوع [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

دریافت انتگرال

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

**بازمی‌گرداند:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونه جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

دریافت انتگرال

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

**بازمی‌گرداند:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونه جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```

دریافت انتگرال بدون حدود

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

**بازمی‌گرداند:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونه جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

دریافت انتگرال

--------------------

> ```
> Example:
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

**بازمی‌گرداند:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونه جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

دریافت انتگرال

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

**بازمی‌گرداند:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نمونه جدید از نوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```

تنظیم یک علامت لهجه (کاراکتر در بالای این عنصر)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| accentCharacter | char | کاراکتر لهجه. مقدار باید در بازه (U+0300\\u2013U+036F) یا (U+20D0\\u2013U+20EF) باشد |

**بازمی‌گرداند:**
[IMathAccent](../../com.aspose.slides/imathaccent) - نمونه جدید از نوع [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```

تنظیم یک خط بالای این عنصر

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**بازمی‌گرداند:**
[IMathBar](../../com.aspose.slides/imathbar) - نمونه جدید از نوع [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```

تنظیم یک خط پایین این عنصر

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**بازمی‌گرداند:**
[IMathBar](../../com.aspose.slides/imathbar) - نمونه جدید از نوع [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```

قرار دادن این عنصر در یک گروه با استفاده از براکت منحنی پایین

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**بازمی‌گرداند:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - نمونه جدید از نوع [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

قرار دادن این عنصر در یک گروه با استفاده از کاراکتر گروه‌بندی مانند براکت منحنی پایین یا کاراکتر دیگر

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| character | char | کاراکتر گروه‌بندی مانند BOTTOM CURLY BRACKET (U+23DF) یا هر کاراکتر دیگر |
| position | int | موقعیت کاراکتر گروه‌بندی |
| verticalJustification | int | تراز عمودی کاراکتر گروه. تعیین‌کنندهٔ هم‌ترازی شیء نسبت به خط پایه است. به عنوان مثال، وقتی کاراکتر گروه بالای شیء باشد، VerticalJustification مقدار Top به معنای قرارگیری بالای شیء بر خط پایه است؛ وقتی مقدار Bottom باشد، پایین شیء بر خط پایه قرار می‌گیرد |

**بازمی‌گرداند:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - نمونه جدید از نوع [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```

قرار دادن این عنصر در یک جعبه‌حاشیه‌ای

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**بازمی‌گرداند:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - جعبه‌حاشیه‌ای که این عنصر داخل آن قرار گرفته است
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

قرار دادن این عنصر در یک جعبه‌حاشیه‌ای

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hideTop | boolean | پنهان کردن لبهٔ بالا |
| hideBottom | boolean | پنهان کردن لبهٔ پایین |
| hideLeft | boolean | پنهان کردن لبهٔ چپ |
| hideRight | boolean | پنهان کردن لبهٔ راست |
| strikethroughHorizontal | boolean | خط‌کش افقی جعبه‌حاشیه‌ای |
| strikethroughVertical | boolean | خط‌کش عمودی جعبه‌حاشیه‌ای |
| strikethroughBottomLeftToTopRight | boolean | خط‌کش از پایین چپ به بالا راست |
| strikethroughTopLeftToBottomRight | boolean | خط‌کش از بالا چپ به پایین راست |

**بازمی‌گرداند:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - جعبه‌حاشیه‌ای که این عنصر داخل آن قرار گرفته است
### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```

قرار دادن این عنصر در یک جعبه غیر‌دیداری (گروه‌بندی منطقی) که برای گروه‌بندی اجزای یک معادله یا نمونه دیگر متن ریاضی استفاده می‌شود. یک شیء بسته‌بندی شده می‌تواند (به عنوان مثال) به عنوان یک شبیه‌ساز عملگر با یا بدون نقطهٔ تراز، به عنوان نقطهٔ شکست خط، یا به‌گونه‌ای گروه‌بندی شود که از شکست خطوط درون آن جلوگیری کند

--------------------

> ```
> مثال:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**بازمی‌گرداند:**
[IMathBox](../../com.aspose.slides/imathbox) - جعبه منطقی که این عنصر داخل آن قرار گرفته است