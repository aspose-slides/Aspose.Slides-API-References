---
title: MathBox
second_title: Aspose.Sildes لمرجع API .NET
description: يحدد تغليف الصناديق المنطقية للعنصر الرياضي. على سبيل المثال، يمكن لكائن معبأ أن يعمل كمحاكي عامل مع أو بدون نقطة محاذاة، أو كنقطة فاصل سطر، أو أن يُجمّع بحيث لا يسمح بفواصل سطر داخله. على سبيل المثال، يجب صَنْدَة العامل لمنع فواصل السطر.
type: docs
weight: 8650
url: /ar/aspose.slides.mathtext/mathbox/
---
## فئة MathBox

يحدد الصناديق المنطقية (التعبئة) للعنصر الرياضي. على سبيل المثال، يمكن لكائن معبأ أن يعمل كمحاكي عامل مع أو بدون نقطة محاذاة، أو أن يكون نقطة فاصل سطر، أو أن يُجمّع بحيث لا يسمح بفواصل سطر داخله. على سبيل المثال، يجب صَنْدَة العامل "==" لمنع فواصل السطر.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | يُنشئ MathBox باستخدام العنصر المحدد كمعامل |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | عند أن تكون true، يعمل هذا المحاكي العامل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في المعادلات الأخرى يمكن محاذاتها معه. القيمة الافتراضية: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | المعامل الأساسي |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | عند أن تكون true، يعمل الصندوق كالعامل التفاضلي (مثال: 𝑑𝑥 في داخل التكامل)، ويتلقى التباعد الأفقي المناسب للمتغير الرياضي التفاضلي. القيمة الافتراضية: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | التوقف الصريح يحدّد ما إذا كان هناك فاصل سطر في بداية كائن Box، بحيث يُطوى السطر عند بداية كائن الصندوق. يحدّد عدد العامل في السطر السابق من النص الرياضي الذي سيُستخدم كنقطة محاذاة للسطر الحالي من النص الرياضي. القيم الممكنة: 1..255. القيمة الافتراضية: 0 (لا توقف صريح) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | عدم الفاصل هذه الخاصية تحدد خاصية "غير قابل للكسر" على صندوق الكائن. عند أن تكون true، لا يمكن حدوث فواصل سطر داخل الصندوق. قد يكون هذا مهمًا لمحاكيات العوامل التي تتألف من أكثر من عامل ثنائي. عندما لا يتم تحديد هذا العنصر، يمكن حدوث فواصل داخل الصندوق. القيمة الافتراضية: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | محاكي العامل. عند أن تكون true، يتصرف الصندوق ومحتوياته كعامل واحد ويرثان خصائص العامل. هذا يعني، على سبيل المثال، أن الحرف يمكن أن يعمل كنقطة لفاصل سطر ويمكن محاذاته إلى عوامل أخرى. غالبًا ما تُستخدم محاكيات العوامل عندما يجتمع أحد أو أكثر من الرموز لتشكيل عامل، مثل '=='. القيمة الافتراضية: false |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | يضبط علامة شدة (حرف فوق هذا العنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | يأخذ الدالة المحددة مستخدمًا هذا المثيل كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | يأخذ الدالة المحددة مستخدمًا هذا المثيل كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | يأخذ الدالة المحددة مستخدمًا هذا المثيل كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | يأخذ الدالة المحددة مستخدمًا هذا المثيل كمعامل ومعامل إضافي محدد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | يأخذ الدالة المحددة مستخدمًا هذا المثيل كمعامل ومعامل إضافي محدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | ينشئ كسرًا باستخدام هذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | ينشئ كسرًا باستخدام هذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | يحيط عنصرًا رياضيًا بأقواس |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | يحيط عنصرًا رياضيًا بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | يأخذ دالة ذات معامل مستخدمًا هذا المثيل كاسم الدالة |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | يأخذ دالة ذات معامل مستخدمًا هذا المثيل كاسم الدالة |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | يحصل على العناصر الفرعية |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | يأخذ التكامل بدون حدود |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | يأخذ التكامل |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | ينضم عنصرًا رياضيًا ويشكل كتلة رياضية |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | ينضم نصًا رياضيًا ويشكل كتلة رياضية |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | ينشئ عاملًا متعدد القيم |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | ينشئ عاملًا متعدد القيم |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | يضع شريطًا فوق هذا العنصر |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | يأخذ الحد السفلي |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | يأخذ الحد السفلي |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | ينشئ نصًا سفليًا |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | ينشئ نصًا سفليًا |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | ينشئ نصًا سفليًا وعليا على اليسار |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | ينشئ نصًا سفليًا وعليا على اليسار |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | ينشئ نصًا سفليًا وعليا على اليمين |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | ينشئ نصًا سفليًا وعليا على اليمين |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | ينشئ نصًا علويًا |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | ينشئ نصًا علويًا |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | يأخذ الحد العلوي |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | يأخذ الحد العلوي |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | يضع هذا العنصر في صندوق حد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | يضع هذا العنصر في صندوق حد |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو نص رياضي آخر. يمكن لكائن معبأ (على سبيل المثال) أن يعمل كمحاكي عامل مع أو بدون نقطة محاذاة، أو أن يكون نقطة فاصل سطر، أو أن يُجمّع بحيث لا يسمح بفواصل سطر داخله. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | يضع في مصفوفة عمودية |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | يضع شريطًا أسفل هذا العنصر |

### أمثلة

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### انظر أيضًا

* الفئة [MathElementBase](../mathelementbase)
* الواجهة [IMathBox](../imathbox)
* المجال [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->