---
title: MathMatrix
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يحدد كائن المصفوفة المكوّن من عناصر فرعية مرتبة في صف واحد أو أكثر وأعمدة. من المهم ملاحظة أن المصفوفات لا تحتوي على فواصل مدمجة. لوضع المصفوفة داخل الأقواس يجب عليك استخدام كائن الفاصل IMathDelimiter. يمكن استخدام المعاملات ذات القيمة Null لإنشاء فراغات في المصفوفات.
type: docs
weight: 8870
url: /ar/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix فئة

يحدد كائن المصفوفة، المكوّن من عناصر فرعية مرتبة في صف واحد أو أكثر وأعمدة. من المهم ملاحظة أن المصفوفات لا تحتوي على فواصل مدمجة. لوضع المصفوفة داخل الأقواس يجب عليك استخدام كائن الفاصل (IMathDelimiter). يمكن استخدام المعاملات ذات القيمة Null لإنشاء فراغات في المصفوفات.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Constructors

| الاسم | الوصف |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | يقوم بتهيئة نسخة جديدة من الفئة MathMatrix. |

## Properties

| الاسم | الوصف |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | يحدد محاذاة العمودية بالنسبة للنص المحيط. القيم الممكنة هي top و bottom و Center. القيمة الافتراضية: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | عدد الأعمدة في المصفوفة |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | قيمة الفاصل الأفقي بين أعمدة المصفوفة؛ إذا تم تعيين ColumnGapRule إلى 3 ("Exactly")، فسيتم تفسير الوحدة كتوِيبس (1/20 من النقطة). إذا تم تعيين ColumnGapRule إلى 4 ("Multiple")، فسيتم تفسير الوحدة كعدد من الزيادات بمقدار 0.5 em. في الحالات الأخرى يتم تجاهلها. القيمة الافتراضية: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | نوع الفاصل الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون وحدات الفاصل الأفقي إما ems أو points (مخزنة كتوِيبس). القيمة الافتراضية: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | إخفاء العناصر النائبة لعناصر المصفوفة الفارغة. القيمة الافتراضية: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | عنصر من المصفوفة |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | العرض الأدنى للعمود بوحدات twips (1/20 من النقطة). يتم إضافة الفاصل (المعروف أيضاً باسم “Column Gap” أو “Gap Width”) إلى MinColumnWidth لتحديد إجمالي الفاصل بين أعمدة المصفوفة (المسافة بين حواف الأعمدة المختلفة). القيمة الافتراضية: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | عدد الصفوف في المصفوفة |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | قيمة الفاصل العمودي بين صفوف المصفوفة؛ إذا تم تعيين RowGapRule إلى 3 ("Exactly")، فسيتم تفسير الوحدة كتوِيبس (1/20 من النقطة). إذا تم تعيين RowGapRule إلى 4 ("Multiple")، فسيتم تفسير الوحدة كنصف خطوط. القيمة الافتراضية: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | نوع الفاصل العمودي بين صفوف المصفوفة؛ يمكن أن تكون وحدات الفاصل العمودي إما lines أو points (مخزنة كتوِيبس). القيمة الافتراضية: SingleSpacingGap (0) |

## Methods

| الاسم | الوصف |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | يحدد علامة إكسنت (حرف فوق هذا العنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | ينفذ الدالة المحددة باستخدام هذه النسخة كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | ينفذ الدالة المحددة باستخدام هذه النسخة كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | ينفذ الدالة المحددة باستخدام هذه النسخة كمعامل |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | ينفذ الدالة المحددة باستخدام هذه النسخة كمعامل بالإضافة إلى معامل إضافي محدد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | ينفذ الدالة المحددة باستخدام هذه النسخة كمعامل بالإضافة إلى معامل إضافي محدد |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | يحذف العمود المحدد |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | يحذف الصف المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | ينشئ كسرًا بهذا البسط وال مقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | ينشئ كسرًا بهذا البسط وال مقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | يطويق عنصر رياضي بأقواس |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | يطويق عنصر رياضي بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | يستدعي دالة للمعامل باستخدام هذه النسخة كاسم الدالة |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | يستدعي دالة للمعامل باستخدام هذه النسخة كاسم الدالة |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | يحصل على العناصر الفرعية |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | يحصل على المحاذاة الأفقية للعمود المحدد |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | يضع هذا العنصر في مجموعة باستخدام القوس المعقوف السفلي |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | يدرج عمودًا جديدًا بعد العمود المحدد. في البداية جميع العناصر في العمود الجديد هي null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | يدرج عمودًا جديدًا قبل العمود المحدد. في البداية جميع العناصر في العمود الجديد هي null. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | يدرج صفًا جديدًا بعد الصف المحدد. في البداية جميع العناصر في الصف الجديد هي null. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | يدرج صفًا جديدًا قبل الصف المحدد. في البداية جميع العناصر في الصف الجديد هي null. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | يأخذ التكامل دون حدود |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | يأخذ التكامل |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | يجمع عنصرًا رياضيًا ويشكل كتلة رياضية |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | يجمع نصًا رياضيًا ويشكل كتلة رياضية |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | ينشئ عاملًا N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | ينشئ عاملًا N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | يضع شريطًا أعلى هذا العنصر |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | يضبط المحاذاة الأفقية للعمود المحدد |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | يضبط المحاذاة الأفقية للأعمدة المحددة |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | يأخذ الحد الأدنى |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | يأخذ الحد الأدنى |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | ينشئ مؤشرًا سفليًا |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | ينشئ مؤشرًا سفليًا |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | ينشئ مؤشرًا سفليًا وعلويًا على اليسار |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | ينشئ مؤشرًا سفليًا وعلويًا على اليسار |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | ينشئ مؤشرًا سفليًا وعلويًا على اليمين |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | ينشئ مؤشرًا سفليًا وعلويًا على اليمين |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | ينشئ مؤشرًا علويًا |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | ينشئ مؤشرًا علويًا |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | يأخذ الحد الأعلى |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | يأخذ الحد الأعلى |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | يضع هذا العنصر في صندوق حدود |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | يضع هذا العنصر في صندوق حدود |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو نص رياضي آخر. يمكن لكائن محاط بصندوق (على سبيل المثال) أن يعمل كمحاكي عامل مع أو بدون نقطة محاذاة، أو كنقطة كسر سطر، أو أن يُجمع بحيث لا يُسمح بكسر السطر داخله. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | يضع في صف عمودي |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | يضع شريطًا أسفل هذا العنصر |

### أمثلة

مثال:

```csharp
[C#]
IMMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### انظر أيضًا

* فئة [MathElementBase](../mathelementbase)
* واجهة [IMathMatrix](../imathmatrix)
* نطاق الاسم [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->