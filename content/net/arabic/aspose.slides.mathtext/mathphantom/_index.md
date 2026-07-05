---
title: MathPhantom
second_title: مرجع API الخاص بـ Aspose.Sildes لـ .NET
description: يمثل كائنًا رياضيًا وهميًا ltmphantgt يؤثر على تنسيق العنصر الفرعي دون الحاجة إلى عرضه. يمكن للكيان الوهمي إخفاء التعبير الأساسي مع الحفاظ على عرضه أو ارتفاعه أو عمقه لتنسيق الصيغ أو حجز مساحة. يتم التحكم في سلوك الظهور والهندسة عبر خصائص مثل Show وZeroWid وZeroAsc وZeroDesc وTransp.
type: docs
weight: 8920
url: /ar/aspose.slides.mathtext/mathphantom/
---
## MathPhantom فئة

يمثل كائنًا رياضيًا وهميًا (<m:phant>) يؤثر على تخطيط العنصر الفرعي دون الحاجة إلى عرضه. يمكن للكيان الوهمي إخفاء التعبير الأساسي مع الحفاظ على عرضه أو ارتفاعه أو عُمقه لتنسيق الصيغ أو حجز مساحة. يتم التحكم في سلوك الظهور والهندسة عبر خصائص مثل Show وZeroWid وZeroAsc وZeroDesc وTransp.

```csharp
public sealed class MathPhantom : MathElementBase, IMathPhantom
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [MathPhantom](mathphantom)(IMathElement) | ينشئ مثيلًا جديدًا من الفئة [`MathPhantom`](../mathphantom) باستخدام عنصر الرياضيات الأساسي المحدد. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathphantom/base) { get; } | وسيط الأساس |
| [Show](../../aspose.slides.mathtext/mathphantom/show) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان العنصر الأساسي معروضًا. |
| [Transp](../../aspose.slides.mathtext/mathphantom/transp) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الوهم شفافًا لقواعد التباعد المعتمدة على الفئة. |
| [ZeroAsc](../../aspose.slides.mathtext/mathphantom/zeroasc) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان ارتفاع الصعود (الارتفاع فوق الخط الأساسي) للعنصر الأساسي يجب أن يُعامل كصفر. |
| [ZeroDesc](../../aspose.slides.mathtext/mathphantom/zerodesc) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هبوط (العمق أسفل الخط الأساسي) للعنصر الأساسي يجب أن يُعامل كصفر. |
| [ZeroWidth](../../aspose.slides.mathtext/mathphantom/zerowidth) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان عرض العنصر الأساسي يجب أن يُعامل كصفر. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | يضبط علامة التشكيل (حرف فوق هذا العنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | يأخذ الدالة المحددة باستخدام هذا المثيل كوسيطة. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | يأخذ الدالة المحددة باستخدام هذا المثيل كوسيطة. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | يأخذ الدالة المحددة باستخدام هذا المثيل كوسيطة. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | يأخذ الدالة المحددة باستخدام هذا المثيل كوسيطة والوسيطة الإضافية المحددة. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | يأخذ الدالة المحددة باستخدام هذا المثيل كوسيطة والوسيطة الإضافية المحددة. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | ينشئ كسرًا بهذا البسط والمقام المحدد. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | ينشئ كسرًا بهذا البسط والمقام المحدد. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | يغلف عنصرًا رياضيًا بأقواس. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | يغلف عنصرًا رياضيًا بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | يأخذ دالة لوسيط باستخدام هذا المثيل كاسم الدالة. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | يأخذ دالة لوسيط باستخدام هذا المثيل كاسم الدالة. |
| [GetChildren](../../aspose.slides.mathtext/mathphantom/getchildren)() | يحصل على العناصر الفرعية. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | يضع هذا العنصر في مجموعة باستخدام قوس تجعيد سفلي. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس السفلي أو غيره. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | يأخذ التكامل بدون حدود. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | يأخذ التكامل. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | يأخذ التكامل. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | يأخذ التكامل. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | يأخذ التكامل. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | يجمع عنصرًا رياضيًا ويكوّن كتلة رياضية. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | يجمع نصًا رياضيًا ويكوّن كتلة رياضية. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | ينشئ عامل N-ary. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | ينشئ عامل N-ary. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | يضبط شريطًا أعلى هذا العنصر. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | يأخذ الحد الأدنى. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | يأخذ الحد الأدنى. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | ينشئ نصًا سفليًا. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | ينشئ نصًا سفليًا. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | ينشئ نصًا سفليًا وعلياً على اليسار. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | ينشئ نصًا سفليًا وعلياً على اليسار. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | ينشئ نصًا سفليًا وعلياً على اليمين. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | ينشئ نصًا سفليًا وعلياً على اليمين. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | ينشئ نصًا علويًا. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | ينشئ نصًا علويًا. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | يأخذ الحد الأعلى. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | يأخذ الحد الأعلى. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | يضع هذا العنصر في صندوق حدود. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | يضع هذا العنصر في صندوق حدود. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو نص رياضي آخر. يمكن أن يكون الكائن المربّع مثالًا على محاكٍ للعامل مع أو بدون نقطة محاذاة، أو كنقطة كسر سطر، أو يُجمع بحيث لا يسمح بفواصل سطر داخله. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | يضعه في مصفوفة رأسية. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | يضبط شريطًا أسفل هذا العنصر. |

### أمثلة

مثال:

```csharp
[C#]
IMMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
phantom.Show = false;          // إخفاء المحتوى
phantom.ZeroWidth = false;     // الإبقاء على العرض
```

### انظر أيضًا

* فئة [MathElementBase](../mathelementbase)
* واجهة [IMathPhantom](../imathphantom)
* مساحة الاسم [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->