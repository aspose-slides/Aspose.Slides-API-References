---
title: MathBlock
second_title: Aspose.Sildes لـ .NET مرجع API
description: يحدد مثيلًا من النص الرياضي الموجود داخل MathParagraph ويبدأ في سطر منفصل. جميع المناطق الرياضية بما في ذلك المعادلات والتعبيرات ومصفوفات المعادلات أو التعبيرات والصيغ تمثَّل بواسطة كتلة رياضية.
type: docs
weight: 8590
url: /ar/aspose.slides.mathtext/mathblock/
---
## MathBlock فئة

يحدد مثيلًا من النص الرياضي الموجود داخل MathParagraph ويبدأ في سطر منفصل. جميع المناطق الرياضية، بما في ذلك المعادلات، التعبيرات، مصفوفات المعادلات أو التعبيرات، والصيغ، تمثَّل بواسطة كتلة رياضية.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## المُنشئات

| Name | Description |
| --- | --- |
| [MathBlock](mathblock#constructor)() | ينشئ مثيلًا جديدًا من فئة MathBlock. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | ينشئ كتلة رياضية جديدة ويضع العناصر المحددة فيها |
| [MathBlock](mathblock#constructor_1)(IMathElement) | ينشئ كتلة رياضية جديدة ويضع العنصر المحدد فيها |

## الخصائص

| Name | Description |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | يحصل على عدد عناصر الرياضة الفرعية الموجودة فعليًا في المجموعة. قراءة فقط Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | يرجع false لأن مجموعة العناصر الفرعية يمكن تعديلها. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | يحصل على أو يعيّن IMathElement في الفهرس المحدد. |

## الأساليب

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | يضبط علامة إكسنت (حرف أعلى هذا العنصر) |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | يضيف عنصرًا رياضيًا إلى نهاية المجموعة. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | يأخذ الدالة المحددة باستخدام هذا المثيل كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | يأخذ الدالة المحددة باستخدام هذا المثيل كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | يأخذ الدالة المحددة باستخدام هذا المثيل كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | يأخذ الدالة المحددة باستخدام هذا المثيل كمعامل ومعامل إضافي محدد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | يأخذ الدالة المحددة باستخدام هذا المثيل كمعامل ومعامل إضافي محدد |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | يزيل جميع العناصر من المجموعة. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | يحدد ما إذا كانت المجموعة تحتوي على قيمة محددة. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | ينسخ إلى المصفوفة المحددة. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | يفصل العناصر الفرعية باستخدام حرف فاصل (بدون الأقواس) |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | يحيط عنصر رياضي بأقواس |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | يحيط العناصر الفرعية لهذه الكتلة بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | يحيط العناصر الفرعية لهذه الكتلة بأحرف محددة مثل الأقواس أو غيرها كإطار ويقسمها بحرف فاصل |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | يأخذ دالة ذات معامل باستخدام هذا المثيل كاسم الدالة |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | يأخذ دالة ذات معامل باستخدام هذا المثيل كاسم الدالة |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | يحصل على العناصر الفرعية |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | يحدد فهرس عنصر رياضي محدد في المجموعة. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | يدرج MathElement في المجموعة عند الفهرس المحدد. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | يأخذ التكامل دون حدود |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | يأخذ التكامل |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | ينضم عنصرًا رياضيًا إلى هذه الكتلة الرياضية |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | ينضم نصًا رياضيًا إلى هذه الكتلة الرياضية |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | ينضم كتلة رياضية أخرى إلى هذه |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | ينشئ عاملًا N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | ينشئ عاملًا N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | يضع شريطًا فوق هذا العنصر |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | يزيل أول ظهور لكائن محدد من المجموعة. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | يزيل العنصر عند الفهرس المحدد في المجموعة. |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو أي نص رياضي آخر. يمكن أن يعمل الكائن المضمن (على سبيل المثال) كمحاكي لمعامل مع أو بدون نقطة محاذاة، أو كنقطة فاصل أسطر، أو يُجمع بحيث لا يسمح بوجود فواصل أسطر داخله. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | يضع العناصر الفرعية في مصفوفة رأسية |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | يضع شريطًا أسفل هذا العنصر |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | يحفظ محتوى هذا [`MathBlock`](../mathblock) كـ MathML |

### أمثلة

مثال:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### انظر أيضًا

* فئة [MathElementBase](../mathelementbase)
* واجهة [IMathBlock](../imathblock)
* مساحة اسم [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->