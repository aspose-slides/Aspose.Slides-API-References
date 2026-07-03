---
title: MathRadical
second_title: Aspose.Sildes لـ .NET مرجع API
description: يحدد الدالة الجذرية التي تتكون من أساس ودرجة اختيارية. مثال على كائن جذري هو .
type: docs
weight: 8940
url: /ar/aspose.slides.mathtext/mathradical/
---
## MathRadical فئة

يحدد الدالة الجذرية، التي تتكون من أساس ودرجة اختيارية. مثال على كائن جذري هو √𝑥.

```csharp
public sealed class MathRadical : MathElementBase, IMathRadical
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [MathRadical](mathradical)(IMathElement, IMathElement) | ينشئ مثيلاً جديداً من فئة MathRadical. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathradical/base) { get; } | معامل الأساس |
| [Degree](../../aspose.slides.mathtext/mathradical/degree) { get; } | معامل الدرجة |
| [HideDegree](../../aspose.slides.mathtext/mathradical/hidedegree) { get; set; } | إخفاء الدرجة. عندما تكون true، لا تُظهر الدرجة، كما في √𝑥 |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | يضبط علامة لهجة (حرف فوق هذا العنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل ومعامل إضافي محدد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل ومعامل إضافي محدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | ينشئ كسرًا مع هذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | ينشئ كسرًا مع هذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | يغلف عنصر رياضي بين قوسين |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | يغلف عنصر رياضي في الأحرف المحددة مثل القوس أو أحرف أخرى كإطار |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | يأخذ دالة لوسيط باستخدام هذه المثيلة كاسم الدالة |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | يأخذ دالة لوسيط باستخدام هذه المثيلة كاسم الدالة |
| [GetChildren](../../aspose.slides.mathtext/mathradical/getchildren)() | يحصل على عناصر الأطفال |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | يأخذ التكامل بدون حدود |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | يأخذ التكامل |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | يجمع عنصر رياضي ويشكل كتلة رياضية |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | يجمع نصًا رياضيًا ويشكل كتلة رياضية |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | ينشئ معامل N-اري |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | ينشئ معامل N-اري |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | يضبط شريطًا أعلى هذا العنصر |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | يأخذ الحد الأدنى |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | يأخذ الحد الأدنى |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | ينشئ مؤشرًا سفليًا |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | ينشئ مؤشرًا سفليًا |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | ينشئ مؤشرًا سفليًا وعاليًا على اليسار |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | ينشئ مؤشرًا سفليًا وعاليًا على اليسار |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | ينشئ مؤشرًا سفليًا وعاليًا على اليمين |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | ينشئ مؤشرًا سفليًا وعاليًا على اليمين |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | ينشئ مؤشرًا علويًا |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | ينشئ مؤشرًا علويًا |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | يأخذ الحد الأعلى |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | يأخذ الحد الأعلى |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | يضع هذا العنصر في صندوق حدود |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | يضع هذا العنصر في صندوق حدود |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو نص رياضي آخر. يمكن أن يكون الكائن المضمن (على سبيل المثال) محاكيًا للمشغل مع أو بدون نقطة محاذاة، أو نقطة كسر سطر، أو مُجَمَّعًا بحيث لا يسمح بكسور السطر داخله. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | يضع في مصفوفة رأسية |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | يضبط شريطًا أسفل هذا العنصر |

### أمثلة

مثال:

```csharp
[C#]
MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
```

### أنظر أيضًا

* فئة [MathElementBase](../mathelementbase)
* واجهة [IMathRadical](../imathradical)
* مساحة الاسم [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->