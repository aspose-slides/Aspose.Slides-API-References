---
title: IMathElement
second_title: Aspose.Slides for Android via Java API Reference
description: الواجهة الأساسية لأي عنصر رياضي: كسر، نص رياضي، دالة، تعبير يحتوي على عناصر متعددة، إلخ
type: docs
url: /ar/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

الواجهة الأساسية لأي عنصر رياضي: كسر، نص رياضي، دالة، تعبير يحتوي على عناصر متعددة، إلخ

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
> ```
## Methods

| Method | Description |
| --- | --- |
| [getChildren()](#getChildren--) | الحصول على عناصر الأطفال |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | دمج عنصر رياضي وتكوين كتلة رياضية |
| [join(String mathText)](#join-java.lang.String-) | دمج نص رياضي وتكوين كتلة رياضية |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | إنشاء كسر بمقام من هذا البسط والمقام المحدد |
| [divide(String denominator)](#divide-java.lang.String-) | إنشاء كسر بمقام من هذا البسط والمقام المحدد |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | إنشاء كسر من النوع المحدد بهذا البسط والمقام المحدد |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | إنشاء كسر من النوع المحدد بهذا البسط والمقام المحدد |
| [enclose()](#enclose--) | إحاطة عنصر رياضي بأقواس |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | إحاطة هذا العنصر بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | أخذ دالة لوسيط باستخدام هذه المثيلة كاسم الدالة |
| [function(String functionArgument)](#function-java.lang.String-) | أخذ دالة لوسيط باستخدام هذه المثيلة كاسم الدالة |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | أخذ الدالة المحددة باستخدام هذه المثيلة كوسيط |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | أخذ الدالة المحددة باستخدام هذه المثيلة كوسيط |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | أخذ الدالة المحددة باستخدام هذه المثيلة كوسيط |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | أخذ الدالة المحددة باستخدام هذه المثيلة كوسيط وإضافة وسيط إضافي |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | أخذ الدالة المحددة باستخدام هذه المثيلة كوسيط وإضافة وسيط إضافي |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | إنشاء نص سفلي |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | إنشاء نص سفلي |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | إنشاء نص علوي |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | إنشاء نص علوي |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | إنشاء نص سفلي وعلوي على اليمين |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | إنشاء نص سفلي وعلوي على اليمين |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | إنشاء نص سفلي وعلوي على اليسار |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | إنشاء نص سفلي وعلوي على اليسار |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | تحديد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد |
| [radical(String degree)](#radical-java.lang.String-) | تحديد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | أخذ الحد الأعلى |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | أخذ الحد الأعلى |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | أخذ الحد الأدنى |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | أخذ الحد الأدنى |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | إنشاء معامل N-ary |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | إنشاء معامل N-ary |
| [toMathArray()](#toMathArray--) | وضع في مصفوفة رأسية |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | أخذ التكامل |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | أخذ التكامل |
| [integral(int integralType)](#integral-int-) | أخذ التكامل دون حدود |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | أخذ التكامل |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | أخذ التكامل |
| [accent(char accentCharacter)](#accent-char-) | تعيين علامة شدة (حرف أعلى هذا العنصر) |
| [overbar()](#overbar--) | تعيين شريط أعلى هذا العنصر |
| [underbar()](#underbar--) | تعيين شريط أسفل هذا العنصر |
| [group()](#group--) | وضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | وضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [toBorderBox()](#toBorderBox--) | وضع هذا العنصر في صندوق حد |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | وضع هذا العنصر في صندوق حد |
| [toBox()](#toBox--) | وضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يستخدم لتجميع مكونات معادلة أو نص رياضي آخر |
### getChildren() {#getChildren--}
```
public abstract IMathElement[] getChildren()
```

الحصول على عناصر الأطفال

**الإرجاع:**
com.aspose.slides.IMathElement[]
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock join(IMathElement mathElement)
```

دمج عنصر رياضي وتكوين كتلة رياضية

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | العنصر المراد دمجه |

**الإرجاع:**
[IMathBlock](../../com.aspose.slides/imathblock) - كتلة رياضية جديدة IMathBlock تحتوي على هذه المثيلة والوسيط المحدد
### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
```

دمج نص رياضي وتكوين كتلة رياضية

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathText | java.lang.String | النص الرياضي المراد دمجه |

**الإرجاع:**
[IMathBlock](../../com.aspose.slides/imathblock) - كتلة رياضية جديدة IMathBlock تحتوي على هذه المثيلة والوسيط المحدد
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction divide(IMathElement denominator)
```

إنشاء كسر بهذا البسط والمقام المحدد

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | المقام |

**الإرجاع:**
[IMathFraction](../../com.aspose.slides/imathfraction) - كسر جديد
### divide(String denominator) {#divide-java.lang.String-}
```
public abstract IMathFraction divide(String denominator)
```

إنشاء كسر بهذا البسط والمقام المحدد

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| denominator | java.lang.String | المقام |

**الإرجاع:**
[IMathFraction](../../com.aspose.slides/imathfraction) - كسر جديد
### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
```

إنشاء كسر من النوع المحدد بهذا البسط والمقام المحدد

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | المقام |
| fractionType | int | نوع الكسر: Bar, NoBar, Skewed, Linear |

**الإرجاع:**
[IMathFraction](../../com.aspose.slides/imathfraction) - كسر جديد
### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public abstract IMathFraction divide(String denominator, int fractionType)
```

إنشاء كسر من النوع المحدد بهذا البسط والمقام المحدد

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| denominator | java.lang.String | المقام |
| fractionType | int | نوع الكسر: Bar, NoBar, Skewed, Linear |

**الإرجاع:**
[IMathFraction](../../com.aspose.slides/imathfraction) - كسر جديد
### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
```

إحاطة عنصر رياضي بأقواس

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**الإرجاع:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر رياضي من النوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) يتضمن الأقواس
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

إحاطة هذا العنصر بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| beginningCharacter | char | الحرف الأول (عادة القوس الأيسر) |
| endingCharacter | char | الحرف الأخير (عادة القوس الأيمن) |

**الإرجاع:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر رياضي من النوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) يتضمن الأحرف المحددة كإطار
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```

أخذ دالة لوسيط باستخدام هذه المثيلة كاسم الدالة

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | وسيط الدالة |

**الإرجاع:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)
### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```

أخذ دالة لوسيط باستخدام هذه المثيلة كاسم الدالة

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionArgument | java.lang.String | وسيط الدالة |

**الإرجاع:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
```

أخذ الدالة المحددة باستخدام هذه المثيلة كوسيط

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | اسم الدالة |

**الإرجاع:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(String functionName)
```

أخذ الدالة المحددة باستخدام هذه المثيلة كوسيط

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionName | java.lang.String | اسم الدالة |

**الإرجاع:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType)
```

أخذ الدالة المحددة باستخدام هذه المثيلة كوسيط

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionType | int | أحد أنواع الدوال الشائعة ذات وسيلة واحدة |

**الإرجاع:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

أخذ الدالة المحددة باستخدام هذه المثيلة كوسيط وإضافة وسيط إضافي

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // إرجاع لوغاريتم 'x' إلى القاعدة '5'
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionType | int | أحد أنواع الدوال الشائعة ذات وسيطين: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | وسيط إضافي يعتمد على نوع الدالة |

**الإرجاع:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

أخذ الدالة المحددة باستخدام هذه المثيلة كوسيط وإضافة وسيط إضافي

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // إرجاع لوغاريتم 'x' إلى القاعدة '5'
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionType | int | أحد أنواع الدوال الشائعة ذات وسيطين: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | وسيط إضافي يعتمد على نوع الدالة |

**الإرجاع:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
```

إنشاء نص سفلي

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | نص سفلي (مؤشر سفلي على اليمين) |

**الإرجاع:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - عنصر رياضي جديد من النوع [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
```

إنشاء نص سفلي

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| subscript | java.lang.String | نص سفلي (مؤشر سفلي على اليمين) |

**الإرجاع:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - عنصر رياضي جديد من النوع [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

إنشاء نص علوي

--------------------

> ```
> مثال:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | نص علوي (مؤشر علوي على اليمين) |

**الإرجاع:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - عنصر رياضي جديد من النوع [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
```

إنشاء نص علوي

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| superscript | java.lang.String | نص علوي (مؤشر علوي على اليمين) |

**الإرجاع:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - عنصر رياضي جديد من النوع [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

إنشاء نص سفلي وعلوي على اليمين

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | نص سفلي (مؤشر سفلي على اليمين) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | نص علوي (مؤشر علوي على اليمين) |

**الإرجاع:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - عنصر رياضي جديد من النوع [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

إنشاء نص سفلي وعلوي على اليمين

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| subscript | java.lang.String | نص سفلي (مؤشر سفلي على اليمين) |
| superscript | java.lang.String | نص علوي (مؤشر علوي على اليمين) |

**الإرجاع:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - عنصر رياضي جديد من النوع [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

إنشاء نص سفلي وعلوي على اليسار

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | نص سفلي (مؤشر سفلي على اليسار) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | نص علوي (مؤشر علوي على اليسار) |

**الإرجاع:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - عنصر رياضي جديد من النوع [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

إنشاء نص سفلي وعلوي على اليسار

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| subscript | java.lang.String | نص سفلي (مؤشر سفلي على اليسار) |
| superscript | java.lang.String | نص علوي (مؤشر علوي على اليسار) |

**الإرجاع:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - عنصر رياضي جديد من النوع [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```

تحديد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | وسيط الجذر |

**الإرجاع:**
[IMathRadical](../../com.aspose.slides/imathradical) - نسخة جديدة من النوع [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```

تحديد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| degree | java.lang.String | وسيط الجذر |

**الإرجاع:**
[IMathRadical](../../com.aspose.slides/imathradical) - نسخة جديدة من النوع [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```

أخذ الحد الأعلى

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | الحد |

**الإرجاع:**
[IMathLimit](../../com.aspose.slides/imathlimit) - نسخة جديدة من النوع [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```

أخذ الحد الأعلى

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| limit | java.lang.String | الحد |

**الإرجاع:**
[IMathLimit](../../com.aspose.slides/imathlimit) - نسخة جديدة من النوع [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```

أخذ الحد الأدنى

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | الحد |

**الإرجاع:**
[IMathLimit](../../com.aspose.slides/imathlimit) - نسخة جديدة من النوع [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```

أخذ الحد الأدنى

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| limit | java.lang.String | الحد |

**الإرجاع:**
[IMathLimit](../../com.aspose.slides/imathlimit) - نسخة جديدة من النوع [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

إنشاء معامل N-ary

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | int | نوع معامل N-ary |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأدنى |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأعلى |

**الإرجاع:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نسخة جديدة من النوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

إنشاء معامل N-ary

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | int | نوع معامل N-ary |
| lowerLimit | java.lang.String | الحد الأدنى |
| upperLimit | java.lang.String | الحد الأعلى |

**الإرجاع:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نسخة جديدة من النوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```

وضع في مصفوفة رأسية

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**الإرجاع:**
[IMathArray](../../com.aspose.slides/imatharray) - نسخة جديدة من النوع [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

أخذ التكامل

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| integralType | int | نوع التكامل |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأدنى للتكامل |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأعلى للتكامل |
| limitLocations | int | موقع الحدود |

**الإرجاع:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نسخة جديدة من النوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

أخذ التكامل

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| integralType | int | نوع التكامل |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأدنى للتكامل |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأعلى للتكامل |

**الإرجاع:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نسخة جديدة من النوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```

أخذ التكامل دون حدود

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| integralType | int | نوع التكامل |

**الإرجاع:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نسخة جديدة من النوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

أخذ التكامل

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| integralType | int | نوع التكامل |
| lowerLimit | java.lang.String | الحد الأدنى للتكامل |
| upperLimit | java.lang.String | الحد الأعلى للتكامل |
| limitLocations | int | موقع الحدود |

**الإرجاع:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نسخة جديدة من النوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

أخذ التكامل

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // إرجاع لوغاريتم 'x' إلى القاعدة '5'
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| integralType | int | نوع التكامل |
| lowerLimit | java.lang.String | الحد الأدنى للتكامل |
| upperLimit | java.lang.String | الحد الأعلى للتكامل |

**الإرجاع:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نسخة جديدة من النوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```

تعيين علامة شدة (حرف أعلى هذا العنصر)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| accentCharacter | char | حرف الشدة. يجب أن يكون ضمن النطاق (U+0300\\u2013U+036F) أو (U+20D0\\u2013U+20EF) |

**الإرجاع:**
[IMathAccent](../../com.aspose.slides/imathaccent) - نسخة جديدة من النوع [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```

تعيين شريط أعلى هذا العنصر

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**الإرجاع:**
[IMathBar](../../com.aspose.slides/imathbar) - نسخة جديدة من النوع [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```

تعيين شريط أسفل هذا العنصر

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**الإرجاع:**
[IMathBar](../../com.aspose.slides/imathbar) - نسخة جديدة من النوع [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```

وضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**الإرجاع:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - نسخة جديدة من النوع [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

وضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| character | char | حرف التجميع مثل القوس المعقوف السفلي (U+23DF) أو أي حرف آخر |
| position | int | موضع حرف التجميع |
| verticalJustification | int | ضبط موضع حرف التجميع عمودياً. يحدد محاذاة الكائن بالنسبة لخط القاعدة. على سبيل المثال، عندما يكون حرف التجميع فوق الكائن، يعني VerticalJustification الأعلى أن أعلى الكائن يقع على خط القاعدة؛ وعندما يُضبط إلى Bottom، يكون أسفل الكائن على خط القاعدة |

**الإرجاع:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - نسخة جديدة من النوع [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```

وضع هذا العنصر في صندوق حد

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**الإرجاع:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - صندوق حد يحتوي هذا العنصر داخله
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

وضع هذا العنصر في صندوق حد

--------------------

> ```
> مثال:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| hideTop | boolean | إخفاء الحافة العلوية |
| hideBottom | boolean | إخفاء الحافة السفلية |
| hideLeft | boolean | إخفاء الحافة اليسرى |
| hideRight | boolean | إخفاء الحافة اليمنى |
| strikethroughHorizontal | boolean | خط أفقي عبر صندوق الحد |
| strikethroughVertical | boolean | خط عمودي عبر صندوق الحد |
| strikethroughBottomLeftToTopRight | boolean | خط مقطع من الأسفل الأيسر إلى الأعلى الأيمن |
| strikethroughTopLeftToBottomRight | boolean | خط مقطع من الأعلى الأيسر إلى الأسفل الأيمن |

**الإرجاع:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - صندوق حد يحتوي هذا العنصر داخله
### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```

وضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو نص رياضي آخر. يمكن للصندوق المعبأ أن يعمل (على سبيل المثال) كمحاكي للمعامل مع أو بدون نقطة محاذاة، أو كنقطة كسر سطر، أو يُجمع بحيث لا يسمح بوجود فواصل سطر داخلية.

--------------------

> ```
> مثال:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**الإرجاع:**
[IMathBox](../../com.aspose.slides/imathbox) - صندوق منطقي يحتوي هذا العنصر داخله