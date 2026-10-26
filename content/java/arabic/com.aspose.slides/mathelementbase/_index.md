---
title: MathElementBase
second_title: Aspose.Slides لـ Java API مرجع
description: الفئة الأساسية لـ IMMathElement مع تنفيذ بعض الطرق المشتركة بين جميع الفئات الموروثة للاستخدام الداخلي فقط.
type: docs
url: /ar/com.aspose.slides/mathelementbase/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject  
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

الفئة الأساسية لـ IMathElement مع تنفيذ بعض الأساليب المشتركة بين جميع الفئات الموروثة. للاستخدام الداخلي فقط. يجب أن تكون الفئة الموروثة هي IMathElement.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | إرجاع كائن Parent_Immediate. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | يجمع عنصرًا رياضيًا ويكوّن كتلة رياضية |
| [join(String mathText)](#join-java.lang.String-) | يجمع نصًا رياضيًا ويكوّن كتلة رياضية |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [divide(String denominator)](#divide-java.lang.String-) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [enclose()](#enclose--) | يغلق عنصرًا رياضيًا بين قوسين |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | يغلق عنصرًا رياضيًا بأحرف محددة مثل القوس أو أحرف أخرى كإطار |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | يأخذ دالة للوسيط باستخدام هذه النسخة كاسم الدالة |
| [function(String functionArgument)](#function-java.lang.String-) | يأخذ دالة للوسيط باستخدام هذه النسخة كاسم الدالة |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | يأخذ دالة محددة باستخدام هذه النسخة كوسيط |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | يأخذ دالة محددة باستخدام هذه النسخة كوسيط |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | يأخذ دالة محددة باستخدام هذه النسخة كوسيط |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | يأخذ دالة محددة باستخدام هذه النسخة كوسيط ووسيط إضافي محدد |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | يأخذ دالة محددة باستخدام هذه النسخة كوسيط ووسيط إضافي محدد |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | ينشئ نصًا تحتيًا |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | ينشئ نصًا تحتيًا |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | ينشئ نصًا فوقيًا |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | ينشئ نصًا فوقيًا |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ينشئ نصًا تحتيًا وفوقيًا على اليمين |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | ينشئ نصًا تحتيًا وفوقيًا على اليمين |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ينشئ نصًا تحتيًا وفوقيًا على اليسار |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | ينشئ نصًا تحتيًا وفوقيًا على اليسار |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد. |
| [radical(String degree)](#radical-java.lang.String-) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | يأخذ الحد الأعلى |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | يأخذ الحد الأعلى |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | يأخذ الحد الأدنى |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | يأخذ الحد الأدنى |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ينشئ مشغلًا متعدد حدّية |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | ينشئ مشغلًا متعدد حدّية |
| [toMathArray()](#toMathArray--) | يضع في مصفوفة عمودية |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | يأخذ التكامل |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | يأخذ التكامل |
| [integral(int integralType)](#integral-int-) | يأخذ التكامل بدون حدود |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | يأخذ التكامل |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | يأخذ التكامل |
| [accent(char accentCharacter)](#accent-char-) | يضبط علامة التشكيل (حرف فوق هذا العنصر) |
| [overbar()](#overbar--) | يضبط شريطًا فوق هذا العنصر |
| [underbar()](#underbar--) | يضبط شريطًا أسفل هذا العنصر |
| [group()](#group--) | يوضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | يوضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [toBorderBox()](#toBorderBox--) | يوضع هذا العنصر في صندوق حدود |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | يوضع هذا العنصر في صندوق حدود |
| [toBox()](#toBox--) | يوضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو مثال آخر للنص الرياضي. |
| [getChildren()](#getChildren--) | احصل على العناصر الفرعية |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

إرجاع كائن Parent_Immediate. قراءة فقط IDOMObject.

**الإرجاع:**  
com.aspose.slides.IDOMObject

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

يجمع عنصرًا رياضيًا ويكوّن كتلة رياضية

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
[IMathBlock](../../com.aspose.slides/imathblock) - عنصر جديد من نوع IMathBlock يحتوي على هذه النسخة والوسيطة المحددة

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

يجمع نصًا رياضيًا ويكوّن كتلة رياضية

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
[IMathBlock](../../com.aspose.slides/imathblock) - عنصر جديد من نوع IMathBlock يحتوي على هذه النسخة والوسيطة المحددة

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
| المعامل | النوع | الوصف |
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
> مثال:
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
| المعامل | النوع | الوصف |
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
> مثال:
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
public final IMathDelimiter enclose()
```

يغلق عنصرًا رياضيًا بين قوسين

--------------------

> ```
> مثال:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```


**الإرجاع:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - العنصر الرياضي من النوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) والذي يشمل القوسين

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

يغلق عنصرًا رياضيًا بأحرف محددة مثل القوس أو أحرف أخرى كإطار

--------------------

> ```
> مثال:
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
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - العنصر الرياضي من النوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) والذي يشمل الأحرف المحددة كإطار

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

يأخذ دالة للوسيط باستخدام هذه النسخة كاسم الدالة

--------------------

> ```
> مثال:
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
public final IMathFunction function(String functionArgument)
```

يأخذ دالة للوسيط باستخدام هذه النسخة كاسم الدالة

--------------------

> ```
> مثال:
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
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

يأخذ دالة محددة باستخدام هذه النسخة كوسيط

--------------------

> ```
> مثال:
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
public final IMathFunction asArgumentOfFunction(String functionName)
```

يأخذ دالة محددة باستخدام هذه النسخة كوسيط

--------------------

> ```
> مثال:
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
public final IMathFunction asArgumentOfFunction(int functionType)
```

يأخذ دالة محددة باستخدام هذه النسخة كوسيط

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
| functionType | int | أحد الأنواع الشائعة للدوال ذات وسيط واحد |

**الإرجاع:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

يأخذ دالة محددة باستخدام هذه النسخة كوسيط ووسيط إضافي محدد

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // يعيد اللوغاريتم لـ 'x' إلى الأساس '5'
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionType | int | أحد الأنواع الشائعة للدوال ذات وسيطين: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | وسيط إضافي يعتمد على نوع الدالة |

**الإرجاع:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

يأخذ دالة محددة باستخدام هذه النسخة كوسيط ووسيط إضافي محدد

--------------------

> ```
> مثال:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // يعيد اللوغاريتم لـ 'x' إلى الأساس '5'
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionType | int | أحد الأنواع الشائعة للدوال ذات وسيطين: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | وسيط إضافي يعتمد على نوع الدالة |

**الإرجاع:**
[IMathFunction](../../com.aspose.slides/imathfunction) - عنصر رياضي جديد من النوع [IMathFunction](../../com.aspose.slides/imathfunction)

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

ينشئ نصًا تحتيًا

--------------------

> ```
> مثال:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | نص تحتي (مؤشر سفلي على اليمين) |

**الإرجاع:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - عنصر رياضي جديد من النوع [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

ينشئ نصًا تحتيًا

--------------------

> ```
> مثال:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| subscript | java.lang.String | نص تحتي (مؤشر سفلي على اليمين) |

**الإرجاع:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - عنصر رياضي جديد من النوع [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

ينشئ نصًا فوقيًا

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
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | نص فوقي (مؤشر علوي على اليمين) |

**الإرجاع:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - عنصر رياضي جديد من النوع [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

ينشئ نصًا فوقيًا

--------------------

> ```
> مثال:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| superscript | java.lang.String | نص فوقي (مؤشر علوي على اليمين) |

**الإرجاع:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - عنصر رياضي جديد من النوع [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

ينشئ نصًا تحتيًا وفوقيًا على اليمين

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | نص تحتي (مؤشر سفلي على اليمين) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | نص فوقي (مؤشر علوي على اليمين) |

**الإرجاع:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - عنصر رياضي جديد من النوع [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

ينشئ نصًا تحتيًا وفوقيًا على اليمين
> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (lower index on the right) |
| superscript | java.lang.String | Superscript (upper index on the right) |

**الإرجاع:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - New math element of type [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

ينشئ نصًا فرعيًا ونصًا فوقيًا على اليسار

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscript (lower index on the left) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superscript (upper index on the left) |

**الإرجاع:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - New math element of type [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

ينشئ نصًا فرعيًا ونصًا فوقيًا على اليسار

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (lower index on the left) |
| superscript | java.lang.String | Superscript (upper index on the left) |

**الإرجاع:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - New math element of type [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
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


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argument of Radical |

**الإرجاع:**
[IMathRadical](../../com.aspose.slides/imathradical) - New instance of type [IMathRadical](../../com.aspose.slides/imathradical)
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


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| degree | java.lang.String | Argument of Radical |

**الإرجاع:**
[IMathRadical](../../com.aspose.slides/imathradical) - New instance of type [IMathRadical](../../com.aspose.slides/imathradical)
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


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**الإرجاع:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
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


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| limit | java.lang.String | limit |

**الإرجاع:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

يأخذ الحد السفلي

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**الإرجاع:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

يأخذ الحد السفلي

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| limit | java.lang.String | limit |

**الإرجاع:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

ينشئ عامل N-ary

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | int | The N-ary operator type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | The lower limit |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | The upper limit |

**الإرجاع:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

ينشئ عامل N-ary

--------------------

> ```
> مثال:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | int | The N-ary operator type |
| lowerLimit | java.lang.String | The lower limit |
| upperLimit | java.lang.String | The upper limit |

**الإرجاع:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

يضع في مصفوفة عمودية

--------------------

> ```
> مثال:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**الإرجاع:**
[IMathArray](../../com.aspose.slides/imatharray) - New instance of type [IMathArray](../../com.aspose.slides/imatharray)
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
```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit of integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Upper limit of integral |
| limitLocations | int | location of limits |

**الإرجاع:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit of integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Upper limit of integral |

**الإرجاع:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

يأخذ التكامل بدون حدود

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| integralType | int | Integral type |

**الإرجاع:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
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


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | java.lang.String | Lower limit of integral |
| upperLimit | java.lang.String | Upper limit of integral |
| limitLocations | int | location of limits |

**الإرجاع:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
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


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | java.lang.String | Lower limit of integral |
| upperLimit | java.lang.String | Upper limit of integral |

**الإرجاع:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

يضبط علامة تشديد (حرف فوق هذا العنصر)

--------------------

> ```
> مثال:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| accentCharacter | char | Accent character. The value should be within the range of (U+0300\\u2013U+036F) or (U+20D0\\u2013U+20EF) |

**الإرجاع:**
[IMathAccent](../../com.aspose.slides/imathaccent) - New instance of type [IMathAccent](../../com.aspose.slides/imathaccent)
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
[IMathBar](../../com.aspose.slides/imathbar) - New instance of type [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public final IMathBar underbar()
```

يضبط شريطًا تحت هذا العنصر

--------------------

> ```
> مثال:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**الإرجاع:**
[IMathBar](../../com.aspose.slides/imathbar) - New instance of type [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public final IMathGroupingCharacter group()
```

يضع هذا العنصر في مجموعة باستخدام قوس تجعيري سفلي

--------------------

> ```
> مثال:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**الإرجاع:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - New instance of type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس التجعيري السفلي أو غيره

--------------------

> ```
> مثال:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| character | char | Grouping Character such as BOTTOM CURLY BRACKET (U+23DF) or any other |
| position | int | Position of grouping character |
| verticalJustification | int | Vertical justification of group character. Specifies the alignment of the object with respect to the baseline. For example, when the group character is above the object, VerticalJustification of Top signifies that the top of the object falls on the baseline; when VerticalJustification is set to Bottom, the bottom of the object is on the baseline |

**الإرجاع:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - New instance of type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

يضع هذا العنصر في صندوق حدّي

--------------------

> ```
> مثال:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```


**الإرجاع:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box with this element placed inside
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

يضع هذا العنصر في صندوق حدّي

--------------------

> ```
> مثال:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| hideTop | boolean | Hide Top Edge |
| hideBottom | boolean | Hide Bottom Edge |
| hideLeft | boolean | Hide Left Edge |
| hideRight | boolean | Hide Right Edge |
| strikethroughHorizontal | boolean | Border Box Strikethrough Horizontal |
| strikethroughVertical | boolean | Border Box Strikethrough Vertical |
| strikethroughBottomLeftToTopRight | boolean | Border Box Strikethrough Bottom-Left to Top-Right |
| strikethroughTopLeftToBottomRight | boolean | Border Box Strikethrough Top-Left to Bottom-Right |

**الإرجاع:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box with this element placed inside
### toBox() {#toBox--}
```
public final IMathBox toBox()
```

يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو نص رياضي آخر. يمكن لكائن محاط بصندوق (مثلاً) أن يعمل كمحاكي عامل مع أو بدون نقطة محاذاة، أو كنقطة كسر سطر، أو أن يُجمع بحيث لا يُسمح بكسور السطر داخله.

--------------------

> ```
> مثال:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**الإرجاع:**
[IMathBox](../../com.aspose.slides/imathbox) - Logical box with this element placed inside
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

احصل على عناصر الأطفال

**الإرجاع:**
com.aspose.slides.IMathElement[] - Array of [IMathElement](../../com.aspose.slides/imathelement)