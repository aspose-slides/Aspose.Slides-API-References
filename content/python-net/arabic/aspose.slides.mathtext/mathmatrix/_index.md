---
title: MathMatrix class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathmatrix/
---
## فئة MathMatrix

يحدد كائن Matrix، المكوّن من عناصر فرعية مرتّبة في صف واحد أو أكثر وأعمدة. 
            من المهم ملاحظة أن المصفوفات لا تحتوي على محددات مدمجة. 
            لوضع المصفوفة بين الأقواس عليك استخدام كائن المحدد (IMathDelimiter). 
            يمكن استخدام القيم الفارغة لإنشاء فجوات في المصفوفات.

**Inheritance:**[`MathMatrix`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)

نوع MathMatrix يكشف عن الأعضاء التالية:

## المُنشئات

| Constructor | Description |
| :- | :- |
| [`__init__(self, row_count, column_count)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/__init__/#int-int) | ي初始化 نسخة جديدة من فئة MathMatrix. |

## الخصائص

| Property | Description |
| :- | :- |
| [`row_count`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/row_count/) | عدد الصفوف في المصفوفة |
| [`column_count`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/column_count/) | عدد الأعمدة في المصفوفة |
| [`hide_placeholders`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | إخفاء العناصر النائبة للمصفوفة الفارغة<br/>            Default: false |
| [`base_justification`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/base_justification/) | يحدد المحاذاة العمودية بالنسبة للنص المحيط.<br/>            القيم الممكنة هي top, bottom, و center.<br/>            Default: Center |
| [`min_column_width`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/min_column_width/) | الحد الأدنى لعرض العمود بوحدات twips (1/20 نقطة)<br/>            يتم إضافة تباعد الفجوة (المعروف أيضًا باسم “Column Gap” أو “Gap Width”) إلى<br/>            MinColumnWidth لتحديد إجمالي تباعد أعمدة المصفوفة<br/>            (المسافة بين الحواف المتساوية لأعمدة مختلفة).<br/>            Default: 0. |
| [`column_gap_rule`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | نوع التباعد الأفقي بين أعمدة المصفوفة؛<br/>            يمكن أن تكون وحدات التباعد الأفقي إما ems أو نقاط (مخزنة كـ twips).<br/>            Default: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/column_gap/) | قيمة التباعد الأفقي بين أعمدة المصفوفة؛<br/>            إذا تم ضبط ColumnGapRule على 3 (“Exactly”)، فإن الوحدة تُفسَّر كـ twips (1/20 نقطة)<br/>            إذا تم ضبط ColumnGapRule على 4 (“Multiple”)، فإن الوحدة تُفسَّر كعدد من الزيادات بمقدار 0.5 em.<br/>            في الحالات الأخرى تُهمل.<br/>            Default: 0 |
| [`row_gap_rule`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | نوع التباعد العمودي بين صفوف المصفوفة؛<br/>            يمكن أن تكون وحدات التباعد العمودي خطوط أو نقاط (مخزنة كـ twips).<br/>            Default: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/row_gap/) | قيمة التباعد العمودي بين صفوف المصفوفة؛<br/>            إذا تم ضبط RowGapRule على 3 (“Exactly”)، فإن الوحدة تُفسَّر كـ twips (1/20 نقطة)<br/>            إذا تم ضبط RowGapRule على 4 (“Multiple”)، فإن الوحدة تُفسَّر كنصف خطوط.<br/>            Default: 0 |

## الأساليب

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/join/#imathelement) | يدمج عنصرًا رياضيًا ويشكل كتلة رياضية |
| [`join(self, math_text)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/join/#str) | يدمج نصًا رياضيًا ويشكل كتلة رياضية |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/divide/#imathelement) | ينشئ كسرًا باستخدام هذا البسط والمقام المحدد |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/divide/#str) | ينشئ كسرًا باستخدام هذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/divide/#imathelement-mathfractiontypes) | ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/divide/#str-mathfractiontypes) | ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد |
| [`enclose(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/enclose/#) | يحيط عنصرًا رياضيًا بأقواس |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/enclose/#char-char) | يحيط عنصرًا رياضيًا بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/function/#imathelement) | يأخذ دالة لوسيط باستخدام هذه النسخة كاسم الدالة |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/function/#str) | يأخذ دالة لوسيط باستخدام هذه النسخة كاسم الدالة |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#imathelement) | يأخذ الدالة المحددة باستخدام هذه النسخة كوسيط |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#str) | يأخذ الدالة المحددة باستخدام هذه النسخة كوسيط |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsofoneargument) | يأخذ الدالة المحددة باستخدام هذه النسخة كوسيط |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | يأخذ الدالة المحددة باستخدام هذه النسخة كوسيط ووسيط إضافي محدد |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) | يأخذ الدالة المحددة باستخدام هذه النسخة كوسيط ووسيط إضافي محدد |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/set_subscript/#imathelement) | ينشئ نصًا فرعيًا |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/set_subscript/#str) | ينشئ نصًا فرعيًا |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/set_superscript/#imathelement) | ينشئ نصًا فوقيًّا |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/set_superscript/#str) | ينشئ نصًا فوقيًّا |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) | ينشئ نصًا فرعيًا وفوقيًّا على اليمين |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#str-str) | ينشئ نصًا فرعيًا وفوقيًّا على اليمين |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) | ينشئ نصًا فرعيًا وفوقيًّا على اليسار |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#str-str) | ينشئ نصًا فرعيًا وفوقيًّا على اليسار |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/radical/#imathelement) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد. |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/radical/#str) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/set_upper_limit/#imathelement) | يأخذ الحد العلوي |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/set_upper_limit/#str) | يأخذ الحد العلوي |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/set_lower_limit/#imathelement) | يأخذ الحد السفلي |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/set_lower_limit/#str) | يأخذ الحد السفلي |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) | ينشئ عاملًا N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-str-str) | ينشئ عاملًا N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement) | يأخذ التكامل |
| [`integral(self, integral_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes) | يأخذ التكامل دون حدود |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str) | يأخذ التكامل |
| [`group(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/group/#) | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [`to_border_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/to_border_box/#) | يضع هذا العنصر في صندوق حدود |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | يضع هذا العنصر في صندوق حدود |
| [`to_math_array(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/to_math_array/#) | يضعه في مصفوفة عمودية |
| [`accent(self, accent_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/accent/#char) | يضيف علامة توكيد (حرف فوق هذا العنصر) |
| [`overbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/overbar/#) | يضيف شريطًا أعلى هذا العنصر |
| [`underbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/underbar/#) | يضيف شريطًا أسفل هذا العنصر |
| [`to_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/to_box/#) | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي)<br/>            يُستخدم لتجميع مكونات المعادلة أو نص رياضي آخر.<br/>            يمكن أن يعمل ككائن موضع (على سبيل المثال) كمحاكي عامل مع أو بدون نقطة محاذاة،<br/>            يعمل كنقطة كسر سطر، أو يُجَمَّع بحيث لا يسمح بكسور السطر داخله. |
| [`get_column_alignment(self, column_index)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/get_column_alignment/#int) | يحصل على محاذاة أفقية للعمود المحدد |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/set_column_alignment/#int-mathhorizontalalignment) | يعيّن محاذاة أفقية للعمود المحدد |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | يعيّن محاذاة أفقية للأعمدة المحددة |
| [`insert_row_before(self, row_index)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/insert_row_before/#int) | يُدرج صفًا جديدًا قبل الصف المحدد<br/>            في البداية جميع العناصر في الصف الجديد هي None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/insert_row_after/#int) | يُدرج صفًا جديدًا بعد الصف المحدد<br/>            في البداية جميع العناصر في الصف الجديد هي None. |
| [`delete_row(self, row_index)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/delete_row/#int) | يحذف الصف المحدد |
| [`insert_column_before(self, column_index)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/insert_column_before/#int) | يُدرج عمودًا جديدًا قبل العمود المحدد<br/>            في البداية جميع العناصر في العمود الجديد هي None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/insert_column_after/#int) | يُدرج عمودًا جديدًا بعد العمود المحدد<br/>            في البداية جميع العناصر في العمود الجديد هي None. |
| [`delete_column(self, column_index)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/delete_column/#int) | يحذف العمود المحدد |
| [`get_children(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix/get_children/#) | يحصل على العناصر الفرعية |


### راجع أيضًا
* الفئة [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)
* الفئة [`MathMatrix`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix)
* الوحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* المكتبة [`Aspose.Slides`](/slides/python-net)