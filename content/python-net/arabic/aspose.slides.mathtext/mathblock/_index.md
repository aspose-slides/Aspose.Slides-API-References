---
title: MathBlock class
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathblock/
---
## MathBlock فئة

يحدد مثيلاً للنص الرياضي الموجود داخل MathParagraph ويبدأ على سطر خاص به.  
جميع مناطق الرياضيات، بما في ذلك المعادلات، التعبيرات، مصفوفات المعادلات أو التعبيرات، والصيغ ممثلة بكتلة رياضية.

**الوراثة:**[`MathBlock`](/slides/python-net/ar/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)

يُظهر نوع MathBlock الأعضاء التالية:

## المُنشئات

| المنشئ | الوصف |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/__init__/#) | ي initializes a new instance of the MathBlock class. |
| [`__init__(self, math_element)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/__init__/#imathelement) | ينشئ كتلة رياضية جديدة ويضع العنصر المحدد فيها |
| [`__init__(self, math_elements)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`count`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/count/) | يحصل على عدد عناصر الرياضيات الفرعية الفعلية الموجودة في المجموعة.<br/>            قابل للقراءة فقط **int**. |
| [`is_read_only`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/is_read_only/) | يرجع false لأن مجموعة العناصر الفرعية يمكن تعديلها. |

يحصل أو يضبط IMathElement في الفهرس المحدد.

## الفهرس

| الاسم | الوصف |
| :- | :- |
| [`[index]`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/__getitem__/) | الفهرس الصفري للعنصر |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/join/#imathelement) | ينضم عنصر رياضي إلى هذه الكتلة الرياضية |
| [`join(self, math_text)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/join/#str) | ينضم نص رياضي إلى هذه الكتلة الرياضية |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/divide/#imathelement) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/divide/#str) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [`enclose(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/enclose/#) | يحيط عنصر رياضي بأقواس |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/enclose/#char-char) | يحيط العناصر الفرعية لهذه الكتلة بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | يحيط العناصر الفرعية لهذه الكتلة بأحرف محددة مثل الأقواس أو أخرى كإطار<br/>            ويحددها بحرف فاصل |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/function/#imathelement) | يأخذ دالة لوسيط باستخدام هذه المثيلة كاسم الدالة |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/function/#str) | يأخذ دالة لوسيط باستخدام هذه المثيلة كاسم الدالة |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | يأخذ الدالة المحددة باستخدام هذه المثيلة كوسيط |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | يأخذ الدالة المحددة باستخدام هذه المثيلة كوسيط |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | يأخذ الدالة المحددة باستخدام هذه المثيلة كوسيط |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | يأخذ الدالة المحددة باستخدام هذه المثيلة كوسيط ووسيط إضافي محدد |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | يأخذ الدالة المحددة باستخدام هذه المثيلة كوسيط ووسيط إضافي محدد |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | ينشئ نصًا سفليًا |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/set_subscript/#str) | ينشئ نصًا سفليًا |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | ينشئ نصًا علويًا |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/set_superscript/#str) | ينشئ نصًا علويًا |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | ينشئ نصًا سفليًا وعليًا على اليمين |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | ينشئ نصًا سفليًا وعليًا على اليمين |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | ينشئ نصًا سفليًا وعليًا على اليسار |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | ينشئ نصًا سفليًا وعليًا على اليسار |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/radical/#imathelement) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد. |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/radical/#str) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | يأخذ الحد الأعلى |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | يأخذ الحد الأعلى |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | يأخذ الحد الأدنى |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | يأخذ الحد الأدنى |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | ينشئ عامل N-آري |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | ينشئ عامل N-آري |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | يأخذ التكامل |
| [`integral(self, integral_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | يأخذ التكامل بدون حدود |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | يأخذ التكامل |
| [`group(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/group/#) | يضع هذا العنصر في مجموعة باستخدام قوس تجعيد سفلي |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل قوس تجعيد سفلي أو آخر |
| [`to_border_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/to_border_box/#) | يضع هذا العنصر في صندوق حد |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | يضع هذا العنصر في صندوق حد |
| [`to_math_array(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/to_math_array/#) | يضع العناصر الفرعية في مصفوفة عمودية |
| [`accent(self, accent_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/accent/#char) | يضبط علامة إكسنت (حرف فوق هذا العنصر) |
| [`overbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/overbar/#) | يضبط شريطًا فوق هذا العنصر |
| [`underbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/underbar/#) | يضبط شريطًا أسفل هذا العنصر |
| [`to_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/to_box/#) | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) <br/>            يُستخدم لتجميع مكونات معادلة أو نص رياضي آخر.<br/>            يمكن لكائن مُحاط (على سبيل المثال) أن يعمل كمحاكي عامل مع أو بدون نقطة محاذاة، <br/>            أو كنقطة فاصل سطر، أو يُجمع بحيث لا يسمح بوجود فواصل سطر داخله. |
| [`get_children(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/get_children/#) | احصل على العناصر الفرعية |
| [`add(self, item)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/add/#imathelement) | يضيف عنصرًا رياضيًا إلى نهاية المجموعة. |
| [`clear(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/clear/#) | يزيل جميع العناصر من المجموعة. |
| [`contains(self, item)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/contains/#imathelement) | يحدد ما إذا كانت المجموعة تحتوي على قيمة محددة. |
| [`copy_to(self, array, array_index)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | نسخ إلى مصفوفة محددة. |
| [`remove(self, item)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/remove/#imathelement) | يزيل الظهور الأول لكائن محدد من المجموعة. |
| [`index_of(self, item)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/index_of/#imathelement) | يحدد فهرس عنصر رياضي معين في المجموعة. |
| [`insert(self, index, item)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | يدرج MathElement في المجموعة عند الفهرس المحدد. |
| [`remove_at(self, index)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/remove_at/#int) | يزيل العنصر عند الفهرس المحدد في المجموعة. |
| [`join_block(self, other)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/join_block/#imathblock) | ينضم كتلة رياضية أخرى إلى هذه. |
| [`delimit(self, separator_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/delimit/#char) | يفصل العناصر الفرعية بحرف فاصل (بدون الأقواس) |
| [`write_as_math_ml(self, stream)`](/slides/python-net/ar/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | يحفظ محتوى هذا [`MathBlock`](/slides/python-net/ar/aspose.slides.mathtext/mathblock) كـ MathML |


### انظر أيضًا
* فئة [`MathBlock`](/slides/python-net/ar/aspose.slides.mathtext/mathblock)
* فئة [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)
* وحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* مكتبة [`Aspose.Slides`](/slides/python-net)