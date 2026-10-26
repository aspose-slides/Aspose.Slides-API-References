---
title: NumberFormatInfo
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يحتوي على معلومات حول كيفية تنسيق الأرقام. عمليات الضبط مُفعّلة فقط على الكائنات غير القابلة للقراءة فقط. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تُنشئ مثلاً من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل و/أو أعطال التأكيد. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 248
url: /ar/system.globalization/numberformatinfo/
---
## فئة NumberFormatInfo

يحتوي على معلومات حول كيفية تنسيق الأرقام. عمليات الضبط مُفعلة فقط على الكائنات غير القابلة للقراءة فقط. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل و/أو أعطال التأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كوسيط.

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## الطرق

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | ينسخ معلومات التنسيق. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام معايير C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين على الرغم من أن المعيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين على الرغم من أن المعيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| int [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | يعيد عدد أرقام الفاصلة العشرية للعملة. |
| [String](../../system/string/) [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | يعيد فاصل الفاصلة العشرية للعملة. |
| [String](../../system/string/) [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | يعيد فاصل مجموعة العملات. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | يعيد عدد أرقام الفاصلة العشرية للعملة لكل مجموعة. |
| int [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | يعيد نمط سالب العملة. |
| int [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | يعيد نمط موجب العملة. |
| [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | يعيد رمز العملة. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | يعيد معلومات تنسيق الأرقام المحددة بثقافة الخيط الحالي. |
| [DigitShapes](../digitshapes/) [get_DigitSubstitution](./get_digitsubstitution/)() const | يعيد قيمة تحدد كيفية عرض شكل الرقم. |
| static const [NumberFormatInfoPtr](../numberformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | يعيد معلومات تنسيق الأرقام المحددة بثقافة غير متغيرة. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | يتحقق إذا كان التنسيق للقراءة فقط. |
| [String](../../system/string/) [get_NaNSymbol](./get_nansymbol/)() const | يعيد رمز Not-a-Number. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_NativeDigits](./get_nativedigits/)() const | يعيد رموز الأرقام (0 إلى 9). |
| [String](../../system/string/) [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | يعيد رمز اللانهاية السالبة. |
| [String](../../system/string/) [get_NegativeSign](./get_negativesign/)() const | يعيد العلامة السالبة. |
| int [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | يعيد عدد الأرقام العشرية. |
| [String](../../system/string/) [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | يعيد فاصل الفاصلة العشرية. |
| [String](../../system/string/) [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | يعيد فاصل مجموعة الأرقام. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_NumberGroupSizes](./get_numbergroupsizes/)() const | يعيد عدد الأرقام لكل مجموعة. |
| int [get_NumberNegativePattern](./get_numbernegativepattern/)() const | يعيد نمط سالب الرقم. |
| int [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | يعيد عدد المنازل العشرية في قيم النسبة المئوية. |
| [String](../../system/string/) [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | يعيد فاصل الفاصلة العشرية في قيم النسبة المئوية. |
| [String](../../system/string/) [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | يعيد فاصل مجموعة القيم في النسبة المئوية. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_PercentGroupSizes](./get_percentgroupsizes/)() const | يعيد عدد الأرقام لكل مجموعة قيم النسبة المئوية. |
| int [get_PercentNegativePattern](./get_percentnegativepattern/)() const | يعيد نمط سالب النسبة المئوية. |
| int [get_PercentPositivePattern](./get_percentpositivepattern/)() const | يعيد نمط موجب النسبة المئوية. |
| [String](../../system/string/) [get_PercentSymbol](./get_percentsymbol/)() const | يعيد رمز النسبة المئوية. |
| [String](../../system/string/) [get_PerMilleSymbol](./get_permillesymbol/)() const | يعيد رمز الألفية. |
| [String](../../system/string/) [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | يعيد رمز اللانهاية الموجبة. |
| [String](../../system/string/) [get_PositiveSign](./get_positivesign/)() const | يعيد العلامة الموجبة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يعيد بنية عداد الإشارة المرجعية المرتبطة بالكائن. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | يعيد المُنسق لنوع معين. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نسخة مماثلة لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). تمكّن تجزئة الكائنات المخصصة. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | يعيد المُنسق المرتبط بموفر التنسيق. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يعيد النوع الفعلي للكائن. نسخة مماثلة لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق إذا كان الكائن يمثل مثيلًا من النوع الموصوف بواسطة targetType. نسخة مماثلة للمشغل C# 'is'. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نسخة مماثلة لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). تمكّن استنساخ الأنواع المخصصة. |
|  [NumberFormatInfo](./numberformatinfo/)() | المُنشئ الافتراضي ([NumberFormatInfo](./) غير متغير). |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويُمكّن إنشاء نسخ فرعية. |
| [NumberFormatInfo](./)\& [operator=](./operator_equal/)(const [NumberFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويُمكّن إنشاء نسخ فرعية. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [ReadOnly](./readonly/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | يعيد نسخة القراءة فقط من المُنسق. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمقارنة المرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمقارنة المرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشتركة بالقيمة المحددة. |
| void [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | يضبط عدد أرقام الفاصلة العشرية للعملة. |
| void [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const [String](../../system/string/)\&) | يضبط فاصل الفاصلة العشرية للعملة. |
| void [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const [String](../../system/string/)\&) | يضبط فاصل مجموعة العملة. |
| void [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | يضبط عدد أرقام الفاصلة العشرية للعملة لكل مجموعة. |
| void [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | يضبط نمط سالب العملة. |
| void [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | يضبط نمط موجب العملة. |
| void [set_CurrencySymbol](./set_currencysymbol/)(const [String](../../system/string/)\&) | يضبط رمز العملة. |
| void [set_DigitSubstitution](./set_digitsubstitution/)([DigitShapes](../digitshapes/)) | يضبط قيمة تحدد كيفية عرض شكل الرقم. |
| void [set_NaNSymbol](./set_nansymbol/)(const [String](../../system/string/)\&) | يضبط رمز Not-a-Number. |
| void [set_NativeDigits](./set_nativedigits/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | يضبط رموز الأرقام (0 إلى 9). |
| void [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const [String](../../system/string/)\&) | يضبط رمز اللانهاية السالبة. |
| void [set_NegativeSign](./set_negativesign/)(const [String](../../system/string/)\&) | يضبط العلامة السالبة. |
| void [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | يضبط عدد الأرقام العشرية. |
| void [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const [String](../../system/string/)\&) | يضبط فاصل الفاصلة العشرية. |
| void [set_NumberGroupSeparator](./set_numbergroupseparator/)(const [String](../../system/string/)\&) | يضبط فاصل مجموعة الأرقام. |
| void [set_NumberGroupSizes](./set_numbergroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | يضبط عدد الأرقام لكل مجموعة. |
| void [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | يضبط نمط سالب الرقم. |
| void [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | يضبط عدد المنازل العشرية في قيم النسبة المئوية. |
| void [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const [String](../../system/string/)\&) | يضبط فاصل الفاصلة العشرية في قيم النسبة المئوية. |
| void [set_PercentGroupSeparator](./set_percentgroupseparator/)(const [String](../../system/string/)\&) | يضبط فاصل مجموعة القيم في النسبة المئوية. |
| void [set_PercentGroupSizes](./set_percentgroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | يضبط عدد الأرقام لكل مجموعة قيم النسبة المئوية. |
| void [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | يضبط نمط سالب النسبة المئوية. |
| void [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | يضبط نمط موجب النسبة المئوية. |
| void [set_PercentSymbol](./set_percentsymbol/)(const [String](../../system/string/)\&) | يضبط رمز النسبة المئوية. |
| void [set_PerMilleSymbol](./set_permillesymbol/)(const [String](../../system/string/)\&) | يضبط رمز الألفية. |
| void [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const [String](../../system/string/)\&) | يضبط رمز اللانهاية الموجبة. |
| void [set_PositiveSign](./set_positivesign/)(const [String](../../system/string/)\&) | يضبط العلامة الموجبة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n إلى مؤشر ضعيف (بدلاً من المشترك). يتيح تحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يعيد القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نسخة مماثلة لطريقة C# [Object.ToString()](../../system/object/tostring/). تمكّن تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [Object](../../system/object/)
* الفئة [IFormatProvider](../../system/iformatprovider/)
* الفئة [ICloneable](../../system/icloneable/)
* النطاق [System::Globalization](../)
* المكتبة [Aspose.Slides](../../)