---
title: IMathBox class
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.mathtext/imathbox/
---
## فئة IMathBox

يحدد التغليف المنطقي (التعبئة) للعنصر الرياضي. على سبيل المثال، يمكن أن يكون الكائن المُغلق محاكيًا للمشغل مع أو بدون نقطة محاذاة، أو يعمل كنقطة فاصل سطر، أو يُجمع بحيث لا يسمح بفواصل الأسطر داخلَه. على سبيل المثال، يجب تغليف المشغل "==" لمنع فواصل الأسطر.

The IMathBox type exposes the following members:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`base`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/base/) | الحجة الأساسية |
| [`operator_emulator`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/operator_emulator/) | محاكي المشغل.<br/>            عند true، يصبح الصندوق ومحتوياته كمشغل واحد وتورث خصائص المشغل.<br/>            هذا يعني، على سبيل المثال، أن الحرف يمكن أن يكون نقطة لفاصل السطر ويمكن محاذاته إلى مشغلات أخرى.<br/>            غالبًا ما تُستخدم محاكيات المشغل عندما يتحد أحد أو أكثر من الرموز لتكوين مشغل، مثل '=='.<br/>            القيمة الافتراضية: false |
| [`no_break`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/no_break/) | بدون فاصل.<br/>            تحدد هذه الخاصية خاصية "unbreakable" على صندوق الكائن. عند true، لا يمكن حدوث فواصل أسطر داخل الصندوق.<br/>            قد يكون هذا مهمًا لمحاكيات المشغل التي تتألف من أكثر من مشغل ثنائي. <br/>            عند عدم تحديد هذا العنصر، يمكن حدوث فواصل داخل الصندوق.<br/>            القيمة الافتراضية: true |
| [`differential`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/differential/) | تفاضل.<br/>            عند true، يعمل الصندوق كتفاضل (مثال، 𝑑𝑥 في التكامل)، ويتلقى التباعد الأفقي المناسب<br/>            للمسافة الأفقية للتفاضل الرياضي.<br/>            القيمة الافتراضية: false |
| [`alignment_point`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/alignment_point/) | عند true، يعمل محاكي المشغل كنقطة محاذاة؛ أي أن<br/>            نقاط المحاذاة المحددة في معادلات أخرى يمكن محاكاتها معه.<br/>            القيمة الافتراضية: false |
| [`explicit_break`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/explicit_break/) | الفاصل الصريح يحدد ما إذا كان هناك فاصل سطر في بداية كائن Box،<br/>            وبالتالي يلتف السطر عند بداية كائن الصندوق.<br/>            يحدد عدد المشغل في السطر السابق من النص الرياضي الذي يجب<br/>            يُستخدم كنقطة محاذاة للسطر الحالي من النص الرياضي<br/>            القيم الممكنة: 1..255<br/>            القيمة الافتراضية: 0 (لا فاصل صريح) |

## الأساليب

| الطريقة | الوصف |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathbox/to_box/#) |  |

### انظر أيضًا
* الوحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* المكتبة [`Aspose.Slides`](/slides/python-net)