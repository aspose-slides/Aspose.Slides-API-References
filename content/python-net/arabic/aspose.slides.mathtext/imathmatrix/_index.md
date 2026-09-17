---
title: IMathMatrix class
second_title: مرجع API Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.mathtext/imathmatrix/
---
## فئة IMathMatrix

يحدد كائن Matrix، المكوّن من عناصر فرعية مرتبة في صف واحد أو أكثر وأعمدة. 
            من المهم ملاحظة أن المصفوفات لا تحتوي على فواصل مدمجة. 
            لوضع المصفوفة داخل الأقواس يجب عليك استخدام كائن الفاصل (IMathDelimiter).
            يمكن استخدام وسائط Null لإنشاء فراغات في المصفوفات.

The IMathMatrix type exposes the following members:

## الخصائص

| خاصية | الوصف |
| :- | :- |
| [`row_count`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/row_count/) | عدد الصفوف في المصفوفة |
| [`column_count`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/column_count/) | عدد الأعمدة في المصفوفة |
| [`hide_placeholders`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | إخفاء عناصر النائب للعناصر الفارغة في المصفوفة<br/>            الافتراضي: false |
| [`base_justification`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/base_justification/) | يحدد الضبط الرأسي بالنسبة للنص المحيط. <br/>            القيم الممكنة هي top, bottom, و center.<br/>            الافتراضي: Center |
| [`min_column_width`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/min_column_width/) | الحد الأدنى لعرض العمود بوحدة twips (1/20 من النقطة)<br/>            يتم إضافة تباعد الفجوة (المشار إليه أيضًا بـ “Column Gap” أو “Gap Width”) إلى <br/>            MinColumnWidth لتحديد إجمالي تباعد أعمدة المصفوفة<br/>            (المسافة بين الحواف المتطابقة للأعمدة المختلفة).<br/>            الافتراضي: 0. |
| [`column_gap_rule`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | نوع التباعد الأفقي بين أعمدة المصفوفة؛ <br/>            يمكن أن تكون وحدات التباعد الأفقي إيم أو نقاط (مخزنة كـ twips).<br/>            الافتراضي: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/column_gap/) | قيمة التباعد الأفقي بين أعمدة المصفوفة;<br/>            إذا تم تعيين ColumnGapRule إلى 3 ("Exactly"), فسيتم تفسير الوحدة كـ twips (1/20 من النقطة)<br/>            إذا تم تعيين ColumnGapRule إلى 4 ("Multiple"), فسيتم تفسير الوحدة كعدد من الزيادات 0.6 em.<br/>            في الحالات الأخرى يتم تجاهلها.<br/>            الافتراضي: 0 |
| [`row_gap_rule`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | نوع التباعد الرأسي بين صفوف المصفوفة؛ <br/>            يمكن أن تكون وحدات التباعد الرأسي خطوط أو نقاط (مخزنة كـ twips).<br/>            الافتراضي: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/row_gap/) | قيمة التباعد الرأسي بين صفوف المصفوفة;<br/>            إذا تم تعيين RowGapRule إلى 3 ("Exactly"), فسيتم تفسير الوحدة كـ twips (1/20 من النقطة)<br/>            إذا تم تعيين RowGapRule إلى 4 ("Multiple"), فسيتم تفسير الوحدة كنصف خطوط.<br/>            الافتراضي: 0 |

## الطرق

| طريقة | الوصف |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment(self, column_index)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | الحصول على محاذاة الصف الأفقي للعمود المحدد |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | تعيين محاذاة الصف الأفقي للعمود المحدد |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | تعيين محاذاة الصف الأفقي للأعمدة المحددة |
| [`insert_row_before(self, row_index)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | إدراج صف جديد قبل الصف المحدد<br/>            في البداية جميع العناصر في الصف الجديد هي None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | إدراج صف جديد بعد الصف المحدد<br/>            في البداية جميع العناصر في الصف الجديد هي None. |
| [`delete_row(self, row_index)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/delete_row/#int) | يحذف الصف المحدد |
| [`insert_column_before(self, column_index)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | إدراج عمود جديد قبل العمود المحدد<br/>            في البداية جميع العناصر في العمود الجديد هي None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | إدراج عمود جديد بعد العمود المحدد<br/>            في البداية جميع العناصر في العمود الجديد هي None. |
| [`delete_column(self, column_index)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/delete_column/#int) | يحذف العمود المحدد |
| [`get_children(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathmatrix/to_box/#) |  |

### انظر أيضا
* الوحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* المكتبة [`Aspose.Slides`](/slides/python-net)