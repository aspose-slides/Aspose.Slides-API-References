---
title: MathBox
second_title: Aspose.Sildes لـ .NET مرجع API
description: يحدد التغليف المنطقي (التعبئة) للعنصر الرياضي. على سبيل المثال، يمكن أن يُستخدم كائن مُغلف كمحاكي عامل مع أو بدون نقطة محاذاة، أو كنقطة فاصل سطر، أو يُجمع بحيث لا يُسمح بوجود فواصل سطر داخلية. على سبيل المثال، يجب تغليف المشغل لمنع فواصل السطر.
type: docs
weight: 8630
url: /ar/aspose.slides.mathtext/mathbox/
---
## MathBox فئة

يحدد التغليف المنطقي (التعبئة) للعنصر الرياضي. على سبيل المثال، يمكن أن يُستخدم كائن مُغلف كمحاكي عامل مع أو بدون نقطة محاذاة، أو كنقطة فاصل سطر، أو يُجمع بحيث لا يسمح بوجود فواصل سطر داخلية. على سبيل المثال، يجب تغليف عامل "==" لمنع فواصل السطر.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | يهيئ MathBox بالعنصر المحدد كمعامل |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | عند true، يعمل هذا المحاكي كعامل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في المعادلات الأخرى يمكن محاذاتها معه. القيمة الافتراضية: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | المعامل الأساسي |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | التفاضل. عندما تكون true، يعمل الصندوق كتفاضل (مثل 𝑑𝑥 في تكامل)، ويتلقى التباعد الأفقي المناسب للتفاضل الرياضي. القيمة الافتراضية: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | الإغلاق الصريح يحدد ما إذا كان هناك فاصل سطر في بداية عنصر Box، بحيث يلتف السطر عند بداية الصندوق. يحدد عدد العامل في السطر السابق من النص الرياضي الذي يجب استخدامه كنقطة محاذاة للسطر الحالي. القيم الممكنة: 1..255. القيمة الافتراضية: 0 (لا فاصل صريح) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | عدم الانقطاع. هذه الخاصية تحدد خاصية "unbreakable" على صندوق الكائن. عندما تكون true، لا يمكن حدوث فواصل سطر داخل الصندوق. قد يكون ذلك مهمًا لمحاكيات العامل التي تتكون من أكثر من عامل ثنائي. عندما لا يتم تحديد هذا العنصر، يمكن حدوث فواصل داخل الصندوق. القيمة الافتراضية: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | محاكي العامل. عندما تكون true، يتصرف الصندوق ومحتوياته كعامل واحد ويرثون خصائص العامل. هذا يعني، على سبيل المثال، أن الحرف يمكن أن يكون نقطة لفاصل سطر ويمكن محاذاته إلى عوامل أخرى. غالبًا ما تُستخدم محاكيات العامل عندما يتحد حرف أو أكثر لتكوين عامل، مثل '=='. القيمة الافتراضية: false |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | يضع علامة تشكيل (حرفًا فوق هذا العنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | يأخذ الدالة المحددة باستخدام هذا المثيل كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | يأخذ الدالة المحددة باستخدام هذا المثيل كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | يأخذ الدالة المحددة باستخدام هذا المثيل كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | يأخذ الدالة المحددة باستخدام هذا المثيل كمعامل ومعامل إضافي محدد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | يأخذ الدالة المحددة باستخدام هذا المثيل كمعامل ومعامل إضافي محدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | ينشئ كسرًا بهذا البسط والاسم المقسوم المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | ينشئ كسرًا بهذا البسط والاسم المقسوم المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والاسم المقسوم المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والاسم المقسوم المحدد |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | يحيط عنصر رياضي بأقواس |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | يحيط عنصر ريابي بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | يأخذ دالة ذات معامل باستخدام هذا المثيل كاسم الدالة |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | يأخذ دالة ذات معامل باستخدام هذا المثيل كاسم الدالة |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | يجلب عناصر الأطفال |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | يأخذ التكامل بدون حدود |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | يأخذ التكامل |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | يجمع عنصرًا رياضيًا ويكوّن كتلة رياضية |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | يجمع نصًا رياضيًا ويكوّن كتلة رياضية |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | ينشئ عامل N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | ينشئ عامل N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | يضع شريطًا أعلى هذا العنصر |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | يأخذ الحد السفلي |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | يأخذ الحد السفلي |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | ينشئ موضعًا سفليًا |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | ينشئ موضعًا سفليًا |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | ينشئ موضعًا سفليًا وعلويًا على اليسار |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | ينشئ موضعًا سفليًا وعلويًا على اليسار |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | ينشئ موضعًا سفليًا وعلويًا على اليمين |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | ينشئ موضعًا سفليًا وعلويًا على اليمين |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | ينشئ موضعًا علويًا |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | ينشئ موضعًا علويًا |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | يأخذ الحد العلوي |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | يأخذ الحد العلوي |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | يضع هذا العنصر في صندوق حدود |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | يضع هذا العنصر في صندوق حدود |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو نص رياضي آخر. يمكن لكائن مُغلف (على سبيل المثال) أن يُستخدم كمحاكي عامل مع أو بدون نقطة محاذاة، أو كنقطة فاصل سطر، أو يُجمع بحيث لا يسمح بفواصل سطر داخلية. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | يضع في مصفوفة عمودية |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | يضع شريطًا أسفل هذا العنصر |

### أمثلة

مثال:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### انظر أيضًا

* فئة [MathElementBase](../mathelementbase)
* واجهة [IMathBox](../imathbox)
* مساحة الاسم [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->