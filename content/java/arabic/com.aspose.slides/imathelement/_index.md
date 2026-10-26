---
title: IMathElement
second_title: Aspose.Slides for Java API Reference
description: واجهة أساسية لأي عنصر رياضي  كسر نص رياضي دالة تعبير مع عناصر متعددة إلخ
type: docs
url: /ar/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

واجهة أساسية لأي عنصر رياضي: كسر، نص رياضي، دالة، تعبير مع عناصر متعددة إلخ

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
> ```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getChildren()](#getChildren--) | الحصول على عناصر الأطفال |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | ينضم إلى عنصر رياضي ويشكّل كتلة رياضية |
| [join(String mathText)](#join-java.lang.String-) | ينضم إلى نص رياضي ويشكّل كتلة رياضية |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | ينشئ كسرًا بالمقام المحدد وهذا البسط |
| [divide(String denominator)](#divide-java.lang.String-) | ينشئ كسرًا بالمقام المحدد وهذا البسط |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد |
| [enclose()](#enclose--) | يُحْطِ العنصر الرياضي بأقواس |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | يُحْطِ هذا العنصر بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | يأخذ دالة لوسيط باستخدام هذا المثيل كاسم الدالة |
| [function(String functionArgument)](#function-java.lang.String-) | يأخذ دالة لوسيط باستخدام هذا المثيل كاسم الدالة |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | يأخذ دالة محددة باستخدام هذا المثيل كوسيط |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | يأخذ دالة محددة باستخدام هذا المثيل كوسيط |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | يأخذ دالة محددة باستخدام هذا المثيل كوسيط |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | يأخذ دالة محددة باستخدام هذا المثيل كوسيط وإضافة وسيط إضافي محدد |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | يأخذ دالة محددة باستخدام هذا المثيل كوسيط وإضافة وسيط إضافي محدد |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | ينشئ نصًا سفليًا |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | ينشئ نصًا سفليًا |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | ينشئ نصًا علويًا |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | ينشئ نصًا علويًا |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ينشئ نصًا سفليًا وعليا على اليمين |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | ينشئ نصًا سفليًا وعليا على اليمين |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ينشئ نصًا سفليًا وعليا على اليسار |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | ينشئ نصًا سفليًا وعليا على اليسار |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | يحدد الجذر الرياضي للدرجة المحددة من الوسيط المحدد. |
| [radical(String degree)](#radical-java.lang.String-) | يحدد الجذر الرياضي للدرجة المحددة من الوسيط المحدد. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | يأخذ الحد الأعلى |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | يأخذ الحد الأعلى |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | يأخذ الحد السفلي |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | يأخذ الحد السفلي |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ينشئ مشغلًا من N أعداد |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | ينشئ مشغلًا من N أعداد |
| [toMathArray()](#toMathArray--) | يضع مصفوفة عمودية |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | يأخذ التكامل |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | يأخذ التكامل |
| [integral(int integralType)](#integral-int-) | يأخذ التكامل بدون حدود |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | يأخذ التكامل |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | يأخذ التكامل |
| [accent(char accentCharacter)](#accent-char-) | يضع علامة تشكيل (حرف فوق هذا العنصر) |
| [overbar()](#overbar--) | يضع شريطًا فوق هذا العنصر |
| [underbar()](#underbar--) | يضع شريطًا أسفل هذا العنصر |
| [group()](#group--) | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [toBorderBox()](#toBorderBox--) | يضع هذا العنصر في صندوق حدود |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | يضع هذا العنصر في صندوق حدود |
| [toBox()](#toBox--) | يضع هذا العنصر في صندوق غير مرئي (مجموعة منطقية) يُستخدم لتجميع مكونات معادلة أو مثال آخر من النص الرياضي. |

### getChildren() {#getChildren--}
```
public abstract IMathElement[] getChildren()
```

الحصول على عناصر الأطفال

**القيمة المرجعة:**
com.aspose.slides.IMathElement[]

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock join(IMathElement mathElement)
```

ينضم إلى عنصر رياضي ويشكّل كتلة رياضية

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
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الذي سيُضمّن |

**القيمة المرجعة:**
[IMathBlock](../../com.aspose.slides/imathblock) - كتلة رياضية جديدة IMathBlock تحتوي على هذا المثيل والوسيط المحدد

### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
```

ينضم إلى نص رياضي ويشكّل كتلة رياضية

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathText | java.lang.String | النص الرياضي الذي سيُضمّن |

**القيمة المرجعة:**
[IMathBlock](../../com.aspose.slides/imathblock) - كتلة رياضية جديدة IMathBlock تحتوي على هذا المثيل والوسيط المحدد

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction divide(IMathElement denominator)
```

