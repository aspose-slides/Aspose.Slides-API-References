---
title: TextWriter
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "فئة أساسية للفئات التي تمثل كاتبين يكتبون تسلسلات من الأحرف إلى وجهات مختلفة. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تُنشئ مثيلًا من هذا النوع على المكدس أو باستخدام المشغّل new، لأن ذلك سيسبّب أخطاءً وقت التشغيل أو أخطاء تأكيد. دائمًا غلف هذه الفئة في المؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 443
url: /ar/system.io/textwriter/
---
## فئة TextWriter

فئة أساسية للفئات التي تمثّل كاتِبين يكتبون سلاسل من الأحرف إلى وجهات مختلفة. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تُنشئ مثيلًا من هذا النوع على المكدس أو باستخدام المشغّل new، لأن ذلك سيسبّب أخطاءً وقت التشغيل أو أخطاء تأكيد. دائمًا غلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class TextWriter : public System::IDisposable
```

## طرق

| الطريقة | الوصف |
| --- | --- |
| virtual void [Close](./close/)() | يغلق الدفق ويحرّر الموارد المكتسبة. |
| void [Dispose](./dispose/)() override | يطلق جميع الموارد المستخدمة من قبل الكائن الحالي ويغلق الدفق الأساسي. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر NaN اثنان متساويين بالرغم من أن معيار IEC 60559:1989 يوضح أن NaN لا يساوي أي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر NaN اثنان متساويين بالرغم من أن معيار IEC 60559:1989 يوضح أن NaN لا يساوي أي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual void [Flush](./flush/)() | يفرغ محتوى المخزن المؤقت إلى الدفق الأساسي. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | يرجع الترميز المستخدم حاليًا. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](./get_formatprovider/)() const | يرجع كائن [IFormatProvider](../../system/iformatprovider/) المستخدم حاليًا. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](./get_formatprovider/)() | يرجع كائن [IFormatProvider](../../system/iformatprovider/) المستخدم حاليًا. |
| virtual [System::String](../../system/string/) [get_NewLine](./get_newline/)() const | يرجع سلسلة محدد سطر. |
| [String](../../system/string/) [get_NewLine](./get_newline/)() | يرجع سلسلة محدد سطر. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | يُنشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع قيم مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_NewLine](./set_newline/)(const [System::String](../../system/string/)\&) | يضبط سلسلة محدد سطر. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | يكتب تمثيل السلسلة للكائن المحدد إلى الدفق. |
| virtual void [Write](./write/)(**bool**) | يكتب تمثيل السلسلة للقيمة البوليانية المحددة إلى الدفق. |
| virtual void [Write](./write/)(char_t) | يكتب الحرف المحدد إلى الدفق. |
| virtual void [Write](./write/)([Decimal](../../system/decimal/)) | يكتب تمثيل السلسلة للكائن [Decimal](../../system/decimal/) المحدد إلى الدفق. |
| virtual void [Write](./write/)(**double**) | يكتب تمثيل السلسلة للقيمة ذات الدقة المزدوجة المحددة إلى الدفق. |
| virtual void [Write](./write/)(int) | يكتب تمثيل السلسلة للقيمة الصحيحة 32-بت المحددة إلى الدفق. |
| virtual void [Write](./write/)(**int64_t**) | يكتب تمثيل السلسلة للقيمة الصحيحة 64-بت المحددة إلى الدفق. |
| virtual void [Write](./write/)(**float**) | يكتب تمثيل السلسلة للقيمة ذات الدقة الأحادية المحددة إلى الدفق. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | يكتب السلسلة المحددة إلى الدفق. |
| virtual void [Write](./write/)(**uint32_t**) | يكتب تمثيل السلسلة للقيمة غير الموقعة 32-بت المحددة إلى الدفق. |
| virtual void [Write](./write/)(**uint64_t**) | يكتب تمثيل السلسلة للقيمة غير الموقعة 64-بت المحددة إلى الدفق. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | يكتب جميع الحروف من المصفوفة المحددة إلى الدفق. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | يكتب النطاق الفرعي المحدد من حروف UTF-16 من المصفوفة المحددة إلى الدفق. |
| virtual void [Write](./write/)(const char_t *) | يكتب السلسلة C المحددة إلى الدفق. |
| virtual void [Write](./write/)(const [TypeInfo](../../system/typeinfo/)\&) | يكتب تمثيل السلسلة للكائن [TypeInfo](../../system/typeinfo/) المحدد إلى الدفق. |
| void [Write](./write/)(const [String](../../system/string/)\&, const TArgs\&...) | يكتب القيم المحددة بصيغة محددة إلى الدفق. |
| virtual void [WriteLine](./writeline/)() | يكتب أحرف محدد السطر إلى الدفق. |
| virtual void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | يكتب تمثيل السلسلة للكائن المحدد يليها أحرف محدد السطر إلى الدفق. |
| virtual void [WriteLine](./writeline/)(**bool**) | يكتب تمثيل السلسلة للقيمة البوليانية يليها أحرف محدد السطر إلى الدفق. |
| virtual void [WriteLine](./writeline/)(char_t) | يكتب الحرف المحدد يليها أحرف محدد السطر إلى الدفق. |
| virtual void [WriteLine](./writeline/)([Decimal](../../system/decimal/)) | يكتب تمثيل السلسلة للكائن [Decimal](../../system/decimal/) المحدد يليها أحرف محدد السطر إلى الدفق. |
| virtual void [WriteLine](./writeline/)(**double**) | يكتب تمثيل السلسلة للقيمة ذات الدقة المزدوجة المحددة يليها أحرف محدد السطر إلى الدفق. |
| virtual void [WriteLine](./writeline/)(int) | يكتب تمثيل السلسلة للقيمة الصحيحة 32-بت المحددة يليها أحرف محدد السطر إلى الدفق. |
| virtual void [WriteLine](./writeline/)(**int64_t**) | يكتب تمثيل السلسلة للقيمة الصحيحة 64-بت المحددة يليها أحرف محدد السطر إلى الدفق. |
| virtual void [WriteLine](./writeline/)(**float**) | يكتب تمثيل السلسلة للقيمة ذات الدقة الأحادية المحددة يليها أحرف محدد السطر إلى الدفق. |
| virtual void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | يكتب السلسلة المحددة يليها أحرف محدد السطر إلى الدفق. |
| virtual void [WriteLine](./writeline/)(**uint32_t**) | يكتب تمثيل السلسلة للقيمة غير الموقعة 32-بت المحددة يليها أحرف محدد السطر إلى الدفق. |
| virtual void [WriteLine](./writeline/)(**uint64_t**) | يكتب تمثيل السلسلة للقيمة غير الموقعة 64-بت المحددة يليها أحرف محدد السطر إلى الدفق. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | يكتب جميع الحروف من المصفوفة المحددة يليها أحرف محدد السطر إلى الدفق. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | يكتب النطاق الفرعي المحدد من حروف UTF-16 من المصفوفة المحددة يليها أحرف محدد السطر إلى الدفق. |
| virtual void [WriteLine](./writeline/)(const char_t *) | يكتب السلسلة C المحددة يليها أحرف محدد السطر إلى الدفق. |
| virtual void [WriteLine](./writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | يكتب تمثيل السلسلة للكائن [TypeInfo](../../system/typeinfo/) المحدد يليها أحرف محدد السطر إلى الدفق. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | يكتب القيم المحددة بصيغة محددة يليها أحرف محدد السطر إلى الدفق. |
| virtual [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |
| virtual [~TextWriter](./~textwriter/)() | المدمر. |

## تعريفات النوع

| الاسم المستعار | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار لمؤشر مشترك إلى هذه الفئة. |

## انظر أيضًا

* الفئة [IDisposable](../../system/idisposable/)
* النطاق [System::IO](../)
* المكتبة [Aspose.Slides](../../)