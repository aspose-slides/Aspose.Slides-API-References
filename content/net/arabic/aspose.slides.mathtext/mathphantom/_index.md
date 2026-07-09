---
title: MathPhantom
second_title: Aspose.Sildes لـ .NET مرجع API
description: يمثل كائن رياضي شبح ltmphantgt يؤثر على تخطيط العنصر الفرعي دون ضرورة عرضه. يمكن للـ phantom إخفاء تعبيره الأساسي مع الحفاظ على عرضه أو ارتفاعه أو عمقه لتنسيق الصيغ أو حجز مساحة. يتم التحكم في سلوك الرؤية والهندسة عبر خصائص مثل Show ZeroWid ZeroAsc ZeroDesc و Transp.
type: docs
weight: 8920
url: /ar/aspose.slides.mathtext/mathphantom/
---
## MathPhantom فئة

يمثل كائن رياضي شبح (&lt;m:phant&gt;) يؤثر على تخطيط العنصر الفرعي دون ضرورة عرضه. يمكن للـ phantom إخفاء التعبير الأساسي مع الحفاظ على عرضه أو ارتفاعه أو عمقه لتنسيق الصيغ أو حجز مساحة. يتم التحكم في سلوك الرؤية والهندسة عبر خصائص مثل Show, ZeroWid, ZeroAsc, ZeroDesc, و Transp.

```csharp
public sealed class MathPhantom : MathElementBase, IMathPhantom
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [MathPhantom](mathphantom)(IMathElement) | يُنشئ مثيلاً جديداً للفئة [`MathPhantom`](../mathphantom) باستخدام عنصر الرياضيات الأساسي المحدد. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathphantom/base) { get; } | المعامل الأساسي |
| [Show](../../aspose.slides.mathtext/mathphantom/show) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان العنصر الأساسي معروضًا. |
| [Transp](../../aspose.slides.mathtext/mathphantom/transp) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان الـ phantom شفافًا لقواعد التباعد القائمة على الفئات. |
| [ZeroAsc](../../aspose.slides.mathtext/mathphantom/zeroasc) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان الصعود (الارتفاع فوق خط القاعدة) للعنصر الأساسي ينبغي معاملته كصفر. |
| [ZeroDesc](../../aspose.slides.mathtext/mathphantom/zerodesc) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان النزول (العمق أسفل خط القاعدة) للعنصر الأساسي ينبغي معاملته كصفر. |
| [ZeroWidth](../../aspose.slides.mathtext/mathphantom/zerowidth) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان عرض العنصر الأساسي ينبغي معاملته كصفر. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | يعيّن علامة إعراب (حرف فوق هذا العنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل ويمرّر معاملًا إضافيًا محددًا |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل ويمرّر معاملًا إضافيًا محددًا |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | يُنشئ كسرًا بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | يُنشئ كسرًا بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | يُنشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | يُنشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | يُغلق عنصر رياضي بين الأقواس |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | يُغلق عنصر رياضي بين أحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | يأخذ دالة لمعامل باستخدام هذه المثيلة كاسم الدالة |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | يأخذ دالة لمعامل باستخدام هذه المثيلة كاسم الدالة |
| [GetChildren](../../aspose.slides.mathtext/mathphantom/getchildren)() | الحصول على العناصر الفرعية |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو حرف آخر |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | يأخذ التكامل بدون حدود |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | يأخذ التكامل |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | يجمع عنصرًا رياضيًا ويكوّن كتلة رياضية |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | يجمع نصًا رياضيًا ويكوّن كتلة رياضية |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | يُنشئ عاملًا N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | يُنشئ عاملًا N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | يضع شريطًا فوق هذا العنصر |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | يُحدِّد جذرًا رياضيًا من الدرجة المعطاة من المُعامل المحدد. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | يُحدِّد جذرًا رياضيًا من الدرجة المعطاة من المُعامل المحدد. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | يأخذ الحد الأدنى |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | يأخذ الحد الأدنى |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | يُنشئ نصًا تحتيًا |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | يُنشئ نصًا تحتيًا |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | يُنشئ نصًا تحتيًا وفوقيًا على اليسار |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | يُنشئ نصًا تحتيًا وفوقيًا على اليسار |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | يُنشئ نصًا تحتيًا وفوقيًا على اليمين |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | يُنشئ نصًا تحتيًا وفوقيًا على اليمين |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | يُنشئ نصًا فوقيًا |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | يُنشئ نصًا فوقيًا |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | يأخذ الحد العلوي |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | يأخذ الحد العلوي |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | يضع هذا العنصر في صندوق حدود |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | يضع هذا العنصر في صندوق حدود |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو نص رياضي آخر. يمكن للكائن المربع (على سبيل المثال) أن يعمل كمحاكي للمعامل مع أو بدون نقطة محاذاة، أو كنقطة كسر سطر، أو يُجمع بحيث لا يُسمح بوجود فواصل سطر داخله. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | يضع في مصفوفة رأسية |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | يضع شريطًا أسفل هذا العنصر |

### أمثلة

مثال:

```csharp
[C#]
IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
phantom.Show = false;          // إخفاء المحتوى
phantom.ZeroWidth = false;     // الحفاظ على العرض
```

### راجع أيضًا

* فئة [MathElementBase](../mathelementbase)
* واجهة [IMathPhantom](../imathphantom)
* نطاق [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->