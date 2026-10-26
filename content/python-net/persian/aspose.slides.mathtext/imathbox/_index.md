---
title: IMathBox class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.mathtext/imathbox/
---
## کلاس IMathBox

مشخص می‌کند بسته‌بندی منطقی (پکیجینگ) عنصر ریاضی.

    به‌عنوان مثال، یک شی بسته می‌تواند به عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز عمل کند،
            به‌عنوان نقطهٔ شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که درون آن اجازهٔ شکست خط داده نشود.
            به‌عنوان مثال، عملگر "==" باید بسته‌بندی شود تا از شکست خط جلوگیری شود.

نوع IMathBox اعضای زیر را در اختیار می‌گذارد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`base`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/base/) | آرگومان پایه |
| [`operator_emulator`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/operator_emulator/) | شبیه‌ساز عملگر.<br/>            هنگامی که مقدار true باشد، جعبه و محتویات آن مانند یک عملگر واحد رفتار می‌کنند و خصوصیات یک عملگر را به ارث می‌برند. <br/>            این به این معنی است که، به عنوان مثال، کاراکتر می‌تواند به عنوان نقطه‌ای برای شکست خط عمل کند و می‌تواند با سایر عملگرها تراز شود.<br/>            شبیه‌سازهای عملگر اغلب زمانی استفاده می‌شوند که یک یا چند گلیف برای تشکیل یک عملگر ترکیب شوند، مانند '=='.<br/>            مقدار پیش‌فرض: false |
| [`no_break`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/no_break/) | بدون شکست.<br/>            این ویژگی ویژگی «قابل شکست نیست» را بر جعبهٔ شیء تعیین می‌کند. هنگامی که مقدار true باشد، هیچ شکست خطی درون جعبه رخ نمی‌دهد.<br/>            این می‌تواند برای شبیه‌سازهای عملگر که بیش از یک عملگر دودویی شامل می‌شوند مهم باشد.<br/>            زمانی که این عنصر مشخص نشود، شکست‌ها می‌توانند درون جعبه رخ دهند.<br/>            پیش‌فرض: true |
| [`differential`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/differential/) | مشتق.<br/>            هنگامی که مقدار true باشد، جعبه به‌عنوان یک مشتق عمل می‌کند (به عنوان مثال، 𝑑𝑥 در یک انتگرال) و<span> </span>فاصله افقی مناسب برای مشتق ریاضی را دریافت می‌کند.<br/>            پیش‌فرض: false |
| [`alignment_point`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/alignment_point/) | هنگامی که مقدار true باشد، این شبیه‌ساز عملگر به عنوان یک نقطهٔ تراز عمل می‌کند؛ یعنی<br/>            نقاط تراز تعیین‌شده در معادلات دیگر می‌توانند با آن تراز شوند.<br/>            پیش‌فرض: false |
| [`explicit_break`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/explicit_break/) | شکست صریح مشخص می‌کند آیا در ابتدای شی Box یک شکست خط وجود دارد یا خیر،<br/>            به‌طوری که خط در ابتدای شی جعبه به‌خط جدید برود.<br/>            شمارهٔ عملگر در خط قبلی متن ریاضی که باید<br/>            به‌عنوان نقطهٔ تراز برای خط فعلی متن ریاضی استفاده شود<br/>            مقادیر ممکن: 1..255<br/>            پیش‌فرض: 0 (بدون شکست صریح) |

## متدها

| متد | توضیح |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathbox/to_box/#) |  |

### موارد مرتبط
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)