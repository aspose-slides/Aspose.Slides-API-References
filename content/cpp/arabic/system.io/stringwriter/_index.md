---
title: StringWriter
second_title: Aspose.Slides لـ C++ مرجع API
description: "تنفّذ TextWriter يكتب المعلومات إلى سلسلة. يجب إنشاء كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم أبداً بإنشاء مثيل من هذا النوع على المكدس أو باستخدام معامل new، لأن ذلك سيسبّب أخطاء وقت التشغيل أو أخطاء تأكيد. يجب دائماً تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كوسيط."
type: docs
weight: 417
url: /ar/system.io/stringwriter/
---
## StringWriter فئة

تنفذ [TextWriter](../textwriter/) يكتب المعلومات إلى سلسلة. يجب إنشاء كائنات هذه الفئة باستخدام دالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبداً بإنشاء مثيل من هذا النوع على مكدس أو باستخدام عامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. دائمًا قم بلف هذه الفئة إلى مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط.

```cpp
class StringWriter : public System::IO::TextWriter
```

## الطرق

| Method | Description |
| --- | --- |
| virtual void [Close](../textwriter/close/)() | يغلق التدفق ويحرر الموارد المكتسبة. |
| void [Dispose](../textwriter/dispose/)() override | يطلق سراح جميع الموارد المستخدمة بواسطة الكائن الحالي ويغلق التدفق الأساسي. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوكيات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي على نمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي على نمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | تحاكي مقارنة النقطة العائمة على نمط C# حيث تُعتبر NaN اثنان متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | تحاكي مقارنة النقطة العائمة على نمط C# حيث تُعتبر NaN اثنان متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual void [Flush](../textwriter/flush/)() | يفرغ محتوى المخزن المؤقت إلى التدفق الأساسي. |
| [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | يرجع الترميز المستخدم حالياً. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | يرجع كائن [IFormatProvider](../../system/iformatprovider/) المستخدم حالياً. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | يرجع كائن [IFormatProvider](../../system/iformatprovider/) المستخدم حالياً. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | يرجع سلسلة محدد سطر. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | يرجع سلسلة محدد سطر. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مقابل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\> [GetStringBuilder](./getstringbuilder/)() | يرجع StringBuilder المستخدم حالياً. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مقابلة لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلاً للنوع الموصوف بواسطة targetType. مقابلة لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل تعبير C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مقابل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يتهيء جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | معامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | يضبط سلسلة محدد سطر. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط معامل القالب رقم n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | يبني مثيلاً جديدًا من [StringWriter](./) باستخدام StringBuilder و [IFormatProvider](../../system/iformatprovider/) المحددين. |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | يبني مثيلاً جديدًا من [StringWriter](./) باستخدام StringBuilder و [IFormatProvider](../../system/iformatprovider/) من الثقافة الحالية. |
|  [StringWriter](./stringwriter/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | يبني مثيلاً جديدًا من [StringWriter](./) باستخدام [IFormatProvider](../../system/iformatprovider/) المحدد. |
|  [StringWriter](./stringwriter/)() | يبني مثيلاً جديدًا من [StringWriter](./) باستخدام [IFormatProvider](../../system/iformatprovider/) من الثقافة الحالية. |
| [String](../../system/string/) [ToString](./tostring/)() const override | يرجع السلسلة الأساسية. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل تعبير C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [Write](./write/)(char_t) override | يكتب الحرف المحدد إلى التدفق. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | يكتب النطاق الفرعي المحدد من الأحرف من مصفوفة الأحرف المحددة إلى التدفق. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | يكتب السلسلة المحددة إلى التدفق. |
| virtual void [Write](../textwriter/write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | يكتب تمثيل السلسلة للكائن المحدد إلى التدفق. |
| virtual void [Write](../textwriter/write/)(**bool**) | يكتب تمثيل السلسلة للقيمة المنطقية المحددة إلى التدفق. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | يكتب تمثيل السلسلة للكائن [Decimal](../../system/decimal/) المحدد إلى التدفق. |
| virtual void [Write](../textwriter/write/)(**double**) | يكتب تمثيل السلسلة للقيمة العشرية ذات الدقة المضاعفة المحددة إلى التدفق. |
| virtual void [Write](../textwriter/write/)(int) | يكتب تمثيل السلسلة للقيمة الصحيحة 32-بت المحددة إلى التدفق. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | يكتب تمثيل السلسلة للقيمة الصحيحة 64-بت المحددة إلى التدفق. |
| virtual void [Write](../textwriter/write/)(**float**) | يكتب تمثيل السلسلة للقيمة العائمة ذات الدقة المفردة المحددة إلى التدفق. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | يكتب تمثيل السلسلة للقيمة الصحيحة غير الموقعة 32-بت المحددة إلى التدفق. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | يكتب تمثيل السلسلة للقيمة الصحيحة غير الموقعة 64-بت المحددة إلى التدفق. |
| virtual void [Write](../textwriter/write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | يكتب جميع الأحرف من المصفوفة المحددة إلى التدفق. |
| virtual void [Write](../textwriter/write/)(const char_t *) | يكتب سلسلة C المحددة إلى التدفق. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | يكتب تمثيل السلسلة للكائن [TypeInfo](../../system/typeinfo/) المحدد إلى التدفق. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | يكتب القيم المحددة بتنسيق وفق الصيغة المحددة إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)() | يكتب أحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | يكتب تمثيل السلسلة للكائن المحدد متبوعًا بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | يكتب تمثيل السلسلة للقيمة المنطقية المحددة متبوعًا بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | يكتب الحرف المحدد متبوعًا بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | يكتب تمثيل السلسلة للكائن [Decimal](../../system/decimal/) المحدد متبوعًا بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | يكتب تمثيل السلسلة للقيمة العشرية ذات الدقة المضاعفة المحددة متبوعًا بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | يكتب تمثيل السلسلة للقيمة الصحيحة 32-بت المحددة متبوعًا بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | يكتب تمثيل السلسلة للقيمة الصحيحة 64-بت المحددة متبوعًا بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | يكتب تمثيل السلسلة للقيمة العائمة ذات الدقة المفردة المحددة متبوعًا بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&) | يكتب السلسلة المحددة متبوعًا بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | يكتب تمثيل السلسلة للقيمة الصحيحة غير الموقعة 32-بت المحددة متبوعًا بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | يكتب تمثيل السلسلة للقيمة الصحيحة غير الموقعة 64-بت المحددة متبوعًا بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | يكتب جميع الأحرف من المصفوفة المحددة متبوعًا بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | يكتب النطاق الفرعي المحدد من أحرف UTF-16 من مصفوفة الأحرف المحددة متبوعًا بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)(const char_t *) | يكتب سلسلة C المحددة متبوعًا بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | يكتب تمثيل السلسلة للكائن [TypeInfo](../../system/typeinfo/) المحدد متبوعًا بأحرف محدد السطر إلى التدفق. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | يكتب القيم المحددة بتنسيق وفق الصيغة المحددة متبوعًا بأحرف محدد السطر إلى التدفق. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | المدمر. |
## أنظر أيضًا

* الفئة [TextWriter](../textwriter/)
* النطاق [System::IO](../)
* المكتبة [Aspose.Slides](../../)