---
title: MathAccent class
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides.mathtext/mathaccent/
---
## کلاس MathAccent

عملکرد لهجه را مشخص می‌کند که از یک پایه و یک علامت ترکیبی تشدید تشکیل شده است.  
            مثال: 𝑎́

**وراثت:**[`MathAccent`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent) → [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)

نوع MathAccent اعضای زیر را عرضه می‌کند:

## سازنده‌ها

| سازنده | توضیح |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/__init__/#imathelement) | یک لهجه ریاضی ایجاد می‌کند که به یک عنصر ریاضی مشخص اعمال می‌شود با مقدار پیش‌فرض کاراکتر لهجه |
| [`__init__(self, element, accent_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/__init__/#imathelement-char) | یک لهجه ریاضی ایجاد می‌کند که به یک عنصر ریاضی مشخص اعمال می‌شود |

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`base`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/base/) | آرگونی که لهجه به آن اعمال شده است |
| [`character`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/character/) | کاراکتر لهجه<br/>            مقدار باید در بازه (U+0300–U+036F) یا (U+20D0–U+20EF) باشد<br/>            مقدار پیش‌فرض: ترکیبی قوس‌دار (U+0302) |

## متدها

| متد | توضیح |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/join/#imathelement) | یک عنصر ریاضی را ترکیب می‌کند و یک بلوک ریاضی می‌سازد |
| [`join(self, math_text)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/join/#str) | متن ریاضی را ترکیب می‌کند و یک بلوک ریاضی می‌سازد |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/divide/#imathelement) | کسر را با این صورت و مخرج مشخص می‌سازد |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/divide/#str) | کسر را با این صورت و مخرج مشخص می‌سازد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/divide/#imathelement-mathfractiontypes) | کسر از نوع مشخص را با این صورت و مخرج مشخص می‌سازد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/divide/#str-mathfractiontypes) | کسر از نوع مشخص را با این صورت و مخرج مشخص می‌سازد |
| [`enclose(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/enclose/#) | یک عنصر ریاضی را در پرانتز می‌گیرد |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/enclose/#char-char) | یک عنصر ریاضی را در کاراکترهای مشخص مانند پرانتز یا دیگر کاراکترها به‌عنوان قاب می‌گیرد |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/function/#imathelement) | یک تابع از یک آرگومان می‌گیرد که این نمونه به‌عنوان نام تابع استفاده می‌شود |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/function/#str) | یک تابع از یک آرگومان می‌گیرد که این نمونه به‌عنوان نام تابع استفاده می‌شود |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/as_argument_of_function/#imathelement) | تابع مشخصی را می‌گیرد که این نمونه به‌عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/as_argument_of_function/#str) | تابع مشخصی را می‌گیرد که این نمونه به‌عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsofoneargument) | تابع مشخصی را می‌گیرد که این نمونه به‌عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | تابع مشخصی را می‌گیرد که این نمونه به‌عنوان آرگومان و آرگومان اضافه‌ٔ مشخص استفاده می‌شود |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-str) | تابع مشخصی را می‌گیرد که این نمونه به‌عنوان آرگومان و آرگومان اضافه‌ٔ مشخص استفاده می‌شود |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/set_subscript/#imathelement) | زیرنویس ایجاد می‌کند |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/set_subscript/#str) | زیرنویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/set_superscript/#imathelement) | بالانویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/set_superscript/#str) | بالانویس ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#str-str) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#str-str) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/radical/#imathelement) | ریشه ریاضی از درجهٔ داده‌شده را از آرگومان مشخص‌شده محاسبه می‌کند. |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/radical/#str) | ریشه ریاضی از درجهٔ داده‌شده را از آرگومان مشخص‌شده محاسبه می‌کند. |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/set_upper_limit/#imathelement) | حد بالا را می‌گیرد |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/set_upper_limit/#str) | حد بالا را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/set_lower_limit/#imathelement) | حد پایین را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/set_lower_limit/#str) | حد پایین را می‌گیرد |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-imathelement-imathelement) | عملگر N-آری ایجاد می‌کند |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-str-str) | عملگر N-آری ایجاد می‌کند |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement) | انتگرال را می‌گیرد |
| [`integral(self, integral_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes) | انتگرال بدون حدود را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str) | انتگرال را می‌گیرد |
| [`group(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/group/#) | این عنصر را در یک گروه با استفاده از کروشهٔ پایین قرار می‌دهد |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/group/#char-mathtopbotpositions-mathtopbotpositions) | این عنصر را در یک گروه با استفاده از کاراکتر گروه‌بندی مانند کروشهٔ پایین یا کاراکتر دیگر قرار می‌دهد |
| [`to_border_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/to_border_box/#) | این عنصر را در یک جعبه مرزی قرار می‌دهد |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | این عنصر را در یک جعبه مرزی قرار می‌دهد |
| [`to_math_array(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/to_math_array/#) | در یک آرایه عمودی قرار می‌دهد |
| [`accent(self, accent_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/accent/#char) | علامت لهجه‌ای تنظیم می‌کند (کاراکتری در بالای این عنصر) |
| [`overbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/overbar/#) | یک خط در بالای این عنصر تنظیم می‌کند |
| [`underbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/underbar/#) | یک خط در پایین این عنصر تنظیم می‌کند |
| [`to_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/to_box/#) | این عنصر را در یک جعبه غیر-نمایشی (گروه‌بندی منطقی) <br/>            که برای گروه‌بندی اجزای یک معادله یا سایر نمونه‌های متن ریاضی استفاده می‌شود.<br/>            یک شیء جعبه‌ای می‌تواند (به عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز عمل کند، <br/>            به‌عنوان نقطهٔ شکست خط عمل کند، یا به‌ گونه‌ای گروه‌بندی شود که اجازهٔ شکست خط درون آن را ندهد. |
| [`get_children(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent/get_children/#) | دریافت عناصر فرزند |

### مراجع دیگر
* کلاس [`MathAccent`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent)
* کلاس [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)