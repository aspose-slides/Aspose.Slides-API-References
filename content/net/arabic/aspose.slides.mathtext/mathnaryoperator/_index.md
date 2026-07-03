---
title: MathNaryOperator
second_title: Aspose.Sildes لـ .NET مرجع API
description: يحدد كائنًا رياضيًا متعدد الحد مثل الجمع والتكامل. يتكون من عامل، قاعدة أو معامل، وحدود عليا وسفلى اختيارية. أمثلة على العوامل متعددة الحد هي الجمع والاتحاد والتقاطع والتكامل
type: docs
weight: 8870
url: /ar/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator فئة

يحدد كائنًا رياضيًا متعدد الحد (N-ary)، مثل الجمع والتكامل. يتكون من عامل، وأساسة (أو معامل)، وحدود علوية وسفلية اختيارية. أمثلة على العوامل متعددة الحد هي: الجمع، الاتحاد، التقاطع، التكامل

```csharp
public sealed class MathNaryOperator : MathElementBase, IMathNaryOperator
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MathNaryOperator](mathnaryoperator#constructor)(char, IMathElement) | ينشئ مثيلًا جديدًا من فئة MathNaryOperator. |
| [MathNaryOperator](mathnaryoperator#constructor_1)(char, IMathElement, IMathElement) | ينشئ مثيلًا جديدًا من فئة MathNaryOperator. |
| [MathNaryOperator](mathnaryoperator#constructor_2)(char, IMathElement, IMathElement, IMathElement) | ينشئ مثيلًا جديدًا من فئة MathNaryOperator. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathnaryoperator/base) { get; } | الحجة الأساسية |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathnaryoperator/growtomatchoperandheight) { get; set; } | حرف العامل ينمو عموديًا ليتطابق مع ارتفاع المعامل |
| [HideSubscript](../../aspose.slides.mathtext/mathnaryoperator/hidesubscript) { get; set; } | إخفاء النص السفلي |
| [HideSuperscript](../../aspose.slides.mathtext/mathnaryoperator/hidesuperscript) { get; set; } | إخفاء النص العلوي |
| [LimitLocation](../../aspose.slides.mathtext/mathnaryoperator/limitlocation) { get; set; } | موقع الحدود (النص السفلي والنص العلوي) |
| [Operator](../../aspose.slides.mathtext/mathnaryoperator/operator) { get; set; } | حرف عامل متعدد الحد، على سبيل المثال: '∑', '∫' |
| [Subscript](../../aspose.slides.mathtext/mathnaryoperator/subscript) { get; } | يحدد حجة نص سفلي، على سبيل المثال في حالة التكامل، يحدد الحد السفلي |
| [Superscript](../../aspose.slides.mathtext/mathnaryoperator/superscript) { get; } | يحدد حجة نص علوي، على سبيل المثال في حالة التكامل، يحدد الحد العلوي |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | يضبط علامة شدة (حرف فوق هذا العنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | ينفذ الدالة المحددة باستخدام هذا المثيل كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | ينفذ الدالة المحددة باستخدام هذا المثيل كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | ينفذ الدالة المحددة باستخدام هذا المثيل كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | ينفذ الدالة المحددة باستخدام هذا المثيل كمعامل ويضيف معاملًا إضافيًا محددًا |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | ينفذ الدالة المحددة باستخدام هذا المثيل كمعامل ويضيف معاملًا إضافيًا محددًا |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | يحيط عنصرًا رياضيًا بأقواس |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | يحيط عنصرًا رياضيًا بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | ينفذ دالة بحجة باستخدام هذا المثيل كاسم الدالة |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | ينفذ دالة بحجة باستخدام هذا المثيل كاسم الدالة |
| [GetChildren](../../aspose.slides.mathtext/mathnaryoperator/getchildren)() | الحصول على العناصر الفرعية |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | يضع هذا العنصر في مجموعة باستخدام القوس المعقوف السفلي |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | يأخذ التكامل بدون حدود |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | يأخذ التكامل |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | ينضم عنصرًا رياضيًا ويشكل كتلة رياضية |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | ينضم نصًا رياضيًا ويشكل كتلة رياضية |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | ينشئ عاملًا متعدد الحد |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | ينشئ عاملًا متعدد الحد |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | يضبط شريطًا أعلى هذا العنصر |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | يحدد الجذر الرياضي للدرجة المعطاة من الحجة المحددة. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | يحدد الجذر الرياضي للدرجة المعطاة من الحجة المحددة. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | يأخذ الحد السفلي |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | يأخذ الحد السفلي |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | ينشئ نصًا سفليًا |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | ينشئ نصًا سفليًا |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | ينشئ نصًا سفليًا وعلويًا على اليسار |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | ينشئ نصًا سفليًا وعلويًا على اليسار |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | ينشئ نصًا سفليًا وعلويًا على اليمين |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | ينشئ نصًا سفليًا وعلويًا على اليمين |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | ينشئ نصًا علويًا |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | ينشئ نصًا علويًا |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | يأخذ الحد العلوي |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | يأخذ الحد العلوي |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | يضع هذا العنصر في صندوق حدود |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | يضع هذا العنصر في صندوق حدود |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو نص رياضي آخر. يمكن أن يكون الكائن المُحاط (على سبيل المثال) محاكيًا للمعامل مع أو بدون نقطة محاذاة، أو كنقطة كسر سطر، أو يُجمّع بحيث لا يُسمح بحدوث انقطاع سطر داخله. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | يضع في مصفوفة عمودية |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | يضبط شريطًا أسفل هذا العنصر |

### أمثلة

مثال:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```

### انظر أيضًا

* فئة [MathElementBase](../mathelementbase)
* واجهة [IMathNaryOperator](../imathnaryoperator)
* مساحة الاسم [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* مجموعة [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->