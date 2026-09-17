---
title: MathPhantom class
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathphantom/
---
## فئة MathPhantom

يمثل كائن رياضي شبح (<m:phant>) يؤثر على تخطيط العنصر الفرعي دون ضرورة عرضه. يمكن للشفبح إخفاء التعبير الأساسي مع الحفاظ على عرضه أو ارتفاعه أو عمقه لتنسيق الصيغ أو حجز مساحة. يتم التحكم في سلوك الرؤية والهندسة بواسطة خصائص مثل Show و ZeroWid و ZeroAsc و ZeroDesc و Transp.

**الوراثة:**[`MathPhantom`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom) → [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)

يعرض نوع MathPhantom الأعضاء التالية:

## المنشئات

| منشئ | الوصف |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/__init__/#imathelement) | ينشئ مثيلاً جديداً من الفئة [`MathPhantom`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom) <br/>            باستخدام عنصر الرياضيات الأساسي المحدد. |

## الخصائص

| خاصية | الوصف |
| :- | :- |
| [`base`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/base/) | المعامل الأساسي |
| [`show`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/show/) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان العنصر الأساسي معروضاً. |
| [`zero_width`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/zero_width/) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب اعتبار عرض العنصر الأساسي صفراً. |
| [`zero_asc`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/zero_asc/) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب اعتبار صعود العنصر الأساسي (الارتفاع فوق خط الأساس) صفراً. |
| [`zero_desc`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/zero_desc/) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب اعتبار هبوط العنصر الأساسي (العمق أسفل خط الأساس) صفراً. |
| [`transp`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/transp/) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشفبح شفافاً لقواعد التباعد المستندة إلى الفئة. |

## الأساليب

| طريقة | الوصف |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/join/#imathelement) | يجمع عنصرًا رياضيًا ويشكل كتلة رياضية |
| [`join(self, math_text)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/join/#str) | يجمع نصًا رياضيًا ويشكل كتلة رياضية |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/divide/#imathelement) | ينشئ كسرًا باستخدام هذا البسط والمقام المحدد |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/divide/#str) | ينشئ كسرًا باستخدام هذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/divide/#imathelement-mathfractiontypes) | ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/divide/#str-mathfractiontypes) | ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد |
| [`enclose(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/enclose/#) | يغلف عنصرًا رياضيًا بأقواس |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/enclose/#char-char) | يغلف عنصرًا رياضيًا بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/function/#imathelement) | يأخذ دالة ذات معامل باستخدام هذه المثيلة كاسم الدالة |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/function/#str) | يأخذ دالة ذات معامل باستخدام هذه المثيلة كاسم الدالة |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/as_argument_of_function/#imathelement) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/as_argument_of_function/#str) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsofoneargument) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل ومعامل إضافي محدد |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) | يأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل ومعامل إضافي محدد |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/set_subscript/#imathelement) | ينشئ نصًا سفليًا |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/set_subscript/#str) | ينشئ نصًا سفليًا |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/set_superscript/#imathelement) | ينشئ نصًا علويًا |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/set_superscript/#str) | ينشئ نصًا علويًا |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) | ينشئ نصًا سفليًا وعليًا على اليمين |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#str-str) | ينشئ نصًا سفليًا وعليًا على اليمين |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) | ينشئ نصًا سفليًا وعليًا على اليسار |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#str-str) | ينشئ نصًا سفليًا وعليًا على اليسار |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/radical/#imathelement) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/radical/#str) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/set_upper_limit/#imathelement) | يأخذ الحد الأعلى |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/set_upper_limit/#str) | يأخذ الحد الأعلى |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/set_lower_limit/#imathelement) | يأخذ الحد الأدنى |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/set_lower_limit/#str) | يأخذ الحد الأدنى |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) | ينشئ عاملًا N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-str-str) | ينشئ عاملًا N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement) | يأخذ التكامل |
| [`integral(self, integral_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes) | يأخذ التكامل بدون حدود |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str) | يأخذ التكامل |
| [`group(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/group/#) | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [`to_border_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/to_border_box/#) | يضع هذا العنصر في صندوق حدود |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | يضع هذا العنصر في صندوق حدود |
| [`to_math_array(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/to_math_array/#) | يضع في مصفوفة عمودية |
| [`accent(self, accent_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/accent/#char) | يضبط علامة لهجة (حرف فوق هذا العنصر) |
| [`overbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/overbar/#) | يضبط شريطًا فوق هذا العنصر |
| [`underbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/underbar/#) | يضبط شريطًا تحت هذا العنصر |
| [`to_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/to_box/#) | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي)<br/>            يُستخدم لتجميع مكونات معادلة أو مثال آخر من النص الرياضي.<br/>            يمكن للعنصر المربع (على سبيل المثال) أن يعمل كمُحاكٍ للمعامل مع أو بدون نقطة محاذاة،<br/>            أو أن يكون نقطة كسر سطر، أو يُجمع بطريقة لا تسمح بوجود فواصل سطر داخله. |
| [`get_children(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom/get_children/#) | احصل على عناصر الأطفال |

### راجع أيضًا
* فئة [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)
* فئة [`MathPhantom`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom)
* وحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)