---
title: IMathMatrix class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix کلاس

Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns.  
It is important to note that matrices do not have built in delimiters.  
To place the matrix in the brackets you should use the delimiter object (IMathDelimiter).  
Null arguments can be used to create gaps in matrices.

The IMathMatrix type exposes the following members:

## خصوصیات

| ویژگی | توضیح |
| :- | :- |
| [`row_count`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/row_count/) | تعداد سطرهای ماتریس |
| [`column_count`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/column_count/) | تعداد ستون‌های ماتریس |
| [`hide_placeholders`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | پنهان کردن مکان‌نگهدارها برای عناصر خالی ماتریس<br/>            Default: false |
| [`base_justification`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/base_justification/) | Specifies the vertical justification respect to surrounding text.<br/>            Possible values are top, bottom, and center.<br/>            Default: Center |
| [`min_column_width`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/min_column_width/) | حداقل عرض ستون به twips (1/20 ام نقطه)<br/>            فاصلهٔ بین ستون‌ها (که به عنوان «Column Gap» یا «Gap Width» نیز نامیده می‌شود) به MinColumnWidth اضافه می‌شود تا کل فاصلهٔ ستون‌های ماتریس تعیین شود<br/>            (فاصله بین لبه‌های مشابه ستون‌های مختلف).<br/>            Default: 0. |
| [`column_gap_rule`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | نوع فاصلهٔ افقی بین ستون‌های یک ماتریس؛<br/>            واحدهای فاصلهٔ افقی می‌توانند em یا point باشند (به صورت twips ذخیره می‌شوند).<br/>            Default: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/column_gap/) | مقدار فاصلهٔ افقی بین ستون‌های یک ماتریس؛<br/>            اگر ColumnGapRule برابر 3 («Exactly») باشد، واحد به عنوان twips (1/20 ام نقطه) تفسیر می‌شود.<br/>            اگر ColumnGapRule برابر 4 («Multiple») باشد، واحد به عنوان تعداد گام‌های 0.5 em تفسیر می‌شود.<br/>            در موارد دیگر نادیده گرفته می‌شود.<br/>            Default: 0 |
| [`row_gap_rule`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | نوع فاصلهٔ عمودی بین سطرهای یک ماتریس؛<br/>            واحدهای فاصلهٔ عمودی می‌توانند خطوط یا points (به صورت twips ذخیره می‌شوند).<br/>            Default: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/row_gap/) | مقدار فاصلهٔ عمودی بین سطرهای یک ماتریس؛<br/>            اگر RowGapRule برابر 3 («Exactly») باشد، واحد به عنوان twips (1/20 ام نقطه) تفسیر می‌شود.<br/>            اگر RowGapRule برابر 4 («Multiple») باشد، واحد به عنوان نصف خط‌ها تفسیر می‌شود.<br/>            Default: 0 |

## متدها

| متد | توضیح |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment(self, column_index)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | دریافت تراز افقی ستون مشخص شده |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | تنظیم تراز افقی ستون مشخص شده |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | تنظیم تراز افقی ستون‌های مشخص شده |
| [`insert_row_before(self, row_index)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | افزودن سطر جدید قبل از سطر مشخص‌شده<br/>            در ابتدا همهٔ عناصر سطر جدید None هستند. |
| [`insert_row_after(self, row_index)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | افزودن سطر جدید پس از سطر مشخص‌شده<br/>            در ابتدا همهٔ عناصر سطر جدید None هستند. |
| [`delete_row(self, row_index)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/delete_row/#int) | حذف سطر مشخص‌شده |
| [`insert_column_before(self, column_index)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | افزودن ستون جدید قبل از ستون مشخص‌شده<br/>            در ابتدا همهٔ عناصر ستون جدید None هستند. |
| [`insert_column_after(self, column_index)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | افزودن ستون جدید پس از ستون مشخص‌شده<br/>            در ابتدا همهٔ عناصر ستون جدید None هستند. |
| [`delete_column(self, column_index)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/delete_column/#int) | حذف ستون مشخص‌شده |
| [`get_children(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathmatrix/to_box/#) |  |

### مراجع
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)