ينشئ كسرًا بالمقام المحدد وهذا البسط

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

**القيمة المرجعة:**
[IMathFraction](../../com.aspose.slides/imathfraction) - كسر جديد

### divide(String denominator) {#divide-java.lang.String-}
```
public abstract IMathFraction divide(String denominator)
```

ينشئ كسرًا بالمقام المحدد وهذا البسط

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

**القيمة المرجعة:**
[IMathFraction](../../com.aspose.slides/imathfraction) - كسر جديد

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
```

ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد

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

**القيمة المرجعة:**
[IMathFraction](../../com.aspose.slides/imathfraction) - كسر جديد

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public abstract IMathFraction divide(String denominator, int fractionType)
```

ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد

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

**القيمة المرجعة:**
[IMathFraction](../../com.aspose.slides/imathfraction) - كسر جديد

### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
```

يُحْطِ العنصر الرياضي بأقواس

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**القيمة المرجعة:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - العنصر الرياضي من النوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) الذي يتضمن الأقواس

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

يُحْطِ هذا العنصر بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| beginningCharacter | char | الحرف الابتدائي (عادة القوس الأيسر) |
| endingCharacter | char | الحرف النهائي (عادة القوس الأيمن) |

**القيمة المرجعة:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - العنصر الرياضي من النوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) الذي يتضمن الأحرف المحددة كإطار

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```

يأخذ دالة لوسيط باستخدام هذا المثيل كاسم الدالة

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

**القيمة المرجعة:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)

### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```

يأخذ دالة لوسيط باستخدام هذا المثيل كاسم الدالة

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

**القيمة المرجعة:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
```

يأخذ دالة محددة باستخدام هذا المثيل كوسيط

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

**القيمة المرجعة:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(String functionName)
```

يأخذ دالة محددة باستخدام هذا المثيل كوسيط

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

**القيمة المرجعة:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType)
```

يأخذ دالة محددة باستخدام هذا المثيل كوسيط

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionType | int | أحد أنواع الدوال الشائعة للوسيط الواحد |

**القيمة المرجعة:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

يأخذ دالة محددة باستخدام هذا المثيل كوسيط وإضافة وسيط إضافي محدد

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // يُعيد لوغاريتم 'x' إلى القاعدة '5'
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionType | int | أحد أنواع الدوال الشائعة للوسيطة ذات الوسيطين: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | وسيط إضافي يعتمد على نوع الدالة |

**القيمة المرجعة:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

يأخذ دالة محددة باستخدام هذا المثيل كوسيط وإضافة وسيط إضافي محدد

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // يُعيد لوغاريتم 'x' إلى القاعدة '5'
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionType | int | أحد أنواع الدوال الشائعة للوسيطة ذات الوسيطين: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | وسيط إضافي يعتمد على نوع الدالة |

**القيمة المرجعة:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
```

ينشئ نصًا سفليًا

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

