---
title: MathFunction
second_title: Aspose.Sildes لـ .NET مرجع API
description: يحدد دالة ذات معامل.
type: docs
weight: 8720
url: /ar/aspose.slides.mathtext/mathfunction/
---
## MathFunction فئة

يحدد دالة ذات معامل.

```csharp
public sealed class MathFunction : MathElementBase, IMathFunction
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [MathFunction](mathfunction#constructor)(IMathElement, IMathElement) | ينشئ مثيلاً جديدًا من فئة MathFunction. |
| [MathFunction](mathfunction#constructor_1)(string, IMathElement) | ينشئ مثيلاً جديدًا من فئة MathFunction. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathfunction/base) { get; } | معامل الدالة |
| [Name](../../aspose.slides.mathtext/mathfunction/name) { get; } | اسم الدالة. على سبيل المثال، أسماء الدوال هي sin و cos |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | يحدد علامة شدة (حرفًا أعلى هذا العنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | يحدد الدالة المحددة باستخدام هذا الكائن كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | يحدد الدالة المحددة باستخدام هذا الكائن كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | يحدد الدالة المحددة باستخدام هذا الكائن كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | يحدد الدالة المحددة باستخدام هذا الكائن كمعامل ومعامل إضافي محدد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | يحدد الدالة المحددة باستخدام هذا الكائن كمعامل ومعامل إضافي محدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | يضع عنصر رياضي بين أقواس |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | يضع عنصر رياضي بين الأحرف المحددة مثل الأقواس أو أحرف أخرى كإطار |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | يحدد دالة لوسيط باستخدام هذا الكائن كاسم الدالة |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | يحدد دالة لوسيط باستخدام هذا الكائن كاسم الدالة |
| [GetChildren](../../aspose.slides.mathtext/mathfunction/getchildren)() | يحصل على العناصر الفرعية |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | يوضع هذا العنصر في مجموعة باستخدام قوسٍ معقوف سفلي |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | يوضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | يحدد التكامل بدون حدود |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | يحدد التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | يحدد التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | يحدد التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | يحدد التكامل |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | يجمع عنصرًا رياضيًا ويشكل كتلة رياضية |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | يجمع نصًا رياضيًا ويشكل كتلة رياضية |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | ينشئ عاملًا متعدد المتغيرات |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | ينشئ عاملًا متعدد المتغيرات |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | يضع شريطًا فوق هذا العنصر |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | يحدد الحد الأدنى |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | يحدد الحد الأدنى |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | ينشئ نصًا سفليًا |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | ينشئ نصًا سفليًا |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | ينشئ نصًا سفليًا وعليا على اليسار |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | ينشئ نصًا سفليًا وعليا على اليسار |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | ينشئ نصًا سفليًا وعليا على اليمين |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | ينشئ نصًا سفليًا وعليا على اليمين |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | ينشئ نصًا عليًا |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | ينشئ نصًا عليًا |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | يحدد الحد الأعلى |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | يحدد الحد الأعلى |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | يوضع هذا العنصر في صندوق حدودي |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | يوضع هذا العنصر في صندوق حدودي |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | يوضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو نص رياضي آخر. يمكن أن يعمل الكائن المضمن كمحاكي عامل مع أو بدون نقطة محاذاة، أو كنقطة فواصل سطر، أو يُجمع بحيث لا يسمح بفواصل أسطر داخله. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | يضع في مصفوفة عمودية |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | يضع شريطًا أسفل هذا العنصر |

### أمثلة

```csharp
[C#]
MathFunction func = new MathFunction("sin", new MathematicalText("x"));
```

### انظر أيضًا

* فئة [MathElementBase](../mathelementbase)
* واجهة [IMathFunction](../imathfunction)
* النطاق [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->