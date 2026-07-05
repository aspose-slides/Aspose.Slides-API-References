---
title: IMathElement
second_title: Aspose.Slides لـ .NET مرجع API
description: الواجهة الأساسية لأي عنصر رياضي مثل الكسر أو النص الرياضي أو الدالة أو التعبير الذي يحتوي على عناصر متعددة وغيرها
type: docs
weight: 8230
url: /ar/aspose.slides.mathtext/imathelement/
---
## IMMathElement واجهة

الواجهة الأساسية لأي عنصر رياضي: كسر، نص رياضي، دالة، تعبير متعدد العناصر إلخ

```csharp
public interface IMathElement
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | يضبط علامة تشكيل (حرف فوق هذا العنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل ومعامل إضافي محدد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل ومعامل إضافي محدد |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | يحيط عنصر رياضي بأقواس |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | يحيط هذا العنصر بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | يأخذ دالة لمعلمة باستخدام هذه المثيلة كاسم الدالة |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | يأخذ دالة لمعلمة باستخدام هذه المثيلة كاسم الدالة |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | يحصل على العناصر الفرعية |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل قوس معقوف سفلي أو آخر |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | يأخذ التكامل بدون حدود |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | يأخذ التكامل |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | يجمع عنصرًا رياضيًا ويشكل كتلة رياضية |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | يجمع نصًا رياضيًا ويشكل كتلة رياضية |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | ينشئ عاملًا N-ary |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | ينشئ عاملًا N-ary |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | يضع شريطًا فوق هذا العنصر |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | يحدد الجذر الرياضي للدرجة المعطاة من المعلمة المحددة |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | يحدد الجذر الرياضي للدرجة المعطاة من المعلمة المحددة |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | يأخذ الحد الأدنى |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | يأخذ الحد الأدنى |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | ينشئ أسفل النص |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | ينشئ أسفل النص |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | ينشئ أسفل النص ومرتفعًا على اليسار |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | ينشئ أسفل النص ومرتفعًا على اليسار |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | ينشئ أسفل النص ومرتفعًا على اليمين |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | ينشئ أسفل النص ومرتفعًا على اليمين |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | ينشئ مرتفع النص |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | ينشئ مرتفع النص |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | يأخذ الحد الأعلى |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | يأخذ الحد الأعلى |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | يضع هذا العنصر في مربع حدود |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | يضع هذا العنصر في مربع حدود |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو نص رياضي آخر. يمكن أن يكون الصندوق المربع، على سبيل المثال، محاكيًا لمعامل مع أو بدون نقطة محاذاة، أو نقطة فاصل سطر، أو يُجمّع بحيث لا يُسمح بفواصل سطر داخلية. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | يضعه في مصفوفة رأسية |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | يضع شريطًا أسفل هذا العنصر |

### أمثلة

مثال:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### انظر أيضاً

* نطاق الاسم [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->