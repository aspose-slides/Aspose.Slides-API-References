---
title: IConvertible
second_title: مرجع API Aspose.Slides للـ C++
description: "يعرّف طرقًا تحول قيمة النوع المرجعي أو القيمي الذي يُطبق إلى نوع زمن تشغيل اللغة المشتركة الذي لديه قيمة مكافئة. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم أبدًا بإنشاء مثيل من هذا النوع على المكدس أو باستخدام operator new، لأن ذلك سيؤدي إلى أخطاء وقت تشغيل و/أو أخطاء تأكيد. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كوسيطة."
type: docs
weight: 937
url: /ar/system/iconvertible/
---
## IConvertible فئة

يُعرِّف طرقًا تُحوِّل قيمة النوع المرجعي أو النوع القيمي الذي يُنفّذ إلى نوع زمن تشغيل اللغة المشتركة الذي يمتلك قيمة مكافئة. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../makeobject/). لا تقم أبدًا بإنشاء مثيل من هذا النوع على المكدس أو باستخدام operator new، لأن ذلك سيؤدي إلى أخطاء وقت تشغيل و/أو أعطال في التأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيطة.

```cpp
class IConvertible : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | يقلّد مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبَر NaNانين متساويين على الرغم من أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | يقلّد مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبَر NaNانين متساويين على الرغم من أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | نظير دالة C# [Object.GetHashCode()](../object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../object/gettype/). |
| virtual [System::TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() | يعيد رمز النوع لهذا المثيل. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلًا للنوع الموضّح بـ targetType. نظير مشغل C# 'is'. |
| void [Lock](../object/lock/)() | يُنفّذ قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | نظير دالة C# [Object.MemberwiseClone()](../object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../object/object/)() | يُنشئ كائنًا. يتهيئ جميع بنى البيانات الداخلية. |
|  [Object](../object/object/)([Object](../object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مقابل nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n't إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual **bool** [ToBoolean](./toboolean/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | يحوّل قيمة هذا المثيل إلى قيمة [Boolean](../boolean/) مكافئة باستخدام معلومات التنسيق الخاصة بالثقافة المحددة. |
| virtual **uint8_t** [ToByte](./tobyte/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | يحوّل قيمة هذا المثيل إلى عدد 8-bit من نوع uint32_teger مكافئ باستخدام معلومات التنسيق الخاصة بالثقافة المحددة. |
| virtual char_t [ToChar](./tochar/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | يحوّل قيمة هذا المثيل إلى حرف Unicode مكافئ باستخدام معلومات التنسيق الخاصة بالثقافة المحددة. |
| virtual [System::DateTime](../datetime/) [ToDateTime](./todatetime/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | يحوّل قيمة هذا المثيل إلى [System::DateTime](../datetime/) مكافئ باستخدام معلومات التنسيق الخاصة بالثقافة المحددة. |
| virtual [System::Decimal](../decimal/) [ToDecimal](./todecimal/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | يحوّل قيمة هذا المثيل إلى رقم [System::Decimal](../decimal/) مكافئ باستخدام معلومات التنسيق الخاصة بالثقافة المحددة. |
| virtual **double** [ToDouble](./todouble/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | يحوّل قيمة هذا المثيل إلى عدد عائم مزدوج الدقة مكافئ باستخدام معلومات التنسيق الخاصة بالثقافة المحددة. |
| virtual **int16_t** [ToInt16](./toint16/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | يحوّل قيمة هذا المثيل إلى عدد صحيح موقّع 16-bit مكافئ باستخدام معلومات التنسيق الخاصة بالثقافة المحددة. |
| virtual **int32_t** [ToInt32](./toint32/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | يحوّل قيمة هذا المثيل إلى عدد صحيح موقّع 32-bit مكافئ باستخدام معلومات التنسيق الخاصة بالثقافة المحددة. |
| virtual **int64_t** [ToInt64](./toint64/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | يحوّل قيمة هذا المثيل إلى عدد صحيح موقّع 64-bit مكافئ باستخدام معلومات التنسيق الخاصة بالثقافة المحددة. |
| virtual **int8_t** [ToSByte](./tosbyte/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | يحوّل قيمة هذا المثيل إلى عدد صحيح موقّع 8-bit مكافئ باستخدام معلومات التنسيق الخاصة بالثقافة المحددة. |
| virtual **float** [ToSingle](./tosingle/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | يحوّل قيمة هذا المثيل إلى عدد عائم ذو دقة مفردة مكافئ باستخدام معلومات التنسيق الخاصة بالثقافة المحددة. |
| virtual [System::String](../string/) [ToString](./tostring/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | يحوّل قيمة هذا المثيل إلى [System::String](../string/) مكافئ باستخدام معلومات التنسيق الخاصة بالثقافة المحددة. |
| virtual [String](../string/) [ToString](./tostring/)() const | نظير دالة C# [Object.ToString()](../object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| virtual [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\> [ToType](./totype/)(const [TypeInfo](../typeinfo/)\&, [System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | يحوّل قيمة هذا المثيل إلى [System::Object](../object/) من النوع System::Type المحدد الذي يمتلك قيمة مكافئة، باستخدام معلومات التنسيق الخاصة بالثقافة المحددة. |
| virtual **uint16_t** [ToUInt16](./touint16/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | يحوّل قيمة هذا المثيل إلى عدد 16-bit من نوع uint32_teger مكافئ باستخدام معلومات التنسيق الخاصة بالثقافة المحددة. |
| virtual **uint32_t** [ToUInt32](./touint32/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | يحوّل قيمة هذا المثيل إلى عدد 32-bit من نوع uint32_teger مكافئ باستخدام معلومات التنسيق الخاصة بالثقافة المحددة. |
| virtual **uint64_t** [ToUInt64](./touint64/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | يحوّل قيمة هذا المثيل إلى عدد 64-bit من نوع uint32_teger مكافئ باستخدام معلومات التنسيق الخاصة بالثقافة المحددة. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | يُنفّذ بنية C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | يُنفّذ إلغاء قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضا

* فئة [Object](../object/)
* مساحة الاسم [System](../)
* مكتبة [Aspose.Slides](../../)