---
title: MathDelimiter
second_title: Aspose.Sildes لـ .NET مرجع API
description: يحدد كائن الفاصل المكوّن من أحرف الفتح والإغلاق مثل الأقواس والأقواس المعقوفة والأقواس المربعة والشرطات الرأسية، بالإضافة إلى عنصر أو أكثر من العناصر الرياضية داخلها مفصولًا بحرف محدد. أمثلة 2 2x7C2
type: docs
weight: 8650
url: /ar/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter فئة

يحدد كائن الفاصل، المكوّن من أحرف الفتح والإغلاق (مثل الأقواس، الأقواس المعقوفة، الأقواس المربعة، والشرطات الرأسية)، وواحد أو أكثر من العناصر الرياضية داخله، مفصولة بحرف محدد. أمثلة: (𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## البنائين

| الاسم | الوصف |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | يقوم بتهيئة MathDelimiter باستخدام العنصر المحدد كحجة أساسية واحدة |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | واحد أو أكثر من العناصر الرياضية مفصولة بأحرف الفاصل |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | Delimiter Beginning Character يحدد حرف الفاصل الافتتاحي. الفواصل الرياضية هي أحرف محيطة مثل الأقواس والأقواس المربعة والأقواس المعقوفة. القيمة الافتراضية: '(' |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | يحدد شكل الفواصل في كائن الفاصل. عندما تكون MathDelimiterShape.Centered، تكون الفواصل مركزية حول محور النص الرياضي ولا يزال يمكن تعديلها لتناسب كامل ارتفاع محتوياتها. عندما تكون MathDelimiterShape.Match، يتم تعديل ارتفاعها وشكلها لتطابق محتوياتها تماماً |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | Delimiter Ending Character يحدد حرف الفاصل الختامي. الفواصل الرياضية هي أحرف محيطة مثل الأقواس والأقواس المربعة والأقواس المعقوفة. القيمة الافتراضية: ')' |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | يحدد نمو BeginningCharacter و SeparatorCharacter و EndingCharacter. عندما يكون true، ينمو الفاصل عمودياً ليتطابق مع ارتفاع المعامل. القيمة الافتراضية هي true |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | Delimiter Separator Character يحدد الحرف الذي يفصل الحجج في كائن الفاصل. القيمة الافتراضية: '&#x7C;' |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | يضبط علامة تشكيل (حرف فوق هذا العنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | يأخذ الدالة المحددة باستخدام هذه المثيلة كحجة |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | يأخذ الدالة المحددة باستخدام هذه المثيلة كحجة |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | يأخذ الدالة المحددة باستخدام هذه المثيلة كحجة |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | يأخذ الدالة المحددة باستخدام هذه المثيلة كحجة والحجة الإضافية المحددة |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | يأخذ الدالة المحددة باستخدام هذه المثيلة كحجة والحجة الإضافية المحددة |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | يفصل الحجج باستخدام حرف الفاصل المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | يضع عنصرًا رياضيًا بين أقواس |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | يضع عنصرًا رياضيًا بين الأحرف المحددة مثل الأقواس أو أحرف أخرى كإطار |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | يأخذ دالة لحجة باستخدام هذه المثيلة كاسم الدالة |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | يأخذ دالة لحجة باستخدام هذه المثيلة كاسم الدالة |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | يحصل على العناصر الفرعية |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | يأخذ التكامل بدون حدود |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | يأخذ التكامل |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | يجمع عنصرًا رياضيًا ويشكل كتلة رياضية |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | يجمع نصًا رياضيًا ويشكل كتلة رياضية |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | ينشئ عاملًا من N |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | ينشئ عاملًا من N |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | يضيف شريطًا أعلى هذا العنصر |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | يحدد الجذر الرياضي للدرجة المعطاة من الحجة المحددة |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | يحدد الجذر الرياضي للدرجة المعطاة من الحجة المحددة |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | يأخذ الحد الأدنى |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | يأخذ الحد الأدنى |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | ينشئ مؤشرًا سفليًا |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | ينشئ مؤشرًا سفليًا |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | ينشئ مؤشرًا سفليًا ومؤشرًا علويًا على اليسار |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | ينشئ مؤشرًا سفليًا ومؤشرًا علويًا على اليسار |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | ينشئ مؤشرًا سفليًا ومؤشرًا علويًا على اليمين |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | ينشئ مؤشرًا سفليًا ومؤشرًا علويًا على اليمين |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | ينشئ مؤشرًا علويًا |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | ينشئ مؤشرًا علويًا |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | يأخذ الحد الأعلى |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | يأخذ الحد الأعلى |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | يضع هذا العنصر في صندوق حدود |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | يضع هذا العنصر في صندوق حدود |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | يضع هذا العنصر في صندوق غير بصري (تجميع منطقي) يُستعمل لتجميع مكونات معادلة أو نص رياضي آخر. يمكن للكيان المربع (على سبيل المثال) أن يعمل كمحاكي عامل مع أو بدون نقطة محاذاة، أو كنقطة كسر سطر، أو يتم تجميعه بحيث لا يسمح بكسور سطر داخله |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | يضع في مصفوفة رأسية |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | يضيف شريطًا أسفل هذا العنصر |

### أمثلة

مثال:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### انظر أيضًا

* فئة [MathElementBase](../mathelementbase)
* واجهة [IMathDelimiter](../imathdelimiter)
* نطاق [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->