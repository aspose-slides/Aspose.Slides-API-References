---
title: MathMatrix
second_title: مرجع API Aspose.Sildes لـ .NET
description: يحدد كائن Matrix المكوّن من عناصر فرعية مرتبة في صف واحد أو أكثر وأعمدة. من المهم ملاحظة أن المصفوفات لا تحتوي على فواصل مدمجة. لوضع المصفوفة داخل الأقواس يجب استخدام كائن الفاصل IMathDelimiter. يمكن استخدام المعلمات الفارغة لإنشاء فراغات في المصفوفات.
type: docs
weight: 8850
url: /ar/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix فئة

يحدد كائن Matrix، المكوّن من عناصر فرعية مرتبة في صف واحد أو أكثر وأعمدة. من المهم ملاحظة أن المصفوفات لا تحتوي على فواصل مدمجة. لوضع المصفوفة داخل الأقواس يجب استخدام كائن الفاصل (IMathDelimiter). يمكن استخدام المعلمات الفارغة لإنشاء فراغات في المصفوفات.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | ينشئ مثيلًا جديدًا من فئة MathMatrix. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | يحدد الضبط العمودي بالنسبة للنص المحيط. القيم الممكنة هي top, bottom, و center. الافتراضي: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | عدد الأعمدة في المصفوفة |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | قيمة التباعد الأفقي بين أعمدة المصفوفة؛ إذا تم تعيين ColumnGapRule إلى 3 ("Exactly"), فالوحدة تُفسَّر كـ twips (1/20 من النقطة). إذا تم تعيين ColumnGapRule إلى 4 ("Multiple"), فالوحدة تُفسَّر كعدد من الزيادات 0.5 em. في الحالات الأخرى تُهمل. الافتراضي: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | نوع التباعد الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون وحدات التباعد الأفقي إما ems أو points (مخزنة كـ twips). الافتراضي: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | إخفاء العناصر النائبة لعناصر المصفوفة الفارغة. الافتراضي: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | عنصر من المصفوفة |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | الحد الأدنى لعرض العمود بوحدة twips (1/20 من النقطة). يُضاف تباعد الفجوة (المعرف أيضًا باسم “Column Gap” أو “Gap Width”) إلى MinColumnWidth لتحديد إجمالي تباعد أعمدة المصفوفة (المسافة بين حواف الأعمدة المختلفة). الافتراضي: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | عدد الصفوف في المصفوفة |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | قيمة التباعد العمودي بين صفوف المصفوة؛ إذا تم تعيين RowGapRule إلى 3 ("Exactly"), فالوحدة تُفسَّر كـ twips (1/20 من النقطة). إذا تم تعيين RowGapRule إلى 4 ("Multiple"), فالوحدة تُفسَّر كنصف خطوط. الافتراضي: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | نوع التباعد العمودي بين صفوف المصفوة؛ يمكن أن تكون وحدات التباعد العمودية إما lines أو points (مخزنة كـ twips). الافتراضي: SingleSpacingGap (0) |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | يضبط علامة إكسنت (حرف على أعلى هذا العنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | يأخذ الدالة المحددة باستخدام هذا الكائن كوسيطة |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | يأخذ الدالة المحددة باستخدام هذا الكائن كوسيطة |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | يأخذ الدالة المحددة باستخدام هذا الكائن كوسيطة |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | يأخذ الدالة المحددة باستخدام هذا الكائن كوسيطة ويضيف وسيلة إضافية محددة |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | يأخذ الدالة المحددة باستخدام هذا الكائن كوسيطة ويضيف وسيلة إضافية محددة |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | يحذف العمود المحدد |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | يحذف الصف المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | ينشئ كسرًا مع هذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | ينشئ كسرًا مع هذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | ينشئ كسرًا من النوع المحدد مع هذا البسط والمقام المحدد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | ينشئ كسرًا من النوع المحدد مع هذا البسط والمقام المحدد |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | يحيط عنصر رياضي بأقواس |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | يحيط عنصر رياضي بالأحرف المحددة مثل الأقواس أو أحرف أخرى كإطار |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | يأخذ دالة لوسيطة باستخدام هذا الكائن كاسم للدالة |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | يأخذ دالة لوسيطة باستخدام هذا الكائن كاسم للدالة |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | يحصل على العناصر الفرعية |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | يحصل على المحاذاة الأفقية للعمود المحدد |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو حرف آخر |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | يدرج عمودًا جديدًا بعد العمود المحدد. في البداية كل العناصر في العمود الجديد هي null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | يدرج عمودًا جديدًا قبل العمود المحدد. في البداية كل العناصر في العمود الجديد هي null. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | يدرج صفًا جديدًا بعد الصف المحدد. في البداية كل العناصر في الصف الجديد هي null. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | يدرج صفًا جديدًا قبل الصف المحدد. في البداية كل العناصر في الصف الجديد هي null. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | يأخذ التكامل بدون حدود |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | يأخذ التكامل |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | يأخذ التكامل |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | ينضم عنصرًا رياضيًا ويشكل كتلة رياضية |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | ينضم نصًا رياضيًا ويشكل كتلة رياضية |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | ينشئ عامل N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | ينشئ عامل N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | يضبط شريطًا فوق هذا العنصر |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيطة المحددة. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيطة المحددة. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | يضبط المحاذاة الأفقية للعمود المحدد |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | يضبط المحاذاة الأفقية للأعمدة المحددة |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | يأخذ الحد الأدنى |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | يأخذ الحد الأدنى |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | ينشئ مؤشر سفلي |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | ينشئ مؤشر سفلي |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | ينشئ مؤشر سفلي ومؤشر علوي على اليسار |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | ينشئ مؤشر سفلي ومؤشر علوي على اليسار |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | ينشئ مؤشر سفلي ومؤشر علوي على اليمين |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | ينشئ مؤشر سفلي ومؤشر علوي على اليمين |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | ينشئ مؤشر علوي |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | ينشئ مؤشر علوي |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | يأخذ الحد الأعلى |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | يأخذ الحد الأعلى |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | يضع هذا العنصر في صندوق حدود |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | يضع هذا العنصر في صندوق حدود |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو نص رياضي آخر. يمكن لكائن مؤطر (على سبيل المثال) أن يعمل كمحاكي عامل مع أو بدون نقطة محاذاة، أو كنقطة كسر سطر، أو يُجمع بحيث لا يسمح بفواصل أسطر داخله. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | يضع في مصفوفة رأسية |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | يضبط شريطًا أسفل هذا العنصر |

### أمثلة

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### انظر أيضًا

* فئة [MathElementBase](../mathelementbase)
* واجهة [IMathMatrix](../imathmatrix)
* مساحة اسم [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->