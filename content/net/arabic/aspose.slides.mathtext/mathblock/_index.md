---
title: MathBlock
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يحدد مثيلًا من النص الرياضي الموجود داخل MathParagraph ويبدأ في سطر مستقل. جميع مناطق الرياضيات بما في ذلك المعادلات والتعبيرات ومصفوفات المعادلات أو التعبيرات والصيغ يتم تمثيلها بـ MathBlock.
type: docs
weight: 8590
url: /ar/aspose.slides.mathtext/mathblock/
---
## فئة MathBlock

يحدد مثيلًا من النص الرياضي الموجود داخل MathParagraph ويبدأ في سطر مستقل. جميع مناطق الرياضيات، بما في ذلك المعادلات، والتعبيرات، ومصفوفات المعادلات أو التعبيرات، والصيغ، يتم تمثيلها بـ MathBlock.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```


## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MathBlock](mathblock#constructor)() | يهيئ مثيلًا جديدًا من فئة MathBlock. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | ينشئ كتلة رياضية جديدة ويضع العناصر المحددة فيها. |
| [MathBlock](mathblock#constructor_1)(IMathElement) | ينشئ كتلة رياضية جديدة ويضع العنصر المحدد فيها. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | يحصل على عدد عناصر الرياضيات الفرعية الموجودة فعليًا في المجموعة. قراءة فقط Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | يُعيد false لأن مجموعة العناصر الفرعية يمكن تعديلها. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | يحصل على أو يضبط IMathElement عند الفهرس المحدد. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | يحدد علامة شدة (حرف فوق هذا العنصر). |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | يضيف عنصر رياضي إلى نهاية المجموعة. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | يستخدم الدالة المحددة مع هذا المثيل كوسيلة. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | يستخدم الدالة المحددة مع هذا المثيل كوسيلة. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | يستخدم الدالة المحددة مع هذا المثيل كوسيلة. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | يستخدم الدالة المحددة مع هذا المثيل كوسيلة ويضيف الوسيط الإضافي المحدد. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | يستخدم الدالة المحددة مع هذا المثيل كوسيلة ويضيف الوسيط الإضافي المحدد. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | يزيل جميع العناصر من المجموعة. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | يحدد ما إذا كانت المجموعة تحتوي على قيمة معينة. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | ينسخ إلى المصفوفة المحددة. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | يحدد عناصر الطفل بفاصل حرف (بدون الأقواس). |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | ينشئ كسرًا بالمقام المحدد لهذا البسط. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | ينشئ كسرًا بالمقام المحدد لهذا البسط. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | يضع العنصر الرياضي بين قوسين. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | يحيط عناصر الطفل في هذا الكتلة بأحرف محددة مثل القوسين أو أحرف أخرى كإطار. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | يحيط عناصر الطفل في هذا الكتلة بأحرف محددة مثل القوسين أو أحرف أخرى كإطار ويحد بفاصل حرف. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | يستخدم هذا المثيل كاسم الدالة لإجراء دالة ذات وسيط. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | يستخدم هذا المثيل كاسم الدالة لإجراء دالة ذات وسيط. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | يحصل على عناصر الأطفال. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | يحدد فهرس عنصر رياضي معين في المجموعة. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | يدرج MathElement في المجموعة عند الفهرس المحدد. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | يأخذ التكامل دون حدود. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | يأخذ التكامل. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | يأخذ التكامل. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | يأخذ التكامل. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | يأخذ التكامل. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | يجمع عنصرًا رياضيًا مع هذا الكتلة الرياضية. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | يجمع نصًا رياضيًا مع هذا الكتلة الرياضية. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | يجمع كتلة رياضية أخرى مع هذه. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | ينشئ عامل N-ary. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | ينشئ عامل N-ary. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | يضيف شريطًا أعلى هذا العنصر. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | يحدد الجذر الرياضي للدرجة المحددة من الوسيط المحدد. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | يحدد الجذر الرياضي للدرجة المحددة من الوسيط المحدد. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | يزيل أول ظهور لكائن معين من المجموعة. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | يزيل العنصر عند الفهرس المحدد في المجموعة. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | يأخذ الحد الأدنى. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | يأخذ الحد الأدنى. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | ينشئ نصًا سفليًا. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | ينشئ نصًا سفليًا. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | ينشئ نصًا سفليًا وعليا على اليسار. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | ينشئ نصًا سفليًا وعليا على اليسار. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | ينشئ نصًا سفليًا وعليا على اليمين. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | ينشئ نصًا سفليًا وعليا على اليمين. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | ينشئ نصًا علويًا. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | ينشئ نصًا علويًا. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | يأخذ الحد الأعلى. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | يأخذ الحد الأعلى. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | يضع هذا العنصر في صندوق حدود. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | يضع هذا العنصر في صندوق حدود. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو نص رياضي آخر. يمكن للصندوق المربع أن يعمل، على سبيل المثال، كمحاكي عامل مع أو بدون نقطة محاذاة، أو كنقطة كسر سطر، أو يُجمّع بحيث لا يسمح بوجود فواصل سطر داخلها. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | يضع عناصر الطفل في صف عمودي. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | يضيف شريطًا أسفل هذا العنصر. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | يحفظ محتوى هذا [`MathBlock`](../mathblock) كـ MathML. |

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