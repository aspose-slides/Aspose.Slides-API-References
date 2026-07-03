---
title: MathMatrix
second_title: Aspose.Sildes لمرجع API .NET
description: يحدد كائن Matrix المكوّن من عناصر فرعية مرتبة في صف واحد أو أكثر وأعمدة. من المهم ملاحظة أن المصفوفات لا تحتوي على محددات مدمجة. لوضع المصفوفة بين الأقواس يجب استخدام كائن المحدد IMathDelimiter. يمكن استخدام معاملات Null لإنشاء فراغات في المصفوفات.
type: docs
weight: 8850
url: /ar/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix الفئة

يحدد كائن Matrix، المكوّن من عناصر فرعية مرتّبة في صف واحد أو أكثر وأعمدة. من المهم ملاحظة أن المصفوفات لا تحتوي على محددات مدمجة. لوضع المصفوفة بين الأقواس يجب استخدام كائن المحدد (IMathDelimiter). يمكن استخدام معاملات Null لإنشاء فراغات في المصفوفات.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | يخلق مثيلاً جديداً من الفئة MathMatrix. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | يحدد محاذاة عمودية بالنسبة للنص المحيط. القيم المحتملة هي top, bottom, and center. الافتراضي: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | عدد الأعمدة في المصفوفة |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | قيمة الفجوة الأفقية بين أعمدة المصفوفة؛ إذا تم تعيين ColumnGapRule إلى 3 ("Exactly")، فسيتم تفسير الوحدة كـ twips (1/20 من النقطة). إذا تم تعيين ColumnGapRule إلى 4 ("Multiple")، فستُفسّر كعدد من الزيادات 0.5 em. في الحالات الأخرى يتم تجاهلها. الافتراضي: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | نوع الفجوة الأفقية بين أعمدة المصفوفة؛ يمكن أن تكون الوحدات ems أو points (مخزنة كـ twips). الافتراضي: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | إخفاء العناصر النائبة للعناصر الفارغة في المصفوفة. الافتراضي: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | عنصر من المصفوفة |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | الحد الأدنى لعرض العمود بوحدة twips (1/20 من النقطة). تُضاف الفجوة (المعروفة أيضاً باسم “Column Gap” أو “Gap Width”) إلى MinColumnWidth لتحديد إجمالي تباعد أعمدة المصفوفة (المسافة بين حواف الأعمدة المختلفة). الافتراضي: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | عدد الصفوف في المصفوفة |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | قيمة الفجوة العمودية بين صفوف المصفوفة؛ إذا تم تعيين RowGapRule إلى 3 ("Exactly")، فسيتم تفسير الوحدة كـ twips (1/20 من النقطة). إذا تم تعيين RowGapRule إلى 4 ("Multiple")، فستُفسّر كأنصاف أسطر. الافتراضي: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | نوع الفجوة العمودية بين صفوف المصفوفة؛ يمكن أن تكون الوحدات lines أو points (مخزنة كـ twips). الافتراضي: SingleSpacingGap (0) |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | يضع علامة لهجة (حرف فوق هذا العنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل ويضيف المعامل الإضافي المحدد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل ويضيف المعامل الإضافي المحدد |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | يحذف العمود المحدد |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | يحذف الصف المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | ينشئ كسرًا باستخدام هذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | ينشئ كسرًا باستخدام هذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | يطوق عنصر رياضي بين قوسين |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | يطوق عنصر رياضي بين أحرف محددة مثل القوس أو أحرف إطارية أخرى |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | يأخذ دالة لوسيط باستخدام هذه المثيلة كاسم الدالة |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | يأخذ دالة لوسيط باستخدام هذه المثيلة كاسم الدالة |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | الحصول على العناصر الفرعية |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | الحصول على محاذاة أفقية للعمود المحدد |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل قوس معقوف سفلي أو غيره |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | يضيف عمودًا جديدًا بعد العمود المحدد. في البداية تكون جميع العناصر في العمود الجديد null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | يضيف عمودًا جديدًا قبل العمود المحدد. في البداية تكون جميع العناصر في العمود الجديد null. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | يضيف صفًا جديدًا بعد الصف المحدد. في البداية تكون جميع العناصر في الصف الجديد null. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | يضيف صفًا جديدًا قبل الصف المحدد. في البداية تكون جميع العناصر في الصف الجديد null. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | يأخذ التكامل بدون حدود |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | يأخذ التكامل |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | يجمع عنصرًا رياضيًا ويكوّن كتلة رياضية |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | يجمع نصًا رياضيًا ويكوّن كتلة رياضية |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | ينشئ مُعاملًا N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | ينشئ مُعاملًا N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | يضع شريطًا فوق هذا العنصر |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | يضبط المحاذاة الأفقية للعمود المحدد |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | يضبط المحاذاة الأفقية للأعمدة المحددة |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | يأخذ حدًا سفليًا |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | يأخذ حدًا سفليًا |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | ينشئ حروفًا سفلية |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | ينشئ حروفًا سفلية |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | ينشئ حروفًا سفلية وعليا على اليسار |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | ينشئ حروفًا سفلية وعليا على اليسار |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | ينشئ حروفًا سفلية وعليا على اليمين |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | ينشئ حروفًا سفلية وعليا على اليمين |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | ينشئ حروفًا عليا |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | ينشئ حروفًا عليا |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | يأخذ حدًا علويًا |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | يأخذ حدًا علويًا |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | يضع هذا العنصر في صندوق حدود |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | يضع هذا العنصر في صندوق حدود |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو نص رياضي آخر. يمكن أن يعمل كجهاز محاكاة لمُعامل مع أو بدون نقطة محاذاة، أو كنقطة كسر سطر، أو يُجمع بحيث لا يُسمح بكسور السطر داخله. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | يضع في مصفوفة رأسية |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | يضع شريطًا أسفل هذا العنصر |

### أمثلة

Example:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### انظر أيضاً

* class [MathElementBase](../mathelementbase)
* interface [IMathMatrix](../imathmatrix)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->