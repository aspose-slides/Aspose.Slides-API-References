---
title: MathBox
second_title: Aspose.Sildes لـ .NET - مرجع API
description: يحدد التعبئة المنطقية (الصندوقية) للعنصر الرياضي. على سبيل المثال، يمكن لكائن محزون أن يعمل كمحاكي عامل مع أو بدون نقطة محاذاة، أو يعمل كنقطة فاصل سطر، أو يُجمع بحيث لا يسمح بفواصل سطر داخله. على سبيل المثال، يجب أن يُحَصن العامل لمنع فواصل السطر.
type: docs
weight: 8630
url: /ar/aspose.slides.mathtext/mathbox/
---
## MathBox فئة

يحدد الصندوق المنطقي (التعبئة) للعنصر الرياضي. على سبيل المثال، يمكن لكائن محزون أن يعمل كمحاكي عامل مع أو بدون نقطة محاذاة، أو يعمل كنقطة فاصل سطر، أو يُجمع بحيث لا يسمح بفواصل سطر داخلية. على سبيل المثال، يجب أن يُحَصن العامل "==" لمنع فواصل السطر.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## البنّاءات

| الاسم | الوصف |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | ينشئ MathBox باستخدام العنصر المحدد كمعامل |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | عند أن تكون true، يعمل هذا المحاكي للعامل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذاتها معه. الافتراضي: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | الوسيط الأساسي |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | مشتق عند أن تكون true، يعمل الصندوق كمشتق (مثل 𝑑𝑥 في تكامل) ويتلقى التباعد الأفقي المناسب للمشتق الرياضي. الافتراضي: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | كسر صريح يحدد ما إذا كان هناك فاصل سطر في بداية كائن Box، بحيث يلتف السطر عند بداية كائن الصندوق. يحدد عدد العامل في السطر السابق للنص الرياضي الذي سيُستخدم كنقطة محاذاة للسطر الحالي من النص الرياضي. القيم الممكنة: 1..255 الافتراضي: 0 (لا كسر صريح) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | بدون كسر تحدد هذه الخاصية خاصية "غير قابل للكسر" على صندوق الكائن. عند أن تكون true، لا يمكن حدوث فواصل سطر داخل الصندوق. قد يكون هذا مهمًا لمحاكيات العامل التي تتكون من أكثر من عامل ثنائي. عندما لا يتم تحديد هذا العنصر، يمكن حدوث فواصل داخل الصندوق. الافتراضي: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | محاكي عامل. عند أن تكون true، يتصرف الصندوق ومحتوياته كعامل واحد ويرث خصائص العامل. هذا يعني، على سبيل المثال، أن الحرف يمكن أن يعمل كنقطة لفاصل السطر ويمكن محاذاته إلى عوامل أخرى. تُستخدم محاكيات العامل غالبًا عندما يتحد حرف أو أكثر لتكوين عامل، مثل '=='. القيمة الافتراضية: false |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | يضبط علامة إكسنت (حرف فوق هذا العنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | تأخذ الدالة المحددة باستخدام هذا المثيل كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | تأخذ الدالة المحددة باستخدام هذا المثيل كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | تأخذ الدالة المحددة باستخدام هذا المثيل كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | تأخذ الدالة المحددة باستخدام هذا المثيل كمعامل والوسيط الإضافي المحدد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | تأخذ الدالة المحددة باستخدام هذا المثيل كمعامل والوسيط الإضافي المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | ينشئ كسرًا بالعدد العلوي هذا والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | ينشئ كسرًا بالعدد العلوي هذا والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بالعدد العلوي هذا والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بالعدد العلوي هذا والمقام المحدد |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | يحيط عنصر رياضي بأقواس |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | يحيط عنصر رياضي بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | تأخذ دالة لوسيط باستخدام هذا المثيل كاسم الدالة |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | تأخذ دالة لوسيط باستخدام هذا المثيل كاسم الدالة |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | يحصل على العناصر الفرعية |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | يأخذ التكامل دون حدود |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | يأخذ التكامل |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | يجمع عنصرًا رياضيًا ويكوّن كتلة رياضية |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | يجمع عنصرًا رياضيًا ويكوّن كتلة رياضية |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | ينشئ عاملًا متعددًا |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | ينشئ عاملًا متعددًا |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | يضبط شريطًا فوق هذا العنصر |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | حدّد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | حدّد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | يأخذ الحد السفلي |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | يأخذ الحد السفلي |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | ينشئ نصًا فرعيًا |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | ينشئ نصًا فرعيًا |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | ينشئ نصًا فرعيًا وعليًا على اليسار |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | ينشئ نصًا فرعيًا وعليًا على اليسار |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | ينشئ نصًا فرعيًا وعليًا على اليمين |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | ينشئ نصًا فرعيًا وعليًا على اليمين |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | ينشئ نصًا عاليًا |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | ينشئ نصًا عاليًا |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | يأخذ الحد العلوي |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | يأخذ الحد العلوي |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | يضع هذا العنصر في صندوق حد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | يضع هذا العنصر في صندوق حد |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو مثال آخر من النص الرياضي. يمكن لكائن محزون (على سبيل المثال) أن يعمل كمحاكي عامل مع أو بدون نقطة محاذاة، أو كنقطة فاصل سطر، أو يُجمع بحيث لا يسمح بفواصل سطر داخلية |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | يضع في مصفوفة عمودية |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | يضبط شريطًا أسفل هذا العنصر |

### أمثلة

مثال:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### انظر أيضًا

* الفئة [MathElementBase](../mathelementbase)
* الواجهة [IMathBox](../imathbox)
* النطاق [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->