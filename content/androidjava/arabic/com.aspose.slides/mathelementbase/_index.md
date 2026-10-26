---
title: MathElementBase
second_title: Aspose.Slides لأندرويد عبر مرجع API جافا
description: فئة أساسية لـ IMathElement مع تنفيذ بعض الأساليب التي هي شائعة لجميع الفئات الموروثة. للاستخدام الداخلي فقط.
type: docs
url: /ar/com.aspose.slides/mathelementbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

الفئة الأساسية لـ IMathElement مع تنفيذ بعض الأساليب المشتركة بين جميع الفئات الموروثة. للاستخدام الداخلي فقط. يجب أن تكون الفئة الموروثة IMMathElement.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | يرجع كائن Parent_Immediate. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | يلتحق بعنصر رياضي ويكوّن كتلة رياضية |
| [join(String mathText)](#join-java.lang.String-) | يلتحق بنص رياضي ويكوّن كتلة رياضية |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [divide(String denominator)](#divide-java.lang.String-) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [enclose()](#enclose--) | يحيط عنصر رياضي بأقواس |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | يحيط عنصر رياضي بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | يأخذ دالة لوسيط باستخدام هذا الكائن كاسم للدالة |
| [function(String functionArgument)](#function-java.lang.String-) | يأخذ دالة لوسيط باستخدام هذا الكائن كاسم للدالة |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | يأخذ الدالة المحددة باستخدام هذا الكائن كوسيط |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | يأخذ الدالة المحددة باستخدام هذا الكائن كوسيط |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | يأخذ الدالة المحددة باستخدام هذا الكائن كوسيط |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | يأخذ الدالة المحددة باستخدام هذا الكائن كوسيط مع وسيط إضافي محدد |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | يأخذ الدالة المحددة باستخدام هذا الكائن كوسيط مع وسيط إضافي محدد |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | ينشئ نصًا سفليًا |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | ينشئ نصًا سفليًا |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | ينشئ نصًا علويًا |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | ينشئ نصًا علويًا |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ينشئ نصًا سفليًا وعلويًا على اليمين |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | ينشئ نصًا سفليًا وعلويًا على اليمين |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ينشئ نصًا سفليًا وعلويًا على اليسار |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | ينشئ نصًا سفليًا وعلويًا على اليسار |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد. |
| [radical(String degree)](#radical-java.lang.String-) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | يأخذ الحد الأعلى |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | يأخذ الحد الأعلى |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | يأخذ الحد الأدنى |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | يأخذ الحد الأدنى |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ينشئ عاملًا N-ary |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | ينشئ عاملًا N-ary |
| [toMathArray()](#toMathArray--) | يضع في مصفوفة عمودية |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | يأخذ التكامل |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | يأخذ التكامل |
| [integral(int integralType)](#integral-int-) | يأخذ التكامل بدون حدود |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | يأخذ التكامل |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | يأخذ التكامل |
| [accent(char accentCharacter)](#accent-char-) | يضبط علامة تشديد (حرف فوق هذا العنصر) |
| [overbar()](#overbar--) | يضبط شريطًا فوق هذا العنصر |
| [underbar()](#underbar--) | يضبط شريطًا أسفل هذا العنصر |
| [group()](#group--) | يوضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | يوضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [toBorderBox()](#toBorderBox--) | يوضع هذا العنصر في صندوق حد |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | يوضع هذا العنصر في صندوق حد |
| [toBox()](#toBox--) | يوضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو نص رياضي آخر. |
| [getChildren()](#getChildren--) | الحصول على العناصر الفرعية |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

يرجع كائن Parent_Immediate. IDOMObject للقراءة فقط.

**الإرجاع:**
com.aspose.slides.IDOMObject

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

يلتحق بعنصر رياضي ويكوّن كتلة رياضية

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الذي سيتم الالتحاق به |

**الإرجاع:**
[IMathBlock](../../com.aspose.slides/imathblock) - كتلة IMathBlock جديدة تحتوي على هذه المثيل والوسيط المحدد

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

يلتحق بنص رياضي ويكوّن كتلة رياضية

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| mathText | java.lang.String | النص الرياضي الذي سيتم الالتحاق به |

**الإرجاع:**
[IMathBlock](../../com.aspose.slides/imathblock) - كتلة IMathBlock جديدة تحتوي على هذه المثيل والوسيط المحدد

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```

ينشئ كسرًا بهذا البسط والمقام المحدد

--------------------

> ```
> مثال:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | المقام |

**الإرجاع:**
[IMathFraction](../../com.aspose.slides/imathfraction) - كسر جديد

### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```

ينشئ كسرًا بهذا البسط والمقام المحدد

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| denominator | java.lang.String | المقام |

**الإرجاع:**
[IMathFraction](../../com.aspose.slides/imathfraction) - كسر جديد

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد

--------------------

> ```
> مثال:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | المقام |
| fractionType | int | نوع الكسر: Bar, NoBar, Skewed, Linear |

**الإرجاع:**
[IMathFraction](../../com.aspose.slides/imathfraction) - كسر جديد

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| denominator | java.lang.String | المقام |
| fractionType | int | نوع الكسر: Bar, NoBar, Skewed, Linear |

**الإرجاع:**
[IMathFraction](../../com.aspose.slides/imathfraction) - كسر جديد

### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

يحيط عنصر رياضي بأقواس

--------------------

> ```
> مثال:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```


**الإرجاع:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر رياضي من النوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) يتضمن الأقواس

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

يحيط عنصر رياضي بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار

--------------------

> ```
> مثال:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| beginningCharacter | char | الحرف الأول (عادة القوس اليساري) |
| endingCharacter | char | الحرف الأخير (عادة القوس اليميني) |

**الإرجاع:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر رياضي من النوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) يتضمن الأحرف المحددة كإطار

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

يأخذ دالة لوسيط باستخدام هذا الكائن كاسم للدالة

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | وسيط الدالة |

**الإرجاع:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)

### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

يأخذ دالة لوسيط باستخدام هذا الكائن كاسم للدالة

--------------------

> ```
> مثال:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| functionArgument | java.lang.String | وسيط الدالة |

**الإرجاع:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

يأخذ الدالة المحددة باستخدام هذا الكائن كوسيط

--------------------

> ```
> مثال:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | اسم الدالة |

**الإرجاع:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

يأخذ الدالة المحددة باستخدام هذا الكائن كوسيط

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| functionName | java.lang.String | اسم الدالة |

**الإرجاع:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

يأخذ الدالة المحددة باستخدام هذا الكائن كوسيط

--------------------

> ```
> مثال:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| functionType | int | أحد الأنواع الشائعة للدالة ذات الوسيط الواحد |

**الإرجاع:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

يأخذ الدالة المحددة باستخدام هذا الكائن كوسيط مع وسيط إضافي محدد

--------------------

> ```
> مثال:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // يعيد لوغاريتم 'x' إلى القاعدة '5'
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| functionType | int | أحد الأنواع الشائعة للدالة ذات الوسيطين: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | الوسيط الإضافي حسب نوع الدالة |

**الإرجاع:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

يأخذ الدالة المحددة باستخدام هذا الكائن كوسيط مع وسيط إضافي محدد

--------------------

> ```
> مثال:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // يعيد لوغاريتم 'x' إلى القاعدة '5'
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| functionType | int | أحد الأنواع الشائعة للدالة ذات الوسيطين: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | الوسيط الإضافي حسب نوع الدالة |

**الإرجاع:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

ينشئ نصًا سفليًا

--------------------

> ```
> مثال:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | نص سفلي (مؤشر منخفض على اليمين) |

**الإرجاع:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - عنصر رياضي جديد من النوع [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

ينشئ نصًا سفليًا

--------------------

> ```
> مثال:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| subscript | java.lang.String | نص سفلي (مؤشر منخفض على اليمين) |

**الإرجاع:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - عنصر رياضي جديد من النوع [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

ينشئ نصًا علويًا

--------------------

> ```
> مثال:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | نص علوي (مؤشر مرتفع على اليمين) |

**الإرجاع:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - عنصر رياضي جديد من النوع [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

ينشئ نصًا علويًا

--------------------

> ```
> مثال:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| superscript | java.lang.String | نص علوي (مؤشر مرتفع على اليمين) |

**الإرجاع:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - عنصر رياضي جديد من النوع [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

ينشئ نصًا سفليًا وعلويًا على اليمين

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
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | نص سفلي (مؤشر منخفض على اليمين) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | نص علوي (مؤشر مرتفع على اليمين) |

**الإرجاع:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - عنصر رياضي جديد من النوع [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

ينشئ نصًا سفليًا وعلويًا على اليمين

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| subscript | java.lang.String | نص سفلي (مؤشر منخفض على اليمين) |
| superscript | java.lang.String | نص علوي (مؤشر مرتفع على اليمين) |

**الإرجاع:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - عنصر رياضي جديد من النوع [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

ينشئ نصًا سفليًا وعلويًا على اليسار

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | نص سفلي (مؤشر منخفض على اليسار) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | نص علوي (مؤشر مرتفع على اليسار) |

**الإرجاع:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - عنصر رياضي جديد من النوع [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)

### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

ينشئ نصًا سفليًا وعلويًا على اليسار

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| subscript | java.lang.String | نص سفلي (مؤشر منخفض على اليسار) |
| superscript | java.lang.String | نص علوي (مؤشر مرتفع على اليسار) |

**الإرجاع:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - عنصر رياضي جديد من النوع [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)

### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد.

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | وسيط الجذر |

**الإرجاع:**
[IMathRadical](../../com.aspose.slides/imathradical) - نسخة جديدة من النوع [IMathRadical](../../com.aspose.slides/imathradical)

### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد.

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| degree | java.lang.String | وسيط الجذر |

**الإرجاع:**
[IMathRadical](../../com.aspose.slides/imathradical) - نسخة جديدة من النوع [IMathRadical](../../com.aspose.slides/imathradical)

### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

يأخذ الحد الأعلى

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | الحد |

**الإرجاع:**
[IMathLimit](../../com.aspose.slides/imathlimit) - نسخة جديدة من النوع [IMathLimit](../../com.aspose.slides/imathlimit)

### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

يأخذ الحد الأعلى

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| limit | java.lang.String | الحد |

**الإرجاع:**
[IMathLimit](../../com.aspose.slides/imathlimit) - نسخة جديدة من النوع [IMathLimit](../../com.aspose.slides/imathlimit)

### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

يأخذ الحد الأدنى

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```


**المعلمات::
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | الحد |

**الإرجاع:**
[IMathLimit](../../com.aspose.slides/imathlimit) - نسخة جديدة من النوع [IMathLimit](../../com.aspose.slides/imathlimit)

### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

يأخذ الحد الأدنى

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| limit | java.lang.String | الحد |

**الإرجاع:**
[IMathLimit](../../com.aspose.slides/imathlimit) - نسخة جديدة من النوع [IMathLimit](../../com.aspose.slides/imathlimit)

### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

ينشئ عاملًا N-ary

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| type | int | نوع عامل N-ary |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأدنى |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأعلى |

**الإرجاع:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نسخة جديدة من النوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

ينشئ عاملًا N-ary

--------------------

> ```
> مثال:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| type | int | نوع عامل N-ary |
| lowerLimit | java.lang.String | الحد الأدنى |
| upperLimit | java.lang.String | الحد الأعلى |

**الإرجاع:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نسخة جديدة من النوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

يضع في مصفوفة عمودية

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
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

يأخذ التكامل

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| integralType | int | نوع التكامل |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأدنى للتكامل |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأعلى للتكامل |
| limitLocations | int | موقع الحدود |

**الإرجاع:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نسخة جديدة من النوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

يأخذ التكامل

--------------------

> ```
> مثال:
>  
  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| integralType | int | نوع التكامل |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأدنى للتكامل |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأعلى للتكامل |

**الإرجاع:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نسخة جديدة من النوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

يأخذ التكامل بدون حدود

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| integralType | int | نوع التكامل |

**الإرجاع:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نسخة جديدة من النوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

يأخذ التكامل

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| integralType | int | نوع التكامل |
| lowerLimit | java.lang.String | الحد الأدنى للتكامل |
| upperLimit | java.lang.String | الحد الأعلى للتكامل |
| limitLocations | int | موقع الحدود |

**الإرجاع:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نسخة جديدة من النوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

يأخذ التكامل

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| integralType | int | نوع التكامل |
| lowerLimit | java.lang.String | الحد الأدنى للتكامل |
| upperLimit | java.lang.String | الحد الأعلى للتكامل |

**الإرجاع:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - نسخة جديدة من النوع [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

يضبط علامة تشديد (حرف فوق هذا العنصر)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| accentCharacter | char | حرف التشديد. يجب أن تكون القيمة ضمن النطاق (U+0300-U+036F) أو (U+20D0-U+20EF) |

**الإرجاع:**
[IMathAccent](../../com.aspose.slides/imathaccent) - نسخة جديدة من النوع [IMathAccent](../../com.aspose.slides/imathaccent)

### overbar() {#overbar--}
```
public final IMathBar overbar()
```

يضبط شريطًا فوق هذا العنصر

--------------------

> ```
> مثال:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**الإرجاع:**
[IMathBar](../../com.aspose.slides/imathbar) - نسخة جديدة من النوع [IMathBar](../../com.aspose.slides/imathbar)

### underbar() {#underbar--}
```
public final IMathBar underbar()
```

يضبط شريطًا أسفل هذا العنصر

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
public final IMathGroupingCharacter group()
```

يوضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي

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
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

يوضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره

--------------------

> ```
> مثال:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| character | char | حرف التجميع مثل القوس المعقوف السفلي (U+23DF) أو أي حرف آخر |
| position | int | موضع حرف التجميع |
| verticalJustification | int | توجيه عمودي لحرف التجميع. يحدد محاذاة الكائن بالنسبة لخط الأساس. على سبيل المثال، عندما يكون حرف المجموعة أعلى الكائن، يعني VerticalJustification = Top أن أعلى الكائن يقع على خط الأساس؛ وعند تعيينه إلى Bottom يكون الجزء السفلي من الكائن على خط الأساس |

**الإرجاع:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - نسخة جديدة من النوع [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)

### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

يوضع هذا العنصر في صندوق حد

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
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

يوضع هذا العنصر في صندوق حد

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| hideTop | boolean | إخفاء الحافة العلوية |
| hideBottom | boolean | إخفاء الحافة السفلية |
| hideLeft | boolean | إخفاء الحافة اليسارية |
| hideRight | boolean | إخفاء الحافة اليمنية |
| strikethroughHorizontal | boolean | شطب أفقي لصندوق الحد |
| strikethroughVertical | boolean | شطب عمودي لصندوق الحد |
| strikethroughBottomLeftToTopRight | boolean | شطب من أسفل اليسار إلى أعلى اليمين |
| strikethroughTopLeftToBottomRight | boolean | شطب من أعلى اليسار إلى أسفل اليمين |

**الإرجاع:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - صندوق حد يحتوي هذا العنصر داخله

### toBox() {#toBox--}
```
public final IMathBox toBox()
```

يوضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو نص رياضي آخر. يمكن لكائن محاط بصندوق (على سبيل المثال) أن يعمل كمحاكي عامل مع أو بدون نقطة محاذاة، أو كنقطة كسر سطر، أو يُجمع بحيث لا يسمح بوجود فواصل سطر داخلية.

--------------------

> ```
> مثال:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**الإرجاع:**
[IMathBox](../../com.aspose.slides/imathbox) - صندوق منطقي يحتوي هذا العنصر داخله

### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

الحصول على العناصر الفرعية

**الإرجاع:**
com.aspose.slides.IMathElement[] - مصفوفة من [IMathElement](../../com.aspose.slides/imathelement)