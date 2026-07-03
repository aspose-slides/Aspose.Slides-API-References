---
title: MathSuperscriptElement
second_title: Aspose.Sildes لـ .NET مرجع API
description: يحدد كائن السوبريسكريبت الذي يتكون من قاعدة وسوبريسكريبت بحجم أصغر موضع أعلى اليمين
type: docs
weight: 9020
url: /ar/aspose.slides.mathtext/mathsuperscriptelement/
---
## MathSuperscriptElement فئة

يحدد كائن السوبريسكريبت، الذي يتكون من قاعدة وسوبريسكريبت بحجم أصغر موضع أعلى اليمين

```csharp
public sealed class MathSuperscriptElement : BaseScript, IMathSuperscriptElement
```

## المنشئات

| Name | Description |
| --- | --- |
| [MathSuperscriptElement](mathsuperscriptelement)(IMathElement, IMathElement) | يقوم بإنشاء نسخة جديدة من فئة MathSuperscriptElement. |

## الخصائص

| Name | Description |
| --- | --- |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | معامل القاعدة |
| [Superscript](../../aspose.slides.mathtext/mathsuperscriptelement/superscript) { get; } | الرفع |

## الطرق

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | يضبط علامة لهجة (حرف على قمة هذا العنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | يأخذ الدالة المحددة باستخدام هذه النسخة كوسيط |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | يأخذ الدالة المحددة باستخدام هذه النسخة كوسيط |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | يأخذ الدالة المحددة باستخدام هذه النسخة كوسيط |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | يأخذ الدالة المحددة باستخدام هذه النسخة كوسيط وإضافة معامل إضافي محدد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | يأخذ الدالة المحددة باستخدام هذه النسخة كوسيط وإضافة معامل إضافي محدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | ينشئ كسرًا مع هذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | ينشئ كسرًا مع هذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | ينشئ كسرًا من النوع المحدد مع هذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | ينشئ كسرًا من النوع المحدد مع هذا البسط والمقام المحدد |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | يغلف عنصر رياضي بأقواس |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | يحيط عنصر رياضي بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | يأخذ دالة معامل باستخدام هذه النسخة كاسم الدالة |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | يأخذ دالة معامل باستخدام هذه النسخة كاسم الدالة |
| [GetChildren](../../aspose.slides.mathtext/mathsuperscriptelement/getchildren)() | يحصل على العناصر الفرعية |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | يوضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | يوضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | يأخذ التكامل بدون حدود |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | يأخذ التكامل |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | يجمع عنصرًا رياضيًا ويكوّن كتلة رياضية |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | يجمع نصًا رياضيًا ويكوّن كتلة رياضية |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | ينشئ معامل N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | ينشئ معامل N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | يضبط شريطًا أعلى هذا العنصر |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | يأخذ الحد الأدنى |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | يأخذ الحد الأدنى |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | ينشئ نصًا سفليًا |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | ينشئ نصًا سفليًا |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | ينشئ نصًا سفليًا وعلويًا على اليسار |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | ينشئ نصًا سفليًا وعلويًا على اليسار |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | ينشئ نصًا سفليًا وعلويًا على اليمين |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | ينشئ نصًا سفليًا وعلويًا على اليمين |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | ينشئ نصًا علويًا |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | ينشئ نصًا علويًا |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | يأخذ الحد الأعلى |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | يأخذ الحد الأعلى |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | يوضع هذا العنصر في صندوق حدود |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | يوضع هذا العنصر في صندوق حدود |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | يوضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو نص رياضي آخر. يمكن للعنصر المضمن أن يعمل (على سبيل المثال) كمحاكي عامل مع أو بدون نقطة محاذاة، أو كنقطة كسر سطر، أو يُجمع بحيث لا يسمح بكسر السطر داخله. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | يضع في صف عمودي |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | يضبط شريطًا أسفل هذا العنصر |

### أمثلة

Example:

```csharp
[C#]
MathSuperscriptElement superscriptElement = new MathematicalText("N").SetSuperscript("i");
```

### انظر أيضًا

* فئة [BaseScript](../basescript)
* واجهة [IMathSuperscriptElement](../imathsuperscriptelement)
* مساحة اسم [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->