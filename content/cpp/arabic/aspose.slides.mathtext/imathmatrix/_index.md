---
title: IMathMatrix
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد كائن Matrix المكوّن من عناصر فرعية مرتبة في صف واحد أو أكثر وأعمدة. من المهم ملاحظة أن المصفوفات لا تحتوي على فواصل مدمجة. لوضع المصفوفة داخل الأقواس يجب استخدام كائن الفاصل (IMathDelimiter). يمكن استخدام معاملات null لإنشاء فجوات في المصفوفات.
type: docs
weight: 391
url: /ar/aspose.slides.mathtext/imathmatrix/
---
## فئة IMathMatrix

Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns. It is important to note that matrices do not have built in delimiters. To place the matrix in the brackets you should use the delimiter object ([IMathDelimiter](../imathdelimiter/)). Null arguments can be used to create gaps in matrices.

```cpp
class IMathMatrix : public virtual Aspose::Slides::MathText::IMathElement
```

## الأساليب

| Method | الوصف |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../imathelement/accent/)(char16_t) | يضبط علامة تركيز (حرف في أعلى هذا العنصر) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | يأخذ الدالة المحددة باستخدام هذا المثال كمعامل |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::String](../../system/string/)) | يأخذ الدالة المحددة باستخدام هذا المثال كمعامل |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) | يأخذ الدالة المحددة باستخدام هذا المثال كمعامل |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | يأخذ الدالة المحددة باستخدام هذا المثال كمعامل ومعامل إضافي محدد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) | يأخذ الدالة المحددة باستخدام هذا المثال كمعامل ومعامل إضافي محدد |
| virtual void [DeleteColumn](./deletecolumn/)(**int32_t**) | يحذف العمود المحدد |
| virtual void [DeleteRow](./deleterow/)(**int32_t**) | يحذف الصف المحدد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | ينشئ كسرًا بالعدد العلوي هذا والمقام المحدد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/)) | ينشئ كسرًا بالعدد العلوي هذا والمقام المحدد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) | ينشئ كسرًا من النوع المحدد بالعدد العلوي هذا والمقام المحدد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) | ينشئ كسرًا من النوع المحدد بالعدد العلوي هذا والمقام المحدد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)() | يحيط عنصرًا رياضيًا بأقواس |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)(char16_t, char16_t) | يحيط هذا العنصر بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سِيمانتِك C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقطية بأسلوب C# حيث تُعتبر NaN مساوية لـ NaN رغم أن IEC 60559:1989 تقول إن NaN لا يساوي أي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقطية بأسلوب C# حيث تُعتبر NaN مساوية لـ NaN رغم أن IEC 60559:1989 تقول إن NaN لا يساوي أي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | يأخذ دالة لوسيط باستخدام هذا المثال كاسم الدالة |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::String](../../system/string/)) | يأخذ دالة لوسيط باستخدام هذا المثال كاسم الدالة |
| virtual [MathVerticalAlignment](../mathverticalalignment/) [get_BaseJustification](./get_basejustification/)() | يحدد المحاذاة العمودية بالنسبة للنص المحيط. القيم المحتملة هي أعلى، أسفل، ووسط. الافتراضي: وسط |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | عدد الأعمدة في المصفوفة |
| virtual **uint32_t** [get_ColumnGap](./get_columngap/)() | قيمة التباعد الأفقي بين أعمدة المصفوفة؛ إذا تم تعيين ColumnGapRule إلى 3 (\"Exactly\"), فالواحدة تُفسَّر كـ twips (1/20 من النقطة). إذا تم تعيين ColumnGapRule إلى 4 (\"Multiple\"), فالواحدة تُفسَّر كعدد من الزيادات 0.5 em. في الحالات الأخرى يتم تجاهلها. الافتراضي: 0 |
| virtual [MathSpacingRules](../mathspacingrules/) [get_ColumnGapRule](./get_columngaprule/)() | نوع التباعد الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون الوحدات إيم أو نقاط (مخزنة كـ twips). الافتراضي: SingleSpacingGap (0) |
| virtual **bool** [get_HidePlaceholders](./get_hideplaceholders/)() | إخفاء العناصر النائبة للعناصر الفارغة في المصفوفة الافتراضي: false |
| virtual **uint32_t** [get_MinColumnWidth](./get_mincolumnwidth/)() | الحد الأدنى لعرض العمود بوحدة twips (1/20 من النقطة). يتم إضافة تباعد الفجوة (المعروف أيضًا باسم \"Column Gap\" أو \"Gap Width\") إلى MinColumnWidth لتحديد إجمالي تباعد Matrix [Column](../../aspose.slides/column/) (المسافة بين الحواف المتماثلة لأعمدة مختلفة). الافتراضي: 0. |
| virtual **int32_t** [get_RowCount](./get_rowcount/)() | عدد الصفوف في المصفوفة |
| virtual **uint32_t** [get_RowGap](./get_rowgap/)() | قيمة التباعد العمودي بين صفوف المصفوفة؛ إذا تم تعيين RowGapRule إلى 3 (\"Exactly\"), فالواحدة تُفسَّر كـ twips (1/20 من النقطة). إذا تم تعيين RowGapRule إلى 4 (\"Multiple\"), فالواحدة تُفسَّر كنصف سطر. الافتراضي: 0 |
| virtual [MathSpacingRules](../mathspacingrules/) [get_RowGapRule](./get_rowgaprule/)() | نوع التباعد العمودي بين صفوف المصفوفة؛ يمكن أن تكون الوحدات سطرًا أو نقاط (مخزنة كـ twips). الافتراضي: SingleSpacingGap (0) |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](../imathelement/getchildren/)() | الحصول على عناصر الأطفال |
| virtual [MathHorizontalAlignment](../mathhorizontalalignment/) [GetColumnAlignment](./getcolumnalignment/)(**int32_t**) | الحصول على المحاذاة الأفقية للعمود المحدد |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بهذا الكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)() | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) | عناصر المصفوفة |
| virtual void [idx_set](./idx_set/)(**int32_t**, **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | عناصر المصفوفة |
| virtual void [InsertColumnAfter](./insertcolumnafter/)(**int32_t**) | إدراج عمود جديد بعد العمود المحدد. في البداية كل العناصر في العمود الجديد هي null. |
| virtual void [InsertColumnBefore](./insertcolumnbefore/)(**int32_t**) | إدراج عمود جديد قبل العمود المحدد. في البداية كل العناصر في العمود الجديد هي null. |
| virtual void [InsertRowAfter](./insertrowafter/)(**int32_t**) | إدراج صف جديد بعد الصف المحدد. في البداية كل العناصر في الصف الجديد هي null. |
| virtual void [InsertRowBefore](./insertrowbefore/)(**int32_t**) | إدراج صف جديد قبل الصف المحدد. في البداية كل العناصر في الصف الجديد هي null. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) | يأخذ التكامل |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | يأخذ التكامل |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/)) | يأخذ التكامل بدون حدود |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) | يأخذ التكامل |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | يأخذ التكامل |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل مثلاً من النوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | يوحد عنصرًا رياضيًا ويشكل كتلة رياضية |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::String](../../system/string/)) | يوحد نصًا رياضيًا ويشكل كتلة رياضية |
| void [Lock](../../system/object/lock/)() | يطبق عِبارة القفل lock() في C#. استدعِها مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | ينشئ عاملًا N-اري |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | ينشئ عاملًا N-اري |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../imathelement/overbar/)() | يضبط شريطًا أعلى هذا العنصر |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::String](../../system/string/)) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن القيمة بالـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة والـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_BaseJustification](./set_basejustification/)([MathVerticalAlignment](../mathverticalalignment/)) | يحدد المحاذاة العمودية بالنسبة للنص المحيط. القيم المحتملة هي أعلى، أسفل، ووسط. الافتراضي: وسط |
| virtual void [set_ColumnGap](./set_columngap/)(**uint32_t**) | قيمة التباعد الأفقي بين أعمدة المصفوفة؛ إذا تم تعيين ColumnGapRule إلى 3 (\"Exactly\"), فالواحدة تُفسَّر كـ twips (1/20 من النقطة). إذا تم تعيين ColumnGapRule إلى 4 (\"Multiple\"), فالواحدة تُفسَّر كعدد من الزيادات 0.5 em. في الحالات الأخرى يتم تجاهلها. الافتراضي: 0 |
| virtual void [set_ColumnGapRule](./set_columngaprule/)([MathSpacingRules](../mathspacingrules/)) | نوع التباعد الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون الوحدات إيم أو نقاط (مخزنة كـ twips). الافتراضي: SingleSpacingGap (0) |
| virtual void [set_HidePlaceholders](./set_hideplaceholders/)(**bool**) | إخفاء العناصر النائبة للعناصر الفارغة في المصفوفة الافتراضي: false |
| virtual void [set_MinColumnWidth](./set_mincolumnwidth/)(**uint32_t**) | الحد الأدنى لعرض العمود بوحدة twips (1/20 من النقطة). يتم إضافة تباعد الفجوة (المعروف أيضًا باسم \"Column Gap\" أو \"Gap Width\") إلى MinColumnWidth لتحديد إجمالي تباعد Matrix [Column](../../aspose.slides/column/) (المسافة بين الحواف المتماثلة لأعمدة مختلفة). الافتراضي: 0. |
| virtual void [set_RowGap](./set_rowgap/)(**uint32_t**) | قيمة التباعد العمودي بين صفوف المصفوفة؛ إذا تم تعيين RowGapRule إلى 3 (\"Exactly\"), فالواحدة تُفسَّر كـ twips (1/20 من النقطة). إذا تم تعيين RowGapRule إلى 4 (\"Multiple\"), فالواحدة تُفسَّر كنصف سطر. الافتراضي: 0 |
| virtual void [set_RowGapRule](./set_rowgaprule/)([MathSpacingRules](../mathspacingrules/)) | نوع التباعد العمودي بين صفوف المصفوة؛ يمكن أن تكون الوحدات سطرًا أو نقاط (مخزنة كـ twips). الافتراضي: SingleSpacingGap (0) |
| virtual void [SetColumnAlignment](./setcolumnalignment/)(**int32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) | عيّن المحاذاة الأفقية للعمود المحدد |
| virtual void [SetColumnsAlignment](./setcolumnsalignment/)(**int32_t**, **uint32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) | عيّن المحاذاة الأفقية للأعمدة المحددة |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | يأخذ الحد الأدنى |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::String](../../system/string/)) | يأخذ الحد الأدنى |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | ينشئ نصًا سفليًا |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::String](../../system/string/)) | ينشئ نصًا سفليًا |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | ينشئ نصًا سفليًا وعاليًا على اليسار |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) | ينشئ نصًا سفليًا وعاليًا على اليسار |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | ينشئ نصًا سفليًا وعاليًا على اليمين |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) | ينشئ نصًا سفليًا وعاليًا على اليمين |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | ينشئ نصًا عاليًا |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::String](../../system/string/)) | ينشئ نصًا عاليًا |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | عيّن الوسيط القالب n مؤشرًا ضعيفًا (بدلاً من مشترك). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | يأخذ الحد الأعلى |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::String](../../system/string/)) | يأخذ الحد الأعلى |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)() | يضع هذا العنصر في صندوق حدود |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) | يضع هذا العنصر في صندوق حدود |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../imathelement/tobox/)() | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكوّنات معادلة أو نص رياضي آخر. يمكن أن يعمل كَمحاكي عامل مع أو بدون نقطة محاذاة، أو كنقطة كسر سطر، أو يتم تجميعه لمنع كسر السطر داخله. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../imathelement/tomatharray/)() | يضع في مصفوفة رأسية |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بناء C# typeof([System.Object](../../system/object/)). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../imathelement/underbar/)() | يضبط شريطًا أسفل هذا العنصر |
| void [Unlock](../../system/object/unlock/)() | يطبق عِبارة القفل lock() في C#. إلغاء القفل. استدعِها مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## ملاحظات

مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## انظر أيضًا

* الفئة [IMathElement](../imathelement/)
* النطاق [Aspose::Slides::MathText](../)
* المكتبة [Aspose.Slides](../../)