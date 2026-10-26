---
title: MathDelimiter class
second_title: مرجع API Aspose.Slides برای پایتون از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.mathtext/mathdelimiter/
---
## کلاس MathDelimiter

شی جداکننده را مشخص می‌کند که از کاراکترهای باز و بسته (مانند پرانتز، کروشه، براکت و خطوط عمودی) تشکیل شده است و یک یا چند عنصر ریاضی داخل آن وجود دارد که با یک کاراکتر مشخص جدا شده‌اند. مثال‌ها: (𝑥2)؛ [𝑥2|𝑦2]

ارث‌بری:[`MathDelimiter`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)

نوع MathDelimiter اعضای زیر را در اختیار می‌گذارد:

## سازنده‌ها

| سازنده | توضیح |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | MathDelimiter را با عنصر مشخص به عنوان آرگومان پایهٔ تک مقداردهی اولیه می‌کند |

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`arguments`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/arguments/) | یک یا چند عنصر ریاضی که با کاراکترهای جداکننده جدا شده‌اند |
| [`beginning_character`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/beginning_character/) | کاراکتر آغاز جداکننده، کاراکتر شروع یا باز کردن جداکننده را مشخص می‌کند. <br/>            جداکننده‌های ریاضی کاراکترهای بسته‌شوندگی مانند پرانتز، براکت و کروشه هستند.<br/>            مقدار پیش‌فرض: '(' |
| [`separator_character`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/separator_character/) | کاراکتر جداکنندهٔ جداکننده، کاراکتری که آرگومان‌ها را در شیء جداکننده جدا می‌کند را مشخص می‌کند. <br/>            مقدار پیش‌فرض: '\|' |
| [`ending_character`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/ending_character/) | کاراکتر پایان جداکننده، کاراکتر بسته یا پایان جداکننده را مشخص می‌کند. <br/>            جداکننده‌های ریاضی کاراکترهای بسته‌شوندگی مانند پرانتز، براکت و کروشه هستند.<br/>            مقدار پیش‌فرض: ')' |
| [`grow_to_match_operand_height`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | رشد کاراکترهای BeginningCharacter، SeparatorCharacter، EndingCharacter را مشخص می‌کند<br/>            وقتی مقدار true باشد، جداکننده‌ها به صورت عمودی رشد می‌کنند تا ارتفاع عملوند آن‌ها را مطابقت دهند.<br/>            مقدار پیش‌فرض true است |
| [`delimiter_shape`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | شکل جداکننده‌ها در شیء جداکننده را مشخص می‌کند. <br/>            وقتی مقدار MathDelimiterShape.Centered باشد، جداکننده‌ها حول محور ریاضی متن ریاضی متمرکز می‌شوند و همچنان به‌گونه‌ای تنظیم می‌شوند که تمام ارتفاع محتوایشان را بپوشانند.<br/>            وقتی مقدار MathDelimiterShape.Match باشد، ارتفاع و شکل آنها دقیقاً با محتوایشان منطبق می‌شود. |

## متدها

| متد | توضیح |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | یک عنصر ریاضی را ترکیب کرده و یک بلوک ریاضی تشکیل می‌دهد |
| [`join(self, math_text)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/join/#str) | یک متن ریاضی را ترکیب کرده و یک بلوک ریاضی تشکیل می‌دهد |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | یک کسر با این صورت و مخرج مشخص ایجاد می‌کند |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/divide/#str) | یک کسر با این صورت و مخرج مشخص ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | کسر از نوع مشخصی را با این صورت و مخرج مشخص ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | کسر از نوع مشخصی را با این صورت و مخرج مشخص ایجاد می‌کند |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | یک عنصر ریاضی را در کاراکترهای مشخص مانند پرانتز یا سایر کاراکترها به‌عنوان قاب می‌گیرد |
| [`enclose(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/enclose/#) | یک عنصر ریاضی را در پرانتز می‌گیرد |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | یک تابع از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع می‌گیرد |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/function/#str) | یک تابع از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع می‌گیرد |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | تابع مشخصی را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | تابع مشخصی را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | تابع مشخصی را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | تابع مشخصی را با استفاده از این نمونه به‌عنوان آرگومان و یک آرگومان اضافهٔ مشخص می‌گیرد |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | تابع مشخصی را با استفاده از این نمونه به‌عنوان آرگومان و یک آرگومان اضافهٔ مشخص می‌گیرد |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | زیرنویس ایجاد می‌کند |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | زیرنویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | بالانویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | بالانویس ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | ریشهٔ ریاضی درجهٔ داده شده را از آرگومان مشخص شده تعیین می‌کند. |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/radical/#str) | ریشهٔ ریاضی درجهٔ داده شده را از آرگومان مشخص شده تعیین می‌کند. |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | حد بالا را می‌گیرد |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | حد بالا را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | حد پایین را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | حد پایین را می‌گیرد |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | یک عملگر N-ارگی ایجاد می‌کند |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | یک عملگر N-ارگی ایجاد می‌کند |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | انتگرال را می‌گیرد |
| [`integral(self, integral_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | انتگرال را بدون حدها می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | انتگرال را می‌گیرد |
| [`group(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/group/#) | این عنصر را با استفاده از کروشهٔ پایین به‌عنوان یک گروه قرار می‌دهد |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | این عنصر را با استفاده از کاراکتر گروه‌بندی مانند کروشهٔ پایین یا دیگری در یک گروه قرار می‌دهد |
| [`to_border_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | این عنصر را در یک کادر مرزی قرار می‌دهد |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | این عنصر را در یک کادر مرزی قرار می‌دهد |
| [`to_math_array(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | در یک آرایهٔ عمودی قرار می‌دهد |
| [`accent(self, accent_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/accent/#char) | علامت لهجه‌ای (کاراکتری بر بالای این عنصر) تنظیم می‌کند |
| [`overbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/overbar/#) | یک نوار در بالای این عنصر تنظیم می‌کند |
| [`underbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/underbar/#) | یک نوار در پایین این عنصر تنظیم می‌کند |
| [`to_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/to_box/#) | این عنصر را در یک جعبه غیر‌تصویری (گروه‌بندی منطقی) قرار می‌دهد <br/>            که برای گروه‌بندی مؤلفه‌های یک معادله یا نمونهٔ دیگر متن ریاضی استفاده می‌شود.<br/>            یک شیء جعبه‌دار می‌تواند (به‌عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز عمل کند، <br/>            به‌عنوان نقطهٔ شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که اجازهٔ شکست خط درون آن نشود. |
| [`delimit(self, separator_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/delimit/#char) | آرگومان‌ها را با استفاده از کاراکتر جداکنندهٔ مشخص محدود می‌کند |
| [`get_children(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter/get_children/#) | عناصر فرزند را دریافت می‌کند |

### موارد مرتبط
* کلاس [`MathDelimiter`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter)
* کلاس [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)