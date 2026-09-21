---
title: MathElementBase class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.mathtext/mathelementbase/
---
## کلاس MathElementBase

کلاس پایه برای IMathElement با پیاده‌سازی برخی متدها که برای تمام کلاس‌های ارث‌بری مشترک هستند
برای استفاده داخلی فقط. کلاس ارث‌بری باید IMathElement باشد.

نوع MathElementBase اعضای زیر را نمایش می‌دهد:

## متدها

| متد | توضیح |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/join/#imathelement) | یک عنصر ریاضی را به هم می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| [`join(self, math_text)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/join/#str) | یک متن ریاضی را به هم می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/divide/#imathelement) | کسر با این صورت و مخرج مشخص ایجاد می‌کند |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/divide/#str) | کسر با این صورت و مخرج مشخص ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/divide/#imathelement-mathfractiontypes) | کسر از نوع مشخص با این صورت و مخرج مشخص ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/divide/#str-mathfractiontypes) | کسر از نوع مشخص با این صورت و مخرج مشخص ایجاد می‌کند |
| [`enclose(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/enclose/#) | یک عنصر ریاضی را در پرانتز می‌گیرد |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/enclose/#char-char) | یک عنصر ریاضی را در کاراکترهای مشخص (مانند پرانتز یا کاراکترهای دیگر) به عنوان چارچوب می‌گیرد |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/function/#imathelement) | تابعی از یک آرگومان می‌گیرد که این نمونه به عنوان نام تابع استفاده می‌شود |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/function/#str) | تابعی از یک آرگومان می‌گیرد که این نمونه به عنوان نام تابع استفاده می‌شود |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#imathelement) | تابع مشخصی را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#str) | تابع مشخصی را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsofoneargument) | تابع مشخصی را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | تابع مشخصی را می‌گیرد که این نمونه به عنوان آرگومان و یک آرگومان اضافه مشخص استفاده می‌شود |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsoftwoarguments-str) | تابع مشخصی را می‌گیرد که این نمونه به عنوان آرگومان و یک آرگومان اضافه مشخص استفاده می‌شود |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/set_subscript/#imathelement) | زیرنویس ایجاد می‌کند |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/set_subscript/#str) | زیرنویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/set_superscript/#imathelement) | بالانویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/set_superscript/#str) | بالانویس ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_right/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_right/#str-str) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_left/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_left/#str-str) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/radical/#imathelement) | ریشه ریاضی با درجهٔ داده شده را از آرگومان مشخص تعیین می‌کند. |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/radical/#str) | ریشه ریاضی با درجهٔ داده شده را از آرگومان مشخص تعیین می‌کند. |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/set_upper_limit/#imathelement) | حد بالا را می‌گیرد |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/set_upper_limit/#str) | حد بالا را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/set_lower_limit/#imathelement) | حد پایین را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/set_lower_limit/#str) | حد پایین را می‌گیرد |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/nary/#mathnaryoperatortypes-imathelement-imathelement) | یک عملگر N-تایی ایجاد می‌کند |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/nary/#mathnaryoperatortypes-str-str) | یک عملگر N-تایی ایجاد می‌کند |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-imathelement-imathelement) | انتگرال را می‌گیرد |
| [`integral(self, integral_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes) | انتگرال را بدون حدها می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-str-str-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-str-str) | انتگرال را می‌گیرد |
| [`group(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/group/#) | این عنصر را با استفاده از یک آکولاد سفلی در یک گروه قرار می‌دهد |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/group/#char-mathtopbotpositions-mathtopbotpositions) | این عنصر را با استفاده از یک کاراکتر گروه‌بندی مانند آکولاد سفلی یا کاراکتر دیگر در یک گروه قرار می‌دهد |
| [`to_border_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/to_border_box/#) | این عنصر را در یک جعبه مرزی قرار می‌دهد |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | این عنصر را در یک جعبه مرزی قرار می‌دهد |
| [`to_math_array(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/to_math_array/#) | در یک آرایه عمودی قرار می‌دهد |
| [`accent(self, accent_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/accent/#char) | یک علامت اکسنت (کاراکتر بر بالای این عنصر) تنظیم می‌کند |
| [`overbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/overbar/#) | یک خط بر بالای این عنصر تنظیم می‌کند |
| [`underbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/underbar/#) | یک خط بر پایین این عنصر تنظیم می‌کند |
| [`to_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/to_box/#) | این عنصر را در یک جعبه غیر‌دیداری (گروه‌بندی منطقی) قرار می‌دهد <br/>            که برای گروه‌بندی مؤلفه‌های یک معادله یا نمونه دیگر متن ریاضی استفاده می‌شود.<br/>            یک شیء جعبه‌بندی‌شده می‌تواند (به عنوان مثال) به عنوان شبیه‌ساز عملگر با یا بدون نقطه تراز استفاده شود، <br/>            به عنوان نقطه شکست خط عمل کند، یا به گونه‌ای گروه‌بندی شود که درون آن اجازه شکست خط داده نشود. |
| [`get_children(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase/get_children/#) |  |

### موارد مرتبط
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)