---
title: IMathElement
second_title: Aspose.Sildes لـ .NET مرجع API
description: الواجهة الأساسية لأي عنصر رياضي مثل الكسر أو النص الرياضي أو الدالة أو التعبير الذي يحتوي على عدة عناصر إلخ
type: docs
weight: 8230
url: /ar/aspose.slides.mathtext/imathelement/
---
## واجهة IMMathElement

الواجهة الأساسية لأي عنصر رياضي: كسر، نص رياضي، دالة، تعبير يحتوي على عدة عناصر وغيرها

```csharp
public interface IMathElement
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | يضبط علامة التشكيل (حرف على أعلى هذا العنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | يأخذ الدالة المحددة باستخدام هذه المثيلة كوسيطة |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | يأخذ الدالة المحددة باستخدام هذه المثيلة كوسيطة |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | يأخذ الدالة المحددة باستخدام هذه المثيلة كوسيطة |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | يأخذ الدالة المحددة باستخدام هذه المثيلة كوسيطة والوسيط الإضافي المحدد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | يأخذ الدالة المحددة باستخدام هذه المثيلة كوسيطة والوسيط الإضافي المحدد |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | يغلف عنصرًا رياضيًا بأقواس |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | يغلف هذا العنصر بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | يأخذ دالة لوسيط باستخدام هذه المثيلة كاسم الدالة |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | يأخذ دالة لوسيط باستخدام هذه المثيلة كاسم الدالة |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | احصل على العناصر الفرعية |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | يضع هذا العنصر في مجموعة باستخدام قوس مجعد سفلي |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المجعد السفلي أو غيره |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | يأخذ التكامل بدون حدود |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | يأخذ التكامل |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | يجمع عنصرًا رياضيًا ويشكل كتلة رياضية |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | يجمع نصًا رياضيًا ويشكل كتلة رياضية |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | ينشئ مشغلًا N-اريًا |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | ينشئ مشغلًا N-اريًا |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | يضبط شريطًا على أعلى هذا العنصر |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد. |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد. |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | يأخذ الحد السفلي |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | يأخذ الحد السفلي |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | ينشئ موضعًا سفليًا |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | ينشئ موضعًا سفليًا |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | ينشئ موضعًا سفليًا وعليا على اليسار |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | ينشئ موضعًا سفليًا وعليا على اليسار |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | ينشئ موضعًا سفليًا وعليا على اليمين |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | ينشئ موضعًا سفليًا وعليا على اليمين |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | ينشئ موضعًا علويًا |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | ينشئ موضعًا علويًا |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | يأخذ الحد الأعلى |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | يأخذ الحد الأعلى |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | يضع هذا العنصر في صندوق حدود |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | يضع هذا العنصر في صندوق حدود |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو غيرها من النصوص الرياضية. يمكن أن يعمل الكائن المربع (مثلاً) كمحاكي لمشغل مع أو بدون نقطة محاذاة، أو كنقطة كسر سطر، أو يتم تجميعه بحيث لا يسمح بوجود فواصل سطرية داخله. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | يضع في مصفوفة عمودية |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | يضع شريطًا في أسفل هذا العنصر |

### أمثلة

مثال:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### أنظر أيضًا

* مساحة الاسم [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->