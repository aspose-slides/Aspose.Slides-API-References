---
title: MathBox
second_title: Aspose.Slides مرجع API للغة C++
description: يحدد عملية التغليف (التعبئة) المنطقية للعنصر الرياضي. على سبيل المثال، يمكن لكائن مُغلف أن يعمل كمحاكي للمشغل مع أو بدون نقطة محاذاة، أو أن يكون نقطة كسر سطر، أو أن يُجمّع بحيث لا يسمح بحدوث كسر سطر داخله. على سبيل المثال، يجب تغليف عامل "==" لمنع كسر السطر.
type: docs
weight: 742
url: /ar/aspose.slides.mathtext/mathbox/
---
## MathBox فئة

Specifies the logical boxing (packaging) of mathematical element. For example, a boxed object can serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within. For example, the \"==\" operator should be boxed to prevent line breaks.

```cpp
class MathBox : public Aspose::Slides::MathText::MathElementBase,
                public Aspose::Slides::MathText::IMathBox,
                public Aspose::Slides::MathText::IHasControlCharacterProperties
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../mathelementbase/accent/)(char16_t) override | يضبط علامة تشكيل (حرف على أعلى هذا العنصر) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | تأخذ الدالة المحددة باستخدام هذا الكائن كمعامل |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::String](../../system/string/)) override | تأخذ الدالة المحددة باستخدام هذا الكائن كمعامل |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) override | تأخذ الدالة المحددة باستخدام هذا الكائن كمعامل |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | تأخذ الدالة المحددة باستخدام هذا الكائن كمعامل وتضيف المعامل الإضافي المحدد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) override | تأخذ الدالة المحددة باستخدام هذا الكائن كمعامل وتضيف المعامل الإضافي المحدد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/)) override | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) override | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) override | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)() override | يحيط عنصر رياضي بأقواس |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)(char16_t, char16_t) override | يحيط عنصر رياضي بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُ considered NaNانان متساويتين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليست مساوية لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُ considered NaNانان متساويتين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليست مساوية لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | تأخذ دالة لوسيط باستخدام هذا الكائن كاسم الدالة |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::String](../../system/string/)) override | تأخذ دالة لوسيط باستخدام هذا الكائن كاسم الدالة |
| **bool** [get_AlignmentPoint](./get_alignmentpoint/)() override | عند كونها true، يعمل هذا محاكي المشغل كنقطة محاذاة؛ أي يمكن محاذاة نقاط المحاذاة المعينة في معادلات أخرى معه. القيمة الافتراضية: false |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Base](./get_base/)() override | وسيطة أساسية |
| **bool** [get_Differential](./get_differential/)() override | التفاضل: عند كونها true، يعمل الصندوق كتفاضل (على سبيل المثال \\uD835\\uDC51\\uD835\\uDC65 في تكامل)، ويتلقى التباعد الأفقي المناسب للفرق الرياضي. القيمة الافتراضية: false |
| **uint8_t** [get_ExplicitBreak](./get_explicitbreak/)() override | الكسرة الصريحة تحدد ما إذا كان هناك كسر سطر في بداية كائن الصندوق، بحيث يلتف السطر عند بداية الصندوق. تحدد عدد المشغل في السطر السابق للنص الرياضي الذي سيُستخدم كنقطة محاذاة للسطر الحالي من النص الرياضي. القيم الممكنة: 1..255 القيمة الافتراضية: 0 (لا كسر صريح) |
| **bool** [get_NoBreak](./get_nobreak/)() override | بدون كسر: هذه الخاصية تحدد خاصية \"غير القابلة للكسر\" على صندوق الكائن. عند كونها true، لا يمكن حدوث أي كسر سطر داخل الصندوق. قد يكون هذا مهمًا لمحاكيات المشغل التي تتكون من أكثر من مشغل ثنائي. إذا لم تُحدد هذه الخاصية، يمكن حدوث كسر داخل الصندوق. القيمة الافتراضية: true |
| **bool** [get_OperatorEmulator](./get_operatoremulator/)() override | محاكي المشغل. عند كونها true، يعمل الصندوق ومحتوياته كمشغل واحد ويرث خصائص المشغل. هذا يعني، على سبيل المثال، أن الحرف يمكن أن يكون نقطة لكسر سطر ويمكن محاذاته إلى مشغلات أخرى. غالبًا ما تُستخدم محاكيات المشغل عندما يجتمع glyph واحد أو أكثر لتكوّن مشغلًا، مثل '=='. القيمة الافتراضية: false |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](./getchildren/)() override | يحصل على العناصر الفرعية |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نسخة مماثلة لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). تمكّن من تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نسخة مماثلة لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)() override | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) override | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) override | يأخذ التكامل |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | يأخذ التكامل |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/)) override | يأخذ التكامل بدون حدود |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) override | يأخذ التكامل |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | يأخذ التكامل |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نسخة مماثلة لمشغل C# 'is'. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | يضم عنصرًا رياضيًا ويشكل كتلة رياضية |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::String](../../system/string/)) override | يضم نصًا رياضيًا ويشكل كتلة رياضية |
| void [Lock](../../system/object/lock/)() | ينفذ جملة C# lock() للقفل. استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
|  [MathBox](./mathbox/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | يُهيّء [MathBox](./) بالعنصر المحدد كمعامل |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نسخة مماثلة لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). تمكّن من استنساخ الأنواع المخصصة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | ينشئ مشغلًا متعدد المتغيّرات |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | ينشئ مشغلًا متعدد المتغيّرات |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّء جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة النسخ. لا ينسخ أي شيء فعليًا، بل يهيّء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | مشغل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيّء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../mathelementbase/overbar/)() override | يضع شريطًا أعلى هذا العنصر |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::String](../../system/string/)) override | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_AlignmentPoint](./set_alignmentpoint/)(**bool**) override | عند كونها true، يعمل هذا محاكي المشغل كنقطة محاذاة؛ أي يمكن محاذاة نقاط المحاذاة المعينة في معادلات أخرى معه. القيمة الافتراضية: false |
| void [set_Differential](./set_differential/)(**bool**) override | التفاضل: عند كونها true، يعمل الصندوق كتفاضل (على سبيل المثال \\uD835\\uDC51\\uD835\\uDC65 في تكامل)، ويتلقى التباعد الأفقي المناسب للفرق الرياضي. القيمة الافتراضية: false |
| void [set_ExplicitBreak](./set_explicitbreak/)(**uint8_t**) override | الكسرة الصريحة تحدد ما إذا كان هناك كسر سطر في بداية كائن الصندوق، بحيث يلتف السطر عند بداية الصندوق. تحدد عدد المشغل في السطر السابق للنص الرياضي الذي سيُستخدم كنقطة محاذاة للسطر الحالي من النص الرياضي. القيم الممكنة: 1..255 القيمة الافتراضية: 0 (لا كسر صريح) |
| void [set_NoBreak](./set_nobreak/)(**bool**) override | بدون كسر: هذه الخاصية تحدد خاصية \"غير القابلة للكسر\" على صندوق الكائن. عند كونها true، لا يمكن حدوث أي كسر سطر داخل الصندوق. قد يكون هذا مهمًا لمحاكيات المشغل التي تتكون من أكثر من مشغل ثنائي. إذا لم تُحدد هذه الخاصية، يمكن حدوث كسر داخل الصندوق. القيمة الافتراضية: true |
| void [set_OperatorEmulator](./set_operatoremulator/)(**bool**) override | محاكي المشغل. عند كونها true، يعمل الصندوق ومحتوياته كمشغل واحد ويرث خصائص المشغل. هذا يعني، على سبيل المثال، أن الحرف يمكن أن يكون نقطة لكسر سطر ويمكن محاذاته إلى مشغلات أخرى. غالبًا ما تُستخدم محاكيات المشغل عندما يجتمع glyph واحد أو أكثر لتكوّن مشغلًا، مثل '=='. القيمة الافتراضية: false |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | يأخذ الحد الأدنى |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::String](../../system/string/)) override | يأخذ الحد الأدنى |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | ينشئ مؤشرًا سفليًا |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::String](../../system/string/)) override | ينشئ مؤشرًا سفليًا |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | ينشئ مؤشرًا سفليًا وعلويًا على اليسار |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) override | ينشئ مؤشرًا سفليًا وعلويًا على اليسار |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | ينشئ مؤشرًا سفليًا وعلويًا على اليمين |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) override | ينشئ مؤشرًا سفليًا وعلويًا على اليمين |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | ينشئ مؤشرًا علويًا |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::String](../../system/string/)) override | ينشئ مؤشرًا علويًا |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كمرجع ضعيف (بدلاً من مشترك). يتيح تحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | يأخذ الحد الأعلى |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::String](../../system/string/)) override | يأخذ الحد الأعلى |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)() override | يضع هذا العنصر في صندوق إطار |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) override | يضع هذا العنصر في صندوق إطار |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../mathelementbase/tobox/)() override | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو أي مثال آخر من النص الرياضي. يمكن لكائن موضع داخل صندوق (على سبيل المثال) أن يعمل كمحاكي مشغل مع أو بدون نقطة محاذاة، أو كنقطة كسر سطر، أو أن يُجمّع بحيث لا يُسمح بحدوث كسر سطر داخله. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../mathelementbase/tomatharray/)() override | يضع في صف عمودي |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نسخة مماثلة لطريقة C# [Object.ToString()](../../system/object/tostring/). تمكّن من تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ تركيب C# typeof([System.Object](../../system/object/)). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../mathelementbase/underbar/)() override | يضع شريطًا أسفل هذا العنصر |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## ملاحظات

Example: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
```

## أنظر أيضًا

* الفئة [MathElementBase](../mathelementbase/)
* الفئة [IMathBox](../imathbox/)
* الفئة [IHasControlCharacterProperties](../ihascontrolcharacterproperties/)
* مساحة الاسم [Aspose::Slides::MathText](../)
* المكتبة [Aspose.Slides](../../)