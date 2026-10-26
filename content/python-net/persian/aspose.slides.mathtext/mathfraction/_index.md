---
title: MathFraction class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.mathtext/mathfraction/
---
## MathFraction کلاس

شیء کسر را مشخص می‌کند که از صورت و مخرج تشکیل شده و توسط یک خط کسر از یکدیگر جدا می‌شوند.
خط کسر می‌تواند افقی یا قطری باشد، بسته به ویژگی‌های کسر.
شیء کسر همچنین برای نمایاندن تابع پشته استفاده می‌شود که یک عنصر را بالای عنصر دیگر قرار می‌دهد، بدون خط کسر.

**ارث‌بری:**[`MathFraction`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction) → [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)

نوع MathFraction اعضای زیر را در اختیار می‌گذارد:

## سازنده‌ها

| سازنده | توضیح |
| :- | :- |
| [`__init__(self, numerator, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement-mathfractiontypes) | MathFraction را با صورت، مخرج و نوع مشخص‌شده مقداردهی اولیه می‌کند |
| [`__init__(self, numerator, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement) | یک MathFraction از نوع 'Bar' را با صورت و مخرج مشخص مقداردهی می‌کند |

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`fraction_type`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/fraction_type/) | نوع کسر<br/>            پیش‌فرض: Bar |
| [`numerator`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/numerator/) | صورت |
| [`denominator`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/denominator/) | مخرج |

## متدها

| متد | توضیح |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/join/#imathelement) | یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| [`join(self, math_text)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/join/#str) | یک متن ریاضی را می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/divide/#imathelement) | یک کسر با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/divide/#str) | یک کسر با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/divide/#imathelement-mathfractiontypes) | یک کسر از نوع مشخص‌شده با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/divide/#str-mathfractiontypes) | یک کسر از نوع مشخص‌شده با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| [`enclose(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/enclose/#) | یک عنصر ریاضی را داخل پرانتز می‌گیرد |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/enclose/#char-char) | یک عنصر ریاضی را در کاراکترهای مشخص‌شده مانند پرانتز یا سایر کاراکترها به‌عنوان قاب می‌گیرد |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/function/#imathelement) | یک تابع آرگومان با استفاده از این نمونه به عنوان نام تابع می‌گیرد |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/function/#str) | یک تابع آرگومان با استفاده از این نمونه به عنوان نام تابع می‌گیرد |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/as_argument_of_function/#imathelement) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/as_argument_of_function/#str) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsofoneargument) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافی می‌گیرد |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-str) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافی می‌گیرد |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/set_subscript/#imathelement) | زیرنویس ایجاد می‌کند |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/set_subscript/#str) | زیرنویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/set_superscript/#imathelement) | بالانویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/set_superscript/#str) | بالانویس ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#str-str) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#str-str) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/radical/#imathelement) | ریشهٔ ریاضی درجهٔ داده‌شده را از آرگومان مشخص‌شده محاسبه می‌کند. |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/radical/#str) | ریشهٔ ریاضی درجهٔ داده‌شده را از آرگومان مشخص‌شده محاسبه می‌کند. |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/set_upper_limit/#imathelement) | حد بالا را می‌گیرد |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/set_upper_limit/#str) | حد بالا را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/set_lower_limit/#imathelement) | حد پایین را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/set_lower_limit/#str) | حد پایین را می‌گیرد |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-imathelement-imathelement) | یک عامل N-ary ایجاد می‌کند |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-str-str) | یک عامل N-ary ایجاد می‌کند |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement) | انتگرال را می‌گیرد |
| [`integral(self, integral_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes) | انتگرال را بدون حدود می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str) | انتگرال را می‌گیرد |
| [`group(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/group/#) | این عنصر را با استفاده از آکولاد پایین به یک گروه می‌گذارد |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/group/#char-mathtopbotpositions-mathtopbotpositions) | این عنصر را با استفاده از کاراکتر گروه‌بندی مانند آکولاد پایین یا دیگر کاراکترها به یک گروه می‌گذارد |
| [`to_border_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/to_border_box/#) | این عنصر را در یک جعبه‌مرز می‌گذارد |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | این عنصر را در یک جعبه‌مرز می‌گذارد |
| [`to_math_array(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/to_math_array/#) | در یک آرایهٔ عمودی قرار می‌دهد |
| [`accent(self, accent_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/accent/#char) | یک علامت تلفظ (کاراکتر بر بالای این عنصر) تنظیم می‌کند |
| [`overbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/overbar/#) | نوار بر بالای این عنصر را تنظیم می‌کند |
| [`underbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/underbar/#) | نوار بر پایین این عنصر را تنظیم می‌کند |
| [`to_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/to_box/#) | این عنصر را در یک جعبه غیر‌مادی (گروه‌بندی منطقی) می‌گذارد <br/>            که برای گروه‌بندی اجزای یک معادله یا سایر نمونهٔ متن ریاضی استفاده می‌شود.<br/>            یک شیء جعبه‌شده می‌تواند (به عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز عمل کند، <br/>            به‌عنوان نقطهٔ شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که شکست خط درون آن مجاز نباشد. |
| [`get_children(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction/get_children/#) | عناصر فرزند را دریافت می‌کند |

### موارد مرتبط
* کلاس [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)
* کلاس [`MathFraction`](/slides/python-net/fa/aspose.slides.mathtext/mathfraction)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)