**القيمة المرجعة:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - عنصر رياضي جديد من النوع [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
```

ينشئ نصًا سفليًا

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

**القيمة المرجعة:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - عنصر رياضي جديد من النوع [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

ينشئ نصًا علويًا

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | نص علوي (مؤشر علوي على اليمين) |

**القيمة المرجعة:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - عنصر رياضي جديد من النوع [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
```

ينشئ نصًا علويًا

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

**القيمة المرجعة:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - عنصر رياضي جديد من النوع [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

ينشئ نصًا سفليًا وعليا على اليمين

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

**القيمة المرجعة:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - عنصر رياضي جديد من النوع [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```
Creates subscript and superscript on the right
====================

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | موضع سفلي (مؤشر أسفل اليمين) |
| superscript | java.lang.String | موضع علوي (مؤشر فوق اليمين) |

**Returns:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - عنصر رياضي جديد من النوع [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Creates subscript and superscript on the left
====================

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | موضع سفلي (مؤشر أسفل اليسار) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | موضع علوي (مؤشر فوق اليسار) |

**Returns:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - عنصر رياضي جديد من النوع [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Creates subscript and superscript on the left
====================

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | موضع سفلي (مؤشر أسفل اليسار) |
| superscript | java.lang.String | موضع علوي (مؤشر فوق اليسار) |

**Returns:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - عنصر رياضي جديد من النوع [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```

Specifies the mathematical root of the given degree from the specified argument.
====================

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | وسيط الجذر |

**Returns:**
[IMathRadical](../../com.aspose.slides/imathradical) - مثيل جديد من النوع [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```

Specifies the mathematical root of the given degree from the specified argument.
====================

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | java.lang.String | وسيط الجذر |

**Returns:**
[IMathRadical](../../com.aspose.slides/imathradical) - مثيل جديد من النوع [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```

Takes upper limit
====================

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأعلى |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - مثيل جديد من النوع [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```

Takes upper limit
====================

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | الحد الأعلى |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - مثيل جديد من النوع [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```

Takes lower limit
====================

> ```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأدنى |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - مثيل جديد من النوع [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```

Takes lower limit
====================

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | الحد |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - مثيل جديد من النوع [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Creates a N-ary operator
====================

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | نوع العامل N-ary |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأدنى |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأعلى |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - مثيل جديد من النوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Creates a N-ary operator
====================

> ```
> مثال:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | نوع العامل N-ary |
| lowerLimit | java.lang.String | الحد الأدنى |
| upperLimit | java.lang.String | الحد الأعلى |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - مثيل جديد من النوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```

Puts in a vertical array
====================

> ```
> مثال:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Returns:**
[IMathArray](../../com.aspose.slides/imatharray) - مثيل جديد من النوع [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Takes the integral
====================

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | نوع التكامل |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأدنى للتكامل |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأعلى للتكامل |
| limitLocations | int | موقع الحدود |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - مثيل جديد من النوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Takes the integral
====================

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | نوع التكامل |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأدنى للتكامل |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأعلى للتكامل |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - مثيل جديد من النوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```

Takes the integral without limits
====================

> ```
public abstract IMathNaryOperator integral(int integralType)
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | نوع التكامل |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - مثيل جديد من النوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Takes the integral
====================

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | نوع التكامل |
| lowerLimit | java.lang.String | الحد الأدنى للتكامل |
| upperLimit | java.lang.String | الحد الأعلى للتكامل |
| limitLocations | int | موقع الحدود |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - مثيل جديد من النوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Takes the integral
====================

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | نوع التكامل |
| lowerLimit | java.lang.String | الحد الأدنى للتكامل |
| upperLimit | java.lang.String | الحد الأعلى للتكامل |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - مثيل جديد من النوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```

Sets an accent mark (a character on the top of this element)
====================

> ```
> مثال:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| accentCharacter | char | حرف التنوين. يجب أن يكون ضمن النطاق (U+0300\\u2013U+036F) أو (U+20D0\\u2013U+20EF) |

**Returns:**
[IMathAccent](../../com.aspose.slides/imathaccent) - مثيل جديد من النوع [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```

Sets a bar on the top of this element
====================

> ```
> مثال:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Returns:**
[IMathBar](../../com.aspose.slides/imathbar) - مثيل جديد من النوع [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```

Sets a bar on the bottom of this element
====================

> ```
> مثال:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Returns:**
[IMathBar](../../com.aspose.slides/imathbar) - مثيل جديد من النوع [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```

Places this element in a group using a bottom curly bracket
====================

> ```
> Example:
>  
```

**Returns:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - مثيل جديد من النوع [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Places this element in a group using a grouping character such as bottom curly bracket or another
====================

> ```
> مثال:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| character | char | حرف التجميع مثل القوس المعقوف السفلي (U+23DF) أو أي حرف آخر |
| position | int | موضع حرف التجميع |
| verticalJustification | int | محاذاة رأسية لحرف المجموعة. تحدد محاذاة الكائن بالنسبة لخط القاعدة. على سبيل المثال، عندما يكون حرف المجموعة فوق الكائن، يعني VerticalJustification العلوي أن أعلى الكائن يقع على خط القاعدة؛ وعندما يُحدد Bottom فإن أسفل الكائن يكون على خط القاعدة |

**Returns:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - مثيل جديد من النوع [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```

Places this element in a border-box
====================

> ```
> مثال:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - صندوق حدود يحتوي على هذا العنصر داخله
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Places this element in a border-box
====================

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hideTop | boolean | إخفاء الحافة العليا |
| hideBottom | boolean | إخفاء الحافة السفلية |
| hideLeft | boolean | إخفاء الحافة اليسارية |
| hideRight | boolean | إخفاء الحافة اليمنية |
| strikethroughHorizontal | boolean | خط شطب أفقي لصندوق الحدود |
| strikethroughVertical | boolean | خط شطب عمودي لصندوق الحدود |
| strikethroughBottomLeftToTopRight | boolean | خط شطب من الأسفل-اليسار إلى الأعلى-اليمين |
| strikethroughTopLeftToBottomRight | boolean | خط شطب من الأعلى-اليسار إلى الأسفل-اليمين |

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - صندوق حدود يحتوي على هذا العنصر داخله
### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```

Places this element in a non-visual box (logical grouping) which is used to group components of an equation or other instance of mathematical text. A boxed object can (for example) serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within.
====================

> ```
> مثال:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Returns:**
[IMathBox](../../com.aspose.slides/imathbox) - صندوق منطقي يحتوي على هذا العنصر داخله