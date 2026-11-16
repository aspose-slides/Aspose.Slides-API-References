---
title: MathArray
second_title: Aspose.Sildes لـ .NET مرجع API
description: يحدد مصفوفة عمودية من المعادلات أو أي كائنات رياضية
type: docs
weight: 8570
url: /ar/aspose.slides.mathtext/matharray/
---
## MathArray فئة

Specifies a vertical array of equations or any mathematical objects

```csharp
public sealed class MathArray : MathElementBase, IMathArray
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MathArray](matharray#constructor_1)(IEnumerable&lt;IMathElement&gt;) | ينشئ مصفوفة رياضية ويضع العناصر المحددة فيها |
| [MathArray](matharray#constructor)(IMathElement) | ينشئ مصفوفة رياضية ويضع العنصر المحدد فيها |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/matharray/arguments) { get; } | مجموعة عناصر المصفوفة |
| [BaseJustification](../../aspose.slides.mathtext/matharray/basejustification) { get; set; } | يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى الأسفل أو الأعلى أو المركز لكائن المصفوفة. القيمة الافتراضية: Center |
| [MaximumDistribution](../../aspose.slides.mathtext/matharray/maximumdistribution) { get; set; } | التوزيع الأقصى. عندما يكون true، تُفرَّغ المصفوفة إلى أقصى عرض للعنصر الحاوي (صفحة، عمود، خلية، إلخ). |
| [ObjectDistribution](../../aspose.slides.mathtext/matharray/objectdistribution) { get; set; } | توزيع الكائن. عندما يكون true، تُفرَّغ محتويات المصفوفة إلى أقصى عرض لكائن المصفوفة. |
| [RowSpacing](../../aspose.slides.mathtext/matharray/rowspacing) { get; set; } | المسافة بين صفوف المصفوفة. يُستخدم فقط عندما تكون RowSpacingRule مضبوطة على 3 Exactly، في هذه الحالة وحدة القياس هي النقاط أو Multiple حيث تكون وحدة القياس نصف سطر. القيمة الافتراضية: 0 |
| [RowSpacingRule](../../aspose.slides.mathtext/matharray/rowspacingrule) { get; set; } | نوع المسافة العمودية بين عناصر المصفوفة. القيمة الافتراضية: SingleLineGap |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | يضبط علامة التشكيل (حرف فوق هذا العنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | يتلقى الدالة المحددة باستخدام هذا العنصر كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | يتلقى الدالة المحددة باستخدام هذا العنصر كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | يتلقى الدالة المحددة باستخدام هذا العنصر كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | يتلقى الدالة المحددة باستخدام هذا العنصر كمعامل ومعامل إضافي محدد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | يتلقى الدالة المحددة باستخدام هذا العنصر كمعامل ومعامل إضافي محدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | يغلف عنصرًا رياضيًا بين قوسين |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | يغلف عنصرًا رياضيًا بأحرف محددة مثل القوس أو أحرف أخرى كإطار |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | يتلقى دالة لمعامل باستخدام هذا العنصر كاسم الدالة |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | يتلقى دالة لمعامل باستخدام هذا العنصر كاسم الدالة |
| [GetChildren](../../aspose.slides.mathtext/matharray/getchildren)() | يحصل على العناصر الفرعية |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | يتلقى التكامل بدون حدود |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | يتلقى التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | يتلقى التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | يتلقى التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | يتلقى التكامل |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | ينضم عنصرًا رياضيًا ويشكل كتلة رياضية |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | ينضم نصًا رياضيًا ويشكل كتلة رياضية |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | ينشئ مشغّلًا N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | ينشئ مشغّلًا N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | يضبط شريطًا أعلى هذا العنصر |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | يحدد الجذر الرياضي للدرجة المعطاة من المتغير المحدد. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | يحدد الجذر الرياضي للدرجة المعطاة من المتغير المحدد. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | يتلقى الحد الأدنى |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | يتلقى الحد الأدنى |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | ينشئ نصًا تحتيًا |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | ينشئ نصًا تحتيًا |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | ينشئ نصًا تحتيًا وعلويًا على الجانب الأيسر |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | ينشئ نصًا تحتيًا وعلويًا على الجانب الأيسر |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | ينشئ نصًا تحتيًا وعلويًا على الجانب الأيمن |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | ينشئ نصًا تحتيًا وعلويًا على الجانب الأيمن |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | ينشئ نصًا علويًا |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | ينشئ نصًا علويًا |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | يتلقى الحد الأعلى |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | يتلقى الحد الأعلى |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | يضع هذا العنصر في صندوق حدود |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | يضع هذا العنصر في صندوق حدود |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو نص رياضي آخر. يمكن أن يعمل الكائن المضمن (على سبيل المثال) كمحاكي عامل مع أو بدون نقطة محاذاة، أو كنقطة كسر سطر، أو يُجمَع بحيث لا يُسمح بكسور السطر داخله. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | يضع في مصفوفة عمودية |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | يضبط شريطًا أسفل هذا العنصر |

### أمثلة

مثال:

```csharp
[C#]
MathArray mathArray = new MathArray(new MathematicalText("item1"));
```

### انظر أيضًا

* فئة [MathElementBase](../mathelementbase)
* واجهة [IMathArray](../imatharray)
* مساحة الاسم [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->