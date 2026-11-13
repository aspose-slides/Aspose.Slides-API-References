---
title: MathBlock
second_title: مرجع API Aspose.Sildes لـ .NET
description: يحدد مثيًرا للنص الرياضي الموجود داخل MathParagraph ويبدأ في سطره الخاص. جميع مناطق الرياضيات بما في ذلك المعادلات، التعبيرات، مصفوفات المعادلات أو التعبيرات، والصيغ يتم تمثيلها بواسطة كتلة رياضية.
type: docs
weight: 8610
url: /ar/aspose.slides.mathtext/mathblock/
---
## MathBlock فئة

يحدد مثيًرا للنص الرياضي الموجود داخل MathParagraph ويبدأ في سطره الخاص. جميع مناطق الرياضيات، بما في ذلك المعادلات، والتعبيرات، ومصفوفات المعادلات أو التعابير، والصيغ يتم تمثيلها بواسطة math block.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MathBlock](mathblock#constructor)() | يُنشئ مثيًرا جديدا لفئة MathBlock. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | ينشئ كتلة رياضية جديدة ويضع العناصر المحددة فيها |
| [MathBlock](mathblock#constructor_1)(IMathElement) | ينشئ كتلة رياضية جديدة ويضع العنصر المحدد فيها |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | يُرجِع عدد عناصر الرياضيات الفرعية الموجودة فعلا في المجموعة. قراءة فقط Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | يُرجِع false لأن مجموعة العناصر الفرعية يمكن تعديلها. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | يُرجِع أو يعيّن IMathElement في الفهرس المحدد. |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | يضبط علامة تشكيل (حرف فوق هذا العنصر) |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | يضيف عنصر رياضي إلى نهاية المجموعة. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | يأخذ الدالة المحددة باستخدام هذا المثيل كوسيط |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | يأخذ الدالة المحددة باستخدام هذا المثيل كوسيط |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | يأخذ الدالة المحددة باستخدام هذا المثيل كوسيط |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | يأخذ الدالة المحددة باستخدام هذا المثيل كوسيط والوسيط الإضافي المحدد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | يأخذ الدالة المحددة باستخدام هذا المثيل كوسيط والوسيط الإضافي المحدد |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | يزيل جميع العناصر من المجموعة. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | يحدد ما إذا كانت المجموعة تحتوي على قيمة معينة. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | ينسخ إلى المصفوفة المحددة. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | يفصل العناصر الفرعية باستخدام حرف الفاصل (بدون الأقواس) |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | يحيط عنصر رياضي بالأقواس |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | يحيط العناصر الفرعية لهذه الكتلة بالحروف المحددة مثل الأقواس أو أحرف أخرى كإطار |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | يحيط العناصر الفرعية لهذه الكتلة بالحروف المحددة مثل الأقواس أو أخرى كإطار ويفصلها بحرف فاصل |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | يأخذ دالة لوسيط باستخدام هذا المثيل كاسم الدالة |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | يأخذ دالة لوسيط باستخدام هذا المثيل كاسم الدالة |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | يحصل على العناصر الفرعية |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | يحدد فهرس عنصر رياضي معين في المجموعة. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | يدخل MathElement في المجموعة عند الفهرس المحدد. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | يأخذ التكامل بدون حدود |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | يأخذ التكامل |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | ينضم عنصر رياضي إلى هذا الكتلة الرياضية |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | ينضم نص رياضي إلى هذه الكتلة الرياضية |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | ينضم كتلة رياضية أخرى إلى هذه |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | ينشئ عامل N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | ينشئ عامل N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | يضبط شريطًا أعلى هذا العنصر |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | يزيل أول ظهور لكائن محدد من المجموعة |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | يزيل العنصر عند الفهرس المحدد في المجموعة |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | يأخذ الحد الأدنى |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | يأخذ الحد الأدنى |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | ينشئ نصًا سفليًا |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | ينشئ نصًا سفليًا |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | ينشئ نصًا سفليًا وعليا على اليسار |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | ينشئ نصًا سفليًا وعليا على اليسار |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | ينشئ نصًا سفليًا وعليا على اليمين |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | ينشئ نصًا سفليًا وعليا على اليمين |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | ينشئ نصًا علويًا |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | ينشئ نصًا علويًا |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | يأخذ الحد الأعلى |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | يأخذ الحد الأعلى |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | يضع هذا العنصر في صندوق حدود |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | يضع هذا العنصر في صندوق حدود |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو نسخة أخرى من النص الرياضي. يمكن للعنصر المربع (مثلاً) أن يعمل كمحاكي عامل مع أو بدون نقطة محاذاة، أو كنقطة كسر سطر، أو أن يُجمع بحيث لا يُسمح بكسر السطر داخله |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | يضع العناصر الفرعية في مصفوفة عمودية |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | يضبط شريطًا أسفل هذا العنصر |
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
* مساحة الاسم [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->