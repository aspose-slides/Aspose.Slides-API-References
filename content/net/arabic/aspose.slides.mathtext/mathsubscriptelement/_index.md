---
title: MathSubscriptElement
second_title: Aspose.Sildes لـ .NET مرجع API
description: يحدد كائن المؤشر السفلي الذي يتكون من قاعدة ومؤشر سفلي بحجم مصغر موضوع أسفل وعلى اليمين.
type: docs
weight: 9000
url: /ar/aspose.slides.mathtext/mathsubscriptelement/
---
## فئة MathSubscriptElement

Specifies the subscript object, which consists of a base and a reduced-size subscript placed below and to the right.

```csharp
public sealed class MathSubscriptElement : BaseScript, IMathSubscriptElement
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MathSubscriptElement](mathsubscriptelement)(IMathElement, IMathElement) | يُنشئ مثيلًا جديدًا من الفئة MathSubscriptElement. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | الوسيط الأساسي |
| [Subscript](../../aspose.slides.mathtext/mathsubscriptelement/subscript) { get; } | المؤشر |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | يضبط علامة تشكيل (حرف في أعلى هذا العنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | يأخذ الدالة المحددة مستخدمًا هذا المثيل كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | يأخذ الدالة المحددة مستخدمًا هذا المثيل كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | يأخذ الدالة المحددة مستخدمًا هذا المثيل كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | يأخذ الدالة المحددة مستخدمًا هذا المثيل كمعامل ومعامل إضافي محدد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | يأخذ الدالة المحددة مستخدمًا هذا المثيل كمعامل ومعامل إضافي محدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | ينشئ كسرًا بهذا البسط والحد المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | ينشئ كسرًا بهذا البسط والحد المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والحد المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والحد المحدد |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | يحيط عنصرًا رياضيًا بأقواس |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | يحيط عنصرًا رياضيًا بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | يأخذ دالة للمعامل مستخدمًا هذا المثيل كاسم الدالة |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | يأخذ دالة للمعامل مستخدمًا هذا المثيل كاسم الدالة |
| [GetChildren](../../aspose.slides.mathtext/mathsubscriptelement/getchildren)() | يحصل على عناصر الأطفال |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | يأخذ التكامل بدون حدود |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | يأخذ التكامل |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | يجمع عنصرًا رياضيًا ويشكّل كتلة رياضية |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | يجمع نصًا رياضيًا ويشكّل كتلة رياضية |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | ينشئ معاملًا من N |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | ينشئ معاملًا من N |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | يضبط شريطًا أعلى هذا العنصر |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | يأخذ الحد الأدنى |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | يأخذ الحد الأدنى |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | ينشئ مؤشرًا سفليًا |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | ينشئ مؤشرًا سفليًا |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | ينشئ مؤشراً سفليًا وعلوياً على اليسار |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | ينشئ مؤشراً سفليًا وعلوياً على اليسار |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | ينشئ مؤشراً سفليًا وعلوياً على اليمين |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | ينشئ مؤشراً سفليًا وعلوياً على اليمين |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | ينشئ مؤشرًا علويًا |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | ينشئ مؤشرًا علويًا |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | يأخذ الحد الأعلى |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | يأخذ الحد الأعلى |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | يضع هذا العنصر في صندوق حدود |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | يضع هذا العنصر في صندوق حدود |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو مثال آخر من النص الرياضي. يمكن أن يعمل الكائن المعبأ (على سبيل المثال) كمحاكي للمعامل مع أو بدون نقطة محاذاة، أو كنقطة لكسر السطر، أو يُجمع بحيث لا يسمح بكسر الأسطر داخله. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | يضعه في مصفوفة رأسية |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | يضبط شريطًا أسفل هذا العنصر |

### أمثلة

مثال:

```csharp
[C#]
MathSubscriptElement subscriptElement = new MathematicalText("N").SetSubscript("i");
```

### أنظر أيضًا

* فئة [BaseScript](../basescript)
* واجهة [IMathSubscriptElement](../imathsubscriptelement)
* نطاق [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* تجميعة [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->