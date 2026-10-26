---
title: MathRadical class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.mathtext/mathradical/
---
## کلاس MathRadical

عملکرد رادیکال را مشخص می‌کند که شامل پایه و درجهٔ اختیاری است.
مثال شی رادیکال √𝑥 است.

**وراثت:**[`MathRadical`](/slides/python-net/fa/aspose.slides.mathtext/mathradical) → [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)

نوع MathRadical اعضای زیر را در معرض می‌گذارد:

## سازنده‌ها

| سازنده | توضیح |
| :- | :- |
| [`__init__(self, base_argument, degree_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/__init__/#imathelement-imathelement) | یک نمونه جدید از کلاس MathRadical را مقداردهی اولیه می‌کند. |

## خواص

| خاصیت | توضیح |
| :- | :- |
| [`base`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/base/) | آرگومان پایه |
| [`degree`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/degree/) | آرگومان درجه |
| [`hide_degree`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/hide_degree/) | مخفی‌سازی درجه<br/>            وقتی true باشد، درجه نشان داده نمی‌شود، همانند √𝑥 |

## متدها

| متد | توضیح |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/join/#imathelement) | یک عنصر ریاضی را به هم پیوست می‌کند و یک بلوک ریاضی می‌سازد |
| [`join(self, math_text)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/join/#str) | متن ریاضی را به هم پیوست می‌کند و یک بلوک ریاضی می‌سازد |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/divide/#imathelement) | کسر با صورت این و مخرج مشخص شده ایجاد می‌کند |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/divide/#str) | کسر با صورت این و مخرج مشخص شده ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/divide/#imathelement-mathfractiontypes) | کسر از نوع مشخص شده با صورت این و مخرج مشخص شده ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/divide/#str-mathfractiontypes) | کسر از نوع مشخص شده با صورت این و مخرج مشخص شده ایجاد می‌کند |
| [`enclose(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/enclose/#) | یک عنصر ریاضی را در پرانتز می‌گذارد |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/enclose/#char-char) | یک عنصر ریاضی را در کاراکترهای مشخص شده مانند پرانتز یا کاراکترهای دیگر به عنوان قاب می‌گذارد |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/function/#imathelement) | یک تابع از یک آرگومان می‌گیرد که این نمونه را به عنوان نام تابع استفاده می‌کند |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/function/#str) | یک تابع از یک آرگومان می‌گیرد که این نمونه را به عنوان نام تابع استفاده می‌کند |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/as_argument_of_function/#imathelement) | تابع مشخص شده‌ای را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/as_argument_of_function/#str) | تابع مشخص شده‌ای را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/as_argument_of_function/#mathfunctionsofoneargument) | تابع مشخص شده‌ای را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | تابع مشخص شده‌ای را می‌گیرد که این نمونه به عنوان آرگومان و یک آرگومان اضافی مشخص استفاده می‌شود |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/as_argument_of_function/#mathfunctionsoftwoarguments-str) | تابع مشخص شده‌ای را می‌گیرد که این نمونه به عنوان آرگومان و یک آرگومان اضافی مشخص استفاده می‌شود |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/set_subscript/#imathelement) | زیرنویس ایجاد می‌کند |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/set_subscript/#str) | زیرنویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/set_superscript/#imathelement) | بالانویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/set_superscript/#str) | بالانویس ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_right/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_right/#str-str) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_left/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_left/#str-str) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/radical/#imathelement) | ریشه ریاضی با درجهٔ داده شده از آرگومان مشخص شده را تعیین می‌کند. |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/radical/#str) | ریشه ریاضی با درجهٔ داده شده از آرگومان مشخص شده را تعیین می‌کند. |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/set_upper_limit/#imathelement) | حد بالا را می‌گیرد |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/set_upper_limit/#str) | حد بالا را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/set_lower_limit/#imathelement) | حد پایین را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/set_lower_limit/#str) | حد پایین را می‌گیرد |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/nary/#mathnaryoperatortypes-imathelement-imathelement) | یک عملگر N-ارگی ایجاد می‌کند |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/nary/#mathnaryoperatortypes-str-str) | یک عملگر N-ارگی ایجاد می‌کند |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-imathelement-imathelement) | انتگرال را می‌گیرد |
| [`integral(self, integral_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes) | انتگرال را بدون حدها می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-str-str-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-str-str) | انتگرال را می‌گیرد |
| [`group(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/group/#) | این عنصر را در گروهی با استفاده از آکولاد پایین قرار می‌دهد |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/group/#char-mathtopbotpositions-mathtopbotpositions) | این عنصر را در گروهی با استفاده از کاراکتر گروه‌بندی مانند آکولاد پایین یا دیگر قرار می‌دهد |
| [`to_border_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/to_border_box/#) | این عنصر را در جعبهٔ حاشیه‌ای قرار می‌دهد |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | این عنصر را در جعبهٔ حاشیه‌ای قرار می‌دهد |
| [`to_math_array(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/to_math_array/#) | در یک آرایهٔ عمودی قرار می‌دهد |
| [`accent(self, accent_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/accent/#char) | علامت لهجه (کاراکتری در بالای این عنصر) تنظیم می‌کند |
| [`overbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/overbar/#) | یک خط بر روی بالای این عنصر تنظیم می‌کند |
| [`underbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/underbar/#) | یک خط بر روی پایین این عنصر تنظیم می‌کند |
| [`to_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/to_box/#) | این عنصر را در یک جعبهٔ غیر‌نمایشی (گروه‌بندی منطقی) قرار می‌دهد <br/>            که برای گروه‌بندی مؤلفه‌های یک معادله یا نمونهٔ دیگری از متن ریاضی استفاده می‌شود.<br/>            یک شیء جعبه‌شده می‌تواند (به عنوان مثال) به عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز عمل کند، <br/>            به عنوان نقطهٔ شکست خط عمل کند، یا به صورت گروه‌بندی شود به طوری که شکست خط درون آن مجاز نباشد. |
| [`get_children(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathradical/get_children/#) | دریافت عناصر فرزند |

### موارد مرتبط
* کلاس [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)
* کلاس [`MathRadical`](/slides/python-net/fa/aspose.slides.mathtext/mathradical)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)