---
title: MathDelimiter class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter کلاس

شیء جداکننده را مشخص می‌کند که شامل کاراکترهای باز و بسته (مانند پرانتز، 
            کروشه، براکت و خطوط عمودی) و یک یا چند عنصر ریاضی داخل آن است که با یک کاراکتر مشخص جدا می‌شوند.
            مثال‌ها: (𝑥2); [𝑥2|𝑦2]

**ارث‌بری:**[`MathDelimiter`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)

نوع MathDelimiter اعضای زیر را ارائه می‌دهد:

## سازنده‌ها

| سازنده | توضیح |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | MathDelimiter را با عنصر مشخص به‌عنوان آرگومان پایهٔ تک مقداردهی اولیه می‌کند |

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`arguments`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/arguments/) | یک یا چند عنصر ریاضی که با کاراکترهای جداکننده جدا شده‌اند |
| [`beginning_character`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Delimiter Beginning Character کاراکتر شروع یا باز شدن جداکننده را مشخص می‌کند. <br/>            جداکننده‌های ریاضی کاراکترهای پوشاننده‌ای مانند پرانتز، براکت و کروشه هستند.<br/>            مقدار پیش‌فرض: '('. |
| [`separator_character`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/separator_character/) | Delimiter Separator Character کاراکتری را که آرگومان‌ها را در شیء جداکننده جدا می‌کند، مشخص می‌کند. <br/>            مقدار پیش‌فرض: '\|'. |
| [`ending_character`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/ending_character/) | Delimiter Ending Character کاراکتر پایان یا بسته شدن جداکننده را مشخص می‌کند. <br/>            جداکننده‌های ریاضی کاراکترهای پوشاننده‌ای مانند پرانتز، براکت و کروشه هستند.<br/>            مقدار پیش‌فرض: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | مشخص می‌کند که BeginningCharacter، SeparatorCharacter، EndingCharacter رشد کنند.<br/>            وقتی مقدار true باشد، جداکننده‌ها به‌صورت عمودی بزرگ می‌شوند تا با ارتفاع عملوند مطابقت داشته باشند.<br/>            مقدار پیش‌فرض true |
| [`delimiter_shape`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | شکل جداکننده‌ها در شیء جداکننده را تعیین می‌کند. <br/>            وقتی مقدار MathDelimiterShape.Centered باشد، جداکننده‌ها حول محور ریاضی متن متمرکز می‌شوند و همچنان برای پر کردن تمام ارتفاع محتوا تنظیم می‌شوند.<br/>            وقتی مقدار MathDelimiterShape.Match باشد، ارتفاع و شکل آن‌ها دقیقاً مطابق محتوا تنظیم می‌شود. |

## متدها

| متد | توضیح |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | یک عنصر ریاضی را پیوست می‌کند و یک بلوک ریاضی می‌سازد |
| [`join(self, math_text)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/join/#str) | یک متن ریاضی را پیوست می‌کند و یک بلوک ریاضی می‌سازد |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | یک کسر با صورت این مقدار و مخرج مشخص ایجاد می‌کند |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/divide/#str) | یک کسر با صورت این مقدار و مخرج مشخص ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | یک کسر از نوع مشخص شده با صورت این مقدار و مخرج مشخص ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | یک کسر از نوع مشخص شده با صورت این مقدار و مخرج مشخص ایجاد می‌کند |
| [`enclose(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/enclose/#) | یک عنصر ریاضی را در پرانتز می‌نشیند |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | یک عنصر ریاضی را در کاراکترهای مشخص شده مانند پرانتز یا کاراکترهای دیگر به‌عنوان قاب می‌نشیند |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | یک تابع از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع می‌گیرد |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/function/#str) | یک تابع از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع می‌گیرد |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | تابع مشخص شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | تابع مشخص شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | تابع مشخص شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | تابع مشخص شده را با استفاده از این نمونه به‌عنوان آرگومان و آرگومان اضافهٔ مشخص می‌گیرد |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | تابع مشخص شده را با استفاده از این نمونه به‌عنوان آرگومان و آرگومان اضافهٔ مشخص می‌گیرد |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | زیرنویس ایجاد می‌کند |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | زیرنویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | بالانویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | بالانویس ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت راست می‌سازد |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | زیرنویس و بالانویس را در سمت راست می‌سازد |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت چپ می‌سازد |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | زیرنویس و بالانویس را در سمت چپ می‌سازد |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | ریشهٔ ریاضی از درجهٔ داده‌شده را از آرگومان مشخص شده محاسبه می‌کند. |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/radical/#str) | ریشهٔ ریاضی از درجهٔ داده‌شده را از آرگومان مشخص شده محاسبه می‌کند. |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | حد بالا را می‌گیرد |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | حد بالا را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | حد پایین را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | حد پایین را می‌گیرد |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | یک عملگر N-ary ایجاد می‌کند |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | یک عملگر N-ary ایجاد می‌کند |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | انتگرال را می‌گیرد |
| [`integral(self, integral_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | انتگرال را بدون حدها می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | انتگرال را می‌گیرد |
| [`group(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/group/#) | این عنصر را با استفاده از آکولاد پایین در یک گروه می‌گذارد |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | این عنصر را با استفاده از کاراکتر گروه‌بندی مانند آکولاد پایین یا کاراکتر دیگر در یک گروه می‌گذارد |
| [`to_border_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | این عنصر را در یک جعبه-حاشیه می‌گذارد |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | این عنصر را در یک جعبه-حاشیه می‌گذارد |
| [`to_math_array(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | در یک آرایهٔ عمودی قرار می‌دهد |
| [`accent(self, accent_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/accent/#char) | یک علامت شِد (کاراکتر بالای این عنصر) تنظیم می‌کند |
| [`overbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/overbar/#) | یک خط افقی بالای این عنصر تنظیم می‌کند |
| [`underbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/underbar/#) | یک خط افقی پایین این عنصر تنظیم می‌کند |
| [`to_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/to_box/#) | این عنصر را در یک جعبهٔ غیر‌دیداری (گروه‌بندی منطقی) <br/>            که برای گروه‌بندی مؤلفه‌های یک معادله یا سایر نمونه‌های متن ریاضی استفاده می‌شود، می‌گذارد.<br/>            یک شیء درون جعبه می‌تواند (به عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز عمل کند، <br/>            به‌عنوان نقطهٔ شکست خط خدمت کند، یا به‌گونه‌ای گروه‌بندی شود که اجازهٔ شکست خط داخل آن نشود. |
| [`delimit(self, separator_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/delimit/#char) | آرگومان‌ها را با کاراکتر جداکنندهٔ مشخص‌شده جدا می‌کند |
| [`get_children(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/get_children/#) | دریافت فرزندان عنصر |

### موارد مرتبط
* کلاس [`MathDelimiter`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter)
* کلاس [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)