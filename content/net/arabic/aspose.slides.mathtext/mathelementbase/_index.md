---
title: MathElementBase
second_title: مرجع API لـ Aspose.Sildes for .NET
description: الفئة الأساسية لـ IMathElement مع تنفيذ بعض الطرق المشتركة بين جميع الفئات الموروثة. للاستخدام الداخلي فقط. يجب أن تكون الفئة الموروثة IMathElement.
type: docs
weight: 8680
url: /ar/aspose.slides.mathtext/mathelementbase/
---
## MathElementBase فئة

الفئة الأساسية لIMathElement مع تنفيذ بعض الطرق التي هي مشتركة لجميع الفئات الموروثة للاستخدام الداخلي فقط. يجب أن تكون الفئة الموروثة IMMathElement.

```csharp
public abstract class MathElementBase : IMathElement
```

## طرق

| الاسم | الوصف |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | يضبط علامة إكسنت (حرف على أعلى هذا العنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction)(IMathElement) | يأخذ الدالة المحددة باستخدام هذه النسخة كوسيطة |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | يأخذ الدالة المحددة باستخدام هذه النسخة كوسيطة |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_4)(string) | يأخذ الدالة المحددة باستخدام هذه النسخة كوسيطة |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | يأخذ الدالة المحددة باستخدام هذه النسخة كوسيطة والوسيطة الإضافية المحددة |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | يأخذ الدالة المحددة باستخدام هذه النسخة كوسيطة والوسيطة الإضافية المحددة |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide)(IMathElement) | ينشئ كسرًا باستخدام هذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_2)(string) | ينشئ كسرًا باستخدام هذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_1)(IMathElement, MathFractionTypes) | ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_3)(string, MathFractionTypes) | ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose)() | يغلف عنصر رياضيًا بأقواس |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose_1)(char, char) | يغلف عنصر رياضي بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function)(IMathElement) | يأخذ دالة لوسيط باستخدام هذه النسخة كاسم الدالة |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function_1)(string) | يأخذ دالة لوسيط باستخدام هذه النسخة كاسم الدالة |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group)() | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral)(MathIntegralTypes) | يأخذ التكامل بدون حدود |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_3)(MathIntegralTypes, string, string) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | يأخذ التكامل |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join)(IMathElement) | يجمع عنصرًا رياضيًا ويشكل كتلة رياضية |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join_1)(string) | يجمع نصًا رياضيًا ويشكل كتلة رياضية |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | ينشئ مشغلًا N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary_1)(MathNaryOperatorTypes, string, string) | ينشئ مشغلًا N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | يضبط شريطًا أعلى هذا العنصر |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical)(IMathElement) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيطة المحددة. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical_1)(string) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيطة المحددة. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit)(IMathElement) | يأخذ الحد الأدنى |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit_1)(string) | يأخذ الحد الأدنى |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript)(IMathElement) | ينشئ مؤشرًا سفليًا |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript_1)(string) | ينشئ مؤشرًا سفليًا |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | ينشئ مؤشرًا سفليًا وأعلى على اليسار |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | ينشئ مؤشرًا سفليًا وأعلى على اليسار |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | ينشئ مؤشرًا سفليًا وأعلى على اليمين |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | ينشئ مؤشرًا سفليًا وأعلى على اليمين |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript)(IMathElement) | ينشئ مؤشرًا علويًا |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript_1)(string) | ينشئ مؤشرًا علويًا |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit)(IMathElement) | يأخذ الحد الأعلى |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit_1)(string) | يأخذ الحد الأعلى |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox)() | يضع هذا العنصر في صندوق حدود |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | يضع هذا العنصر في صندوق حدود |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو مثال آخر من النص الرياضي. يمكن لكائن محاط بصندوق (على سبيل المثال) أن يعمل كمحاكي عامل مع أو بدون نقطة محاذاة، أو كنقطة كسر سطر، أو أن يُجمع بحيث لا يُسمح بكسر الأسطر داخله. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | يضع في مصفوفة رأسية |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | يضبط شريطًا أسفل هذا العنصر |

### انظر أيضاً

* واجهة [IMathElement](../imathelement)
* مساحة اسم [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->