---
title: MathGroupingCharacter class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.mathtext/mathgroupingcharacter/
---
## کلاس MathGroupingCharacter

نماد گروه‌بندی را بالای یا زیر یک عبارت مشخص می‌کند، معمولاً برای برجسته‌سازی رابطه بین عناصر

**ارث‌بری:**[`MathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter) → [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)

نوع MathGroupingCharacter اعضای زیر را نمایش می‌دهد:

## سازنده‌ها

| سازنده | شرح |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement) | یک نمونه جدید از کلاس MathGroupingCharacter را مقداردهی اولیه می‌کند <br/>            با کاراکتر گروه‌بندی پیش‌فرض U+23DF (پرانتز منحنی پایین) |
| [`__init__(self, element, character, position, vertical_justification)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement-char-mathtopbotpositions-mathtopbotpositions) | یک نمونه جدید از کلاس MathGroupingCharacter را مقداردهی اولیه می‌کند. |

## ویژگی‌ها

| ویژگی | شرح |
| :- | :- |
| [`base`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/base/) | آرگومان پایه |
| [`character`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/character/) | کاراکتر گروه‌بندی<br/>            مقدار پیش‌فرض: U+23DF (پرانتز منحنی پایین) |
| [`position`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/position/) | موقعیت کاراکتر گروه‌بندی.<br/>            پیش‌فرض: Bottom |
| [`vertical_justification`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/vertical_justification/) | تراز عمودی کاراکتر گروه.<br/>            توجیه تراز شیء نسبت به خط پایه را مشخص می‌کند.<br/>            برای مثال، هنگامی که کاراکتر گروه بالای شیء قرار دارد، <br/>            VerticalJustification مقدار Top به این معنی است که بالای شیء بر خط پایه قرار می‌گیرد؛<br/>            وقتی VerticalJustification برابر Bottom باشد، پایین شیء بر خط پایه قرار می‌گیرد<br/>            پیش‌فرض: Bottom برای Position=Top و Top برای Position=Bottom |

## متدها

| متد | شرح |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/join/#imathelement) | یک عنصر ریاضی را ترکیب می‌کند و یک بلوک ریاضی تشکیل می‌دهد |
| [`join(self, math_text)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/join/#str) | یک متن ریاضی را ترکیب می‌کند و یک بلوک ریاضی تشکیل می‌دهد |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement) | کسر را با این صورت و مخرج مشخص ایجاد می‌کند |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/divide/#str) | کسر را با این صورت و مخرج مشخص ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement-mathfractiontypes) | کسر از نوع مشخص شده را با این صورت و مخرج مشخص ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/divide/#str-mathfractiontypes) | کسر از نوع مشخص شده را با این صورت و مخرج مشخص ایجاد می‌کند |
| [`enclose(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/enclose/#) | یک عنصر ریاضی را در پرانتز می‌گیرد |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/enclose/#char-char) | یک عنصر ریاضی را در کاراکترهای مشخص مانند پرانتز یا سایر کاراکترها به عنوان قاب می‌گیرد |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/function/#imathelement) | تابعی از یک آرگومان می‌گیرد که نام آن با این نمونه است |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/function/#str) | تابعی از یک آرگومان می‌گیرد که نام آن با این نمونه است |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#imathelement) | تابعی را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#str) | تابعی را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) | تابعی را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | تابعی را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود و آرگومان اضافی مشخص شده را دارد |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | تابعی را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود و آرگومان اضافی مشخص شده را دارد |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#imathelement) | زیرنویس ایجاد می‌کند |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#str) | زیرنویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#imathelement) | بالانویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#str) | بالانویس ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/radical/#imathelement) | ریشه ریاضی از درجه داده شده را از آرگومان مشخص شده تعیین می‌کند. |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/radical/#str) | ریشه ریاضی از درجه داده شده را از آرگومان مشخص شده تعیین می‌کند. |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#imathelement) | حد بالا را می‌گیرد |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#str) | حد بالا را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#imathelement) | حد پایین را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#str) | حد پایین را می‌گیرد |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) | اپراتور N-ارگی ایجاد می‌کند |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) | اپراتور N-ارگی ایجاد می‌کند |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) | انتگرال را می‌گیرد |
| [`integral(self, integral_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes) | انتگرال را بدون حدها می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str) | انتگرال را می‌گیرد |
| [`group(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/group/#) | این عنصر را در یک گروه با استفاده از پرانتز منحنی پایین قرار می‌دهد |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) | این عنصر را در یک گروه با استفاده از کاراکتر گروه‌بندی مانند پرانتز منحنی پایین یا دیگری قرار می‌دهد |
| [`to_border_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#) | این عنصر را در یک جعبه حاشیه‌ای قرار می‌دهد |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | این عنصر را در یک جعبه حاشیه‌ای قرار می‌دهد |
| [`to_math_array(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/to_math_array/#) | در یک آرایه عمودی قرار می‌دهد |
| [`accent(self, accent_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/accent/#char) | علامت تأکید (یک کاراکتر در بالای این عنصر) را تنظیم می‌کند |
| [`overbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/overbar/#) | نوار در بالای این عنصر را تنظیم می‌کند |
| [`underbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/underbar/#) | نوار در پایین این عنصر را تنظیم می‌کند |
| [`to_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/to_box/#) | این عنصر را در یک جعبه غیر‌چشم‌پذیر (گروه‌بندی منطقی) قرار می‌دهد <br/>            که برای گروه‌بندی مؤلفه‌های یک معادله یا سایر نمونه‌های متن ریاضی استفاده می‌شود.<br/>            یک شیء درون جعبه می‌تواند (به عنوان مثال) به عنوان شبیه‌ساز عملگر با یا بدون نقطه تراز عمل کند، <br/>            به عنوان نقطه شکستن خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که شکست خط درون آن اجازه داده نشود. |
| [`get_children(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter/get_children/#) | دریافت عناصر فرزند |

### موارد مرتبط
* کلاس [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)
* کلاس [`MathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/mathgroupingcharacter)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)