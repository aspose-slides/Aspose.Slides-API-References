---
title: MathBox class
second_title: Aspose.Slides للغة Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathbox/
---
## فئة MathBox

يحدد التغليف المنطقي (التعبئة) للعنصر الرياضي.
            على سبيل المثال، يمكن لكائن مُغَلَّف أن يعمل كمحاكي للمشغل مع أو بدون نقطة محاذاة،
            أو أن يكون نقطة كسر سطر، أو يتم تجميعه بحيث لا يُسمَح بحدوث كسور سطر داخله.
            على سبيل المثال، يجب تغليف المُشغل "==" لمنع كسر السطر.

**الوراثة:**[`MathBox`](/slides/python-net/ar/aspose.slides.mathtext/mathbox) → [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)

يعرض نوع MathBox الأعضاء التالية:

## المنشئات

| المنشئ | الوصف |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/__init__/#imathelement) | يقوم بتهيئة MathBox بالعنصر المحدد كمعامل |

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`base`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/base/) | الوسيط الأساسي |
| [`operator_emulator`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/operator_emulator/) | محاكي المشغل.<br/>            عندما تكون true، يتصرف الصندوق ومحتوياته كمشغل واحد ويرث خصائص المشغل.<br/>            هذا يعني، على سبيل المثال، أن الحرف يمكن أن يكون نقطة لكسر السطر ويمكن محاذاته إلى مشغلات أخرى.<br/>            غالبًا ما تُستخدم محاكيات المشغل عندما تتحد أحد أو أكثر من الرموز لتشكيل مشغل، مثل '==' .<br/>            القيمة الافتراضية: false |
| [`no_break`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/no_break/) | بدون كسر<br/>            تحدد هذه الخاصية خاصية "unbreakable" على صندوق الكائن. عندما تكون true، لا يمكن حدوث كسر سطر داخل الصندوق.<br/>            قد يكون ذلك مهمًا لمحاكيات المشغل التي تتكون من أكثر من مشغل ثنائي.<br/>            عندما لا يتم تحديد هذا العنصر، يمكن حدوث كسر داخل الصندوق.<br/>            القيمة الافتراضية: true |
| [`differential`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/differential/) | تفاضلية<br/>            عندما تكون true، يعمل الصندوق كأداة تفاضلية (مثال، 𝑑𝑥 في تكامل)، ويتلقى التباعد الأفقي المناسب للتفاضل الرياضي.<br/>            القيمة الافتراضية: false |
| [`alignment_point`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/alignment_point/) | عند true، يعمل هذا محاكي المشغل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذاتها معه.<br/>            القيمة الافتراضية: false |
| [`explicit_break`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/explicit_break/) | كسر صريح يحدد ما إذا كان هناك كسر سطر في بداية كائن Box،<br/>            بحيث يلتف السطر في بداية كائن الصندوق.<br/>            يحدد عدد المشغل في سطر النص الرياضي السابق الذي سيُستخدم كنقطة محاذاة للسطر الحالي من النص الرياضي.<br/>            القيم الممكنة: 1..255<br/>            القيمة الافتراضية: 0 (لا كسر صريح) |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/join/#imathelement) | يجمع عنصرًا رياضيًا ويشكل كتلة رياضية |
| [`join(self, math_text)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/join/#str) | يجمع نصًا رياضيًا ويشكل كتلة رياضية |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/divide/#imathelement) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/divide/#str) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/divide/#imathelement-mathfractiontypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/divide/#str-mathfractiontypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [`enclose(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/enclose/#) | يضع عنصرًا رياضيًا بين قوسين |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/enclose/#char-char) | يضع عنصرًا رياضيًا بين أحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/function/#imathelement) | يأخذ دالة لوسيط باستخدام هذا الكائن كاسم الدالة |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/function/#str) | يأخذ دالة لوسيط باستخدام هذا الكائن كاسم الدالة |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/as_argument_of_function/#imathelement) | يأخذ الدالة المحددة باستخدام هذا الكائن كوسيط |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/as_argument_of_function/#str) | يأخذ الدالة المحددة باستخدام هذا الكائن كوسيط |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsofoneargument) | يأخذ الدالة المحددة باستخدام هذا الكائن كوسيط |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | يأخذ الدالة المحددة باستخدام هذا الكائن كوسيط وإضافة وسيط إضافي محدد |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | يأخذ الدالة المحددة باستخدام هذا الكائن كوسيط وإضافة وسيط إضافي محدد |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/set_subscript/#imathelement) | ينشئ حروفًا سفلية |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/set_subscript/#str) | ينشئ حروفًا سفلية |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/set_superscript/#imathelement) | ينشئ حروفًا علوية |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/set_superscript/#str) | ينشئ حروفًا علوية |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | ينشئ حروفًا سفلية وعليا على اليمين |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#str-str) | ينشئ حروفًا سفلية وعليا على اليمين |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | ينشئ حروفًا سفلية وعليا على اليسار |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#str-str) | ينشئ حروفًا سفلية وعليا على اليسار |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/radical/#imathelement) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد. |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/radical/#str) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/set_upper_limit/#imathelement) | يأخذ الحد الأعلى |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/set_upper_limit/#str) | يأخذ الحد الأعلى |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/set_lower_limit/#imathelement) | يأخذ الحد الأدنى |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/set_lower_limit/#str) | يأخذ الحد الأدنى |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | ينشئ مشغلًا متعددًا (N-ary) |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-str-str) | ينشئ مشغلًا متعددًا (N-ary) |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement) | يأخذ التكامل |
| [`integral(self, integral_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes) | يأخذ التكامل بدون حدود |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str) | يأخذ التكامل |
| [`group(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/group/#) | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/group/#char-mathtopbotpositions-mathtopbotpositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [`to_border_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/to_border_box/#) | يضع هذا العنصر في صندوق حدود |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | يضع هذا العنصر في صندوق حدود |
| [`to_math_array(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/to_math_array/#) | يضع في مصفوفة رأسية |
| [`accent(self, accent_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/accent/#char) | يضبط علامة لهجة (حرف فوق هذا العنصر) |
| [`overbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/overbar/#) | يضع شريطًا أعلى هذا العنصر |
| [`underbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/underbar/#) | يضع شريطًا أسفل هذا العنصر |
| [`to_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/to_box/#) | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) <br/>            يستخدم لتجميع مكونات معادلة أو أي مثال آخر للنص الرياضي.<br/>            يمكن لكائن مُغَلَّف (على سبيل المثال) أن يعمل كمحاكي للمشغل مع أو بدون نقطة محاذاة،<br/>            أو أن يكون نقطة كسر سطر، أو يتم تجميعه بحيث لا يُسمح بحدوث كسر سطر داخله. |
| [`get_children(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathbox/get_children/#) | احصل على عناصر الأطفال |

### انظر أيضًا
* فئة [`MathBox`](/slides/python-net/ar/aspose.slides.mathtext/mathbox)
* فئة [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)
* الوحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* المكتبة [`Aspose.Slides`](/slides/python-net)