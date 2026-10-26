---
title: MathMatrix class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix کلاس

Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns. 
            It is important to note that matrices do not have built in delimiters. 
            To place the matrix in the brackets you should use the delimiter object (IMathDelimiter).
            Null arguments can be used to create gaps in matrices.

**ارث‌بری:**[`MathMatrix`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)

The MathMatrix type exposes the following members:

## سازنده‌ها

| سازنده | توضیح |
| :- | :- |
| [`__init__(self, row_count, column_count)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/__init__/#int-int) | یک نمونهٔ جدید از کلاس MathMatrix را مقداردهی اولیه می‌کند. |

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`row_count`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/row_count/) | تعداد ردیف‌ها در ماتریس |
| [`column_count`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/column_count/) | تعداد ستون‌ها در ماتریس |
| [`hide_placeholders`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | پنهان کردن جای‌گیرها برای عناصر خالی ماتریس<br/>            پیش‌فرض: false |
| [`base_justification`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/base_justification/) | تعیین تراز عمودی نسبت به متن اطراف.<br/>            مقادیر ممکن top، bottom و center هستند.<br/>            پیش‌فرض: Center |
| [`min_column_width`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/min_column_width/) | حداقل عرض ستون بر حسب twips (1/20ام نقطه)<br/>            فاصلهٔ بین‌ستونی (که به عنوان “Column Gap” یا “Gap Width” نیز شناخته می‌شود) به<br/>            MinColumnWidth اضافه می‌شود تا کل فاصلهٔ ستون‌های ماتریس تعیین شود<br/>            (فاصله بین لبه‌های مشابه ستون‌های مختلف).<br/>            پیش‌فرض: 0. |
| [`column_gap_rule`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | نوع فاصلهٔ افقی بین ستون‌های یک ماتریس؛<br/>            واحدهای فاصلهٔ افقی می‌توانند ems یا points باشند (به صورت twips ذخیره می‌شوند).<br/>            پیش‌فرض: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/column_gap/) | مقدار فاصلهٔ افقی بین ستون‌های یک ماتریس؛<br/>            اگر ColumnGapRule برابر 3 ("Exactly") باشد، واحد به عنوان twips (1/20ام نقطه) تعبیر می‌شود<br/>            اگر ColumnGapRule برابر 4 ("Multiple") باشد، واحد به عنوان تعداد افزایشی 0.5 em تعبیر می‌شود.<br/>            در سایر موارد نادیده گرفته می‌شود.<br/>            پیش‌فرض: 0 |
| [`row_gap_rule`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | نوع فاصلهٔ عمودی بین ردیف‌های یک ماتریس؛<br/>            واحدهای فاصلهٔ عمودی می‌توانند خطوط یا points باشند (به صورت twips ذخیره می‌شوند).<br/>            پیش‌فرض: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/row_gap/) | مقدار فاصلهٔ عمودی بین ردیف‌های یک ماتریس؛<br/>            اگر RowGapRule برابر 3 ("Exactly") باشد، واحد به عنوان twips (1/20ام نقطه) تعبیر می‌شود<br/>            اگر RowGapRule برابر 4 ("Multiple") باشد، واحد به عنوان نیم‌خط‌ها تعبیر می‌شود.<br/>            پیش‌فرض: 0 |

## متدها

| متد | توضیح |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/join/#imathelement) | یک عنصر ریاضیاتی را به هم می‌پیوندد و یک بلاک ریاضیاتی ایجاد می‌کند |
| [`join(self, math_text)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/join/#str) | یک متن ریاضیاتی را به هم می‌پیوندد و یک بلاک ریاضیاتی ایجاد می‌کند |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/divide/#imathelement) | یک کسر با این صورت و مخرج مشخص شده ایجاد می‌کند |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/divide/#str) | یک کسر با این صورت و مخرج مشخص شده ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/divide/#imathelement-mathfractiontypes) | یک کسر از نوع مشخص شده با این صورت و مخرج مشخص ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/divide/#str-mathfractiontypes) | یک کسر از نوع مشخص شده با این صورت و مخرج مشخص ایجاد می‌کند |
| [`enclose(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/enclose/#) | یک عنصر ریاضی را در پرانتز می‌گیرد |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/enclose/#char-char) | یک عنصر ریاضی را در کاراکترهای مشخص شده مانند پرانتز یا سایر کاراکترها به عنوان قاب می‌گیرد |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/function/#imathelement) | یک تابع از یک آرگومان می‌گیرد که این نمونه به عنوان نام تابع استفاده می‌شود |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/function/#str) | یک تابع از یک آرگومان می‌گیرد که این نمونه به عنوان نام تابع استفاده می‌شود |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#imathelement) | تابع مشخص شده‌ای را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#str) | تابع مشخص شده‌ای را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsofoneargument) | تابع مشخص شده‌ای را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | تابع مشخص شده‌ای را می‌گیرد که این نمونه به عنوان آرگومان و یک آرگومان اضافهٔ مشخص استفاده می‌شود |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) | تابع مشخص شده‌ای را می‌گیرد که این نمونه به عنوان آرگومان و یک آرگومان اضافهٔ مشخص استفاده می‌شود |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/set_subscript/#imathelement) | زیرنویس ایجاد می‌کند |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/set_subscript/#str) | زیرنویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/set_superscript/#imathelement) | بالانویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/set_superscript/#str) | بالانویس ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#str-str) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#str-str) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/radical/#imathelement) | ریشهٔ ریاضیاتی از درجهٔ داده‌شده را از آرگومان مشخص شده تعیین می‌کند. |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/radical/#str) | ریشهٔ ریاضیاتی از درجهٔ داده‌شده را از آرگومان مشخص شده تعیین می‌کند. |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/set_upper_limit/#imathelement) | حد بالا را می‌گیرد |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/set_upper_limit/#str) | حد بالا را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/set_lower_limit/#imathelement) | حد پایین را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/set_lower_limit/#str) | حد پایین را می‌گیرد |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) | یک عملگر N-ary ایجاد می‌کند |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-str-str) | یک عملگر N-ary ایجاد می‌کند |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement) | انتگرال را می‌گیرد |
| [`integral(self, integral_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes) | انتگرال را بدون حد می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str) | انتگرال را می‌گیرد |
| [`group(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/group/#) | این عنصر را با استفاده از براکت کروی زیرین در یک گروه قرار می‌دهد |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) | این عنصر را با استفاده از کاراکتر گروه‌بند مانند براکت کروی زیرین یا دیگری در یک گروه قرار می‌دهد |
| [`to_border_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/to_border_box/#) | این عنصر را در یک جعبهٔ حاشیه قرار می‌دهد |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | این عنصر را در یک جعبهٔ حاشیه قرار می‌دهد |
| [`to_math_array(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/to_math_array/#) | در یک آرایهٔ عمودی قرار می‌دهد |
| [`accent(self, accent_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/accent/#char) | یک علامت لهجه (کاراکتری در بالای این عنصر) تنظیم می‌کند |
| [`overbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/overbar/#) | یک نوار در بالای این عنصر تنظیم می‌کند |
| [`underbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/underbar/#) | یک نوار در پایین این عنصر تنظیم می‌کند |
| [`to_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/to_box/#) | این عنصر را در یک جعبهٔ غیر‌ دیداری (گروه‌بندی منطقی) قرار می‌دهد <br/>            که برای گروه‌بندی اجزای یک معادله یا سایر نمونه‌های متن ریاضیاتی استفاده می‌شود.<br/>            یک شیء جعبه‌دار می‌تواند (به عنوان مثال) به عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز عمل کند، <br/>            به عنوان نقطهٔ شکستن خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که اجازهٔ شکستن خط درون آن داده نشود. |
| [`get_column_alignment(self, column_index)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/get_column_alignment/#int) | تراز افقی ستون مشخص‌شده را دریافت می‌کند |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/set_column_alignment/#int-mathhorizontalalignment) | تراز افقی ستون مشخص‌شده را تنظیم می‌کند |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | تراز افقی ستون‌های مشخص‌شده را تنظیم می‌کند |
| [`insert_row_before(self, row_index)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/insert_row_before/#int) | یک ردیف جدید را قبل از ردیف مشخص‌شده وارد می‌کند<br/>            در ابتدا تمام عناصر ردیف جدید None هستند. |
| [`insert_row_after(self, row_index)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/insert_row_after/#int) | یک ردیف جدید را پس از ردیف مشخص‌شده وارد می‌کند<br/>            در ابتدا تمام عناصر ردیف جدید None هستند. |
| [`delete_row(self, row_index)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/delete_row/#int) | ردیف مشخص‌شده را حذف می‌کند |
| [`insert_column_before(self, column_index)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/insert_column_before/#int) | یک ستون جدید را قبل از ستون مشخص‌شده وارد می‌کند<br/>            در ابتدا تمام عناصر ستون جدید None هستند. |
| [`insert_column_after(self, column_index)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/insert_column_after/#int) | یک ستون جدید را پس از ستون مشخص‌شده وارد می‌کند<br/>            در ابتدا تمام عناصر ستون جدید None هستند. |
| [`delete_column(self, column_index)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/delete_column/#int) | ستون مشخص‌شده را حذف می‌کند |
| [`get_children(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix/get_children/#) | عناصر فرزند را دریافت می‌کند |

### موارد مرتبط
* کلاس [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)
* کلاس [`MathMatrix`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)