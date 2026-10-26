---
title: MathMatrix
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد كائن Matrix، المكوّن من عناصر فرعية مرتبة في صف واحد أو أكثر وأعمدة. من المهم ملاحظة أن المصفوفات لا تحتوي على محددات مدمجة. لوضع المصفوفة داخل الأقواس يجب استخدام كائن المحدد (IMathDelimiter). يمكن استخدام الوسائط الفارغة لإنشاء فراغات في المصفوفات.
type: docs
weight: 950
url: /ar/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix فئة

يحدد كائن Matrix، المكوّن من عناصر فرعية مرتبة في صفوف وأعمدة واحدة أو أكثر. من المهم ملاحظة أن المصفوفات لا تحتوي على محددات مدمجة. لوضع المصفوفة داخل الأقواس يجب استخدام كائن المحدد ([IMathDelimiter](../imathdelimiter/)). يمكن استخدام الوسائط الفارغة لإنشاء فراغات في المصفوفات.

```cpp
class MathMatrix : public Aspose::Slides::MathText::MathElementBase,
                   public Aspose::Slides::MathText::IMathMatrix,
                   public Aspose::Slides::MathText::IHasControlCharacterProperties
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../mathelementbase/accent/)(char16_t) override | يضبط علامة إكسنت (حرف فوق هذا العنصر) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | يأخذ الدالة المحددة باستخدام هذه النسخة كوسيط |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::String](../../system/string/)) override | يأخذ الدالة المحددة باستخدام هذه النسخة كوسيط |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) override | يأخذ الدالة المحددة باستخدام هذه النسخة كوسيط |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | يأخذ الدالة المحددة باستخدام هذه النسخة كوسيط والوسيط الإضافي المحدد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) override | يأخذ الدالة المحددة باستخدام هذه النسخة كوسيط والوسيط الإضافي المحدد |
| void [DeleteColumn](./deletecolumn/)(**int32_t**) override | يحذف العمود المحدد |
| void [DeleteRow](./deleterow/)(**int32_t**) override | يحذف الصف المحدد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/)) override | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) override | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) override | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)() override | يغلق عنصر رياضي بين أقواس |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)(char16_t, char16_t) override | يغلق عنصر رياضي بين أحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام C# [Object.Equals](../../system/object/equals/) دلالات. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبر NaNانين متساويين رغم أنه وفقًا لـ IEC 60559:1989 NaN ليس مساويًا لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبر NaNانين متساويين رغم أنه وفقًا لـ IEC 60559:1989 NaN ليس مساويًا لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | يأخذ دالة لوسيط باستخدام هذه النسخة كاسم الدالة |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::String](../../system/string/)) override | يأخذ دالة لوسيط باستخدام هذه النسخة كاسم الدالة |
| [MathVerticalAlignment](../mathverticalalignment/) [get_BaseJustification](./get_basejustification/)() override | يحدد محاذاة عمودية بالنسبة للنص المحيط. القيم الممكنة هي أعلى، أسفل، ووسط. الافتراضي: وسط |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | عدد الأعمدة في المصفوفة |
| **uint32_t** [get_ColumnGap](./get_columngap/)() override | قيمة التباعد الأفقي بين أعمدة المصفوفة؛ إذا تم ضبط ColumnGapRule إلى 3 ("Exactly")، فالوحدة تُفسر كـ twips (1/20 من النقطة). إذا تم ضبط ColumnGapRule إلى 4 ("Multiple")، فالوحدة تُفسر كعدد من الزيادات 0.5 em. في حالات أخرى يتم تجاهلها. الافتراضي: 0 |
| [MathSpacingRules](../mathspacingrules/) [get_ColumnGapRule](./get_columngaprule/)() override | نوع التباعد الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون وحدات التباعد الأمي أو النقاط (مخزنة كـ twips). الافتراضي: SingleSpacingGap (0) |
| **bool** [get_HidePlaceholders](./get_hideplaceholders/)() override | إخفاء العناصر النائبة للعناصر الفارغة في المصفوة الافتراضي: false |
| **uint32_t** [get_MinColumnWidth](./get_mincolumnwidth/)() override | الحد الأدنى لعرض العمود بوحدة twips (1/20 من النقطة). يتم إضافة تباعد الفجوة (المعروف أيضًا بـ "Column Gap" أو "Gap Width") إلى MinColumnWidth لتحديد إجمالي تباعد Matrix [Column](../../aspose.slides/column/) (المسافة بين الحواف المتشابهة للأعمدة المختلفة). الافتراضي: 0. |
| **int32_t** [get_RowCount](./get_rowcount/)() override | عدد الصفوف في المصفوفة |
| **uint32_t** [get_RowGap](./get_rowgap/)() override | قيمة التباعد الرأسي بين صفوف المصفوفة؛ إذا تم ضبط RowGapRule إلى 3 ("Exactly")، فالوحدة تُفسر كـ twips (1/20 من النقطة). إذا تم ضبط RowGapRule إلى 4 ("Multiple")، فالوحدة تُفسر كنصف سطر. الافتراضي: 0 |
| [MathSpacingRules](../mathspacingrules/) [get_RowGapRule](./get_rowgaprule/)() override | نوع التباعد العمودي بين صفوف المصفورة؛ يمكن أن تكون الوحدات خطوطًا أو نقاطًا (مخزنة كـ twips). الافتراضي: SingleSpacingGap (0) |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](./getchildren/)() override | احصل على العناصر الفرعية |
| [MathHorizontalAlignment](../mathhorizontalalignment/) [GetColumnAlignment](./getcolumnalignment/)(**int32_t**) override | احصل على المحاذاة الأفقية للعمود المحدد |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)() override | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) override | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) override | عنصر من المصفوفة |
| void [idx_set](./idx_set/)(**int32_t**, **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | عنصر من المصفوفة |
| void [InsertColumnAfter](./insertcolumnafter/)(**int32_t**) override | إدراج عمود جديد بعد العمود المحدد. في البداية جميع العناصر في العمود الجديد هي null. |
| void [InsertColumnBefore](./insertcolumnbefore/)(**int32_t**) override | إدراج عمود جديد قبل العمود المحدد. في البداية جميع العناصر في العمود الجديد هي null. |
| void [InsertRowAfter](./insertrowafter/)(**int32_t**) override | إدراج صف جديد بعد الصف المحدد. في البداية جميع العناصر في الصف الجديد هي null. |
| void [InsertRowBefore](./insertrowbefore/)(**int32_t**) override | إدراج صف جديد قبل الصف المحدد. في البداية جميع العناصر في الصف الجديد هي null. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) override | يأخذ التكامل |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | يأخذ التكامل |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/)) override | يأخذ التكامل بدون حدود |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) override | يأخذ التكامل |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | يأخذ التكامل |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | يوحد عنصرًا رياضيًا ويكوّن كتلة رياضية |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::String](../../system/string/)) override | يوحد نصًا رياضيًا ويكوّن كتلة رياضية |
| void [Lock](../../system/object/lock/)() | يُنفّذ تعبير القفل lock() في C#. يُستدعى مباشرة أو يستخدم كائن الحارس [LockContext](../../system/lockcontext/). |
|  [MathMatrix](./mathmatrix/)(**int32_t**, **int32_t**) | ينشئ نسخة جديدة من الفئة [MathMatrix](./). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | ينشئ عاملًا N-ي |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | ينشئ عاملًا N-ي |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يُهيئ جميع البُنى الداخلية |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة نسخة. لا ينسخ شيئًا فعلاً، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعلاً، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../mathelementbase/overbar/)() override | يضبط شريطًا فوق هذا العنصر |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | يحدد الجذر الرياضي للدرجة المحددة من الوسيط المحدد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::String](../../system/string/)) override | يحدد الجذر الرياضي للدرجة المحددة من الوسيط المحدد |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة |
| void [set_BaseJustification](./set_basejustification/)([MathVerticalAlignment](../mathverticalalignment/)) override | يحدد المحاذاة العمودية بالنسبة للنص المحيط. القيم الممكنة هي أعلى، أسفل، ووسط. الافتراضي: وسط |
| void [set_ColumnGap](./set_columngap/)(**uint32_t**) override | قيمة التباعد الأفقي بين أعمدة المصفوفة؛ إذا تم ضبط ColumnGapRule إلى 3 ("Exactly")، فالوحدة تُفسر كـ twips (1/20 من النقطة). إذا تم ضبط ColumnGapRule إلى 4 ("Multiple")، فالوحدة تُفسر كعدد من الزيادات 0.5 em. في حالات أخرى يتم تجاهلها. الافتراضي: 0 |
| void [set_ColumnGapRule](./set_columngaprule/)([MathSpacingRules](../mathspacingrules/)) override | نوع التباعد الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون وحدات التباعد الأمي أو النقاط (مخزنة كـ twips). الافتراضي: SingleSpacingGap (0) |
| void [set_HidePlaceholders](./set_hideplaceholders/)(**bool**) override | إخفاء العناصر النائبة للعناصر الفارغة في المصفوة الافتراضي: false |
| void [set_MinColumnWidth](./set_mincolumnwidth/)(**uint32_t**) override | الحد الأدنى لعرض العمود بوحدة twips (1/20 من النقطة). يتم إضافة تباعد الفجوة (المعروف أيضًا بـ "Column Gap" أو "Gap Width") إلى MinColumnWidth لتحديد إجمالي تباعد Matrix [Column](../../aspose.slides/column/) (المسافة بين الحواف المتشابهة للأعمدة المختلفة). الافتراضي: 0. |
| void [set_RowGap](./set_rowgap/)(**uint32_t**) override | قيمة التباعد الرأسي بين صفوف المصفوفة؛ إذا تم ضبط RowGapRule إلى 3 ("Exactly")، فالوحدة تُفسر كـ twips (1/20 من النقطة). إذا تم ضبط RowGapRule إلى 4 ("Multiple")، فالوحدة تُفسر كنصف سطر. الافتراضي: 0 |
| void [set_RowGapRule](./set_rowgaprule/)([MathSpacingRules](../mathspacingrules/)) override | نوع التباعد العمودي بين صفوف المصفوفة؛ يمكن أن تكون الوحدات خطوطًا أو نقاطًا (مخزنة كـ twips). الافتراضي: SingleSpacingGap (0) |
| void [SetColumnAlignment](./setcolumnalignment/)(**int32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) override | يضبط المحاذاة الأفقية للعمود المحدد |
| void [SetColumnsAlignment](./setcolumnsalignment/)(**int32_t**, **uint32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) override | يضبط المحاذاة الأفقية للأعمدة المحددة |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | يأخذ الحد الأدنى |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::String](../../system/string/)) override | يأخذ الحد الأدنى |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | ينشئ نصًا سفليًا |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::String](../../system/string/)) override | ينشئ نصًا سفليًا |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | ينشئ نصًا سفليًا وعليا على اليسار |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) override | ينشئ نصًا سفليًا وعليا على اليسار |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | ينشئ نصًا سفليًا وعليا على اليمين |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) override | ينشئ نصًا سفليًا وعليا على اليمين |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | ينشئ نصًا عُلويًا |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::String](../../system/string/)) override | ينشئ نصًا عُلويًا |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n't كإشارة ضعيفة (بدلاً من مشاركة). يتيح تحويل الإشارات في الحاويات إلى الوضع الضعيف |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | يأخذ الحد الأعلى |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::String](../../system/string/)) override | يأخذ الحد الأعلى |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعدد المرجع المشترك |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويرجع عدد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)() override | يضع هذا العنصر في صندوق حد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) override | يضع هذا العنصر في صندوق حد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../mathelementbase/tobox/)() override | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو غيرها من النصوص الرياضية. يمكن أن يستخدم الصندوق كمحاكي عامل مع أو بدون نقطة محاذاة، أو كنقطة كسر سطر، أو يُجمع بحيث لا يسمح بكسر السطر داخله |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../mathelementbase/tomatharray/)() override | يضع في مصفوفة عمودية |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../mathelementbase/underbar/)() override | يضبط شريطًا أسفل هذا العنصر |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل C# lock(). يُستدعى مباشرة أو يستخدم كائن الحارس [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع البُنى الداخلية |

## ملاحظات


مثال: 
```cpp
System::SharedPtr<IMathMatrix> matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## انظر أيضا

* فئة [MathElementBase](../mathelementbase/)
* فئة [IMathMatrix](../imathmatrix/)
* فئة [IHasControlCharacterProperties](../ihascontrolcharacterproperties/)
* نطاق [Aspose::Slides::MathText](../)
* مكتبة [Aspose.Slides](../../)