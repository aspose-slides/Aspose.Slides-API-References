---
title: IFormatterConverter
second_title: Aspose.Slides للـ C++ مرجع API
description: "يوفر الاتصال بين نسخة من System::Runtime::Serialization::SerializationInfo والفئة التي يوفرها المُنسّق والتي تكون الأنسب لتحليل البيانات داخل System::Runtime::Serialization::SerializationInfo."
type: docs
weight: 27
url: /ar/system.runtime.serialization/iformatterconverter/
---
## فئة IFormatterConverter

يوفر الاتصال بين نسخة من [System::Runtime::Serialization::SerializationInfo](../serializationinfo/) والفئة التي يوفرها المُنسّق والتي تكون الأنسب لتحليل البيانات داخل [System::Runtime::Serialization::SerializationInfo](../serializationinfo/).

```cpp
class IFormatterConverter : public System::Object
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Convert](./convert/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, const [TypeInfo](../../system/typeinfo/)\&) | معلومات RTTI. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Convert](./convert/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [TypeCode](../../system/typecode/)) | يحوّل قيمة إلى [System::TypeCode](../../system/typecode/) المحدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaN ينتين متساويتين على الرغم من أن IEC 60559:1989 تنص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaN ينتين متساويتين على الرغم من أن IEC 60559:1989 تنص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عدّاد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يطبق قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ البنى الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ البنى الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات عن طريق المرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات عن طريق المرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجعية مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيطة النّ من القالب لتكون مؤشرًا ضعيفًا (بدلاً من مشترك). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعدّاد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual **bool** [ToBoolean](./toboolean/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحوّل قيمة إلى bool. |
| virtual **uint8_t** [ToByte](./tobyte/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحوّل قيمة إلى **uint8_t**. |
| virtual char16_t [ToChar](./tochar/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحوّل قيمة إلى char16_t. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحوّل قيمة إلى [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحوّل قيمة إلى [Decimal](../../system/decimal/). |
| virtual **double** [ToDouble](./todouble/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحوّل قيمة إلى double. |
| virtual **int16_t** [ToInt16](./toint16/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحوّل قيمة إلى **int16_t**. |
| virtual **int32_t** [ToInt32](./toint32/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحوّل قيمة إلى **int32_t**. |
| virtual **int64_t** [ToInt64](./toint64/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحوّل قيمة إلى **int64_t**. |
| virtual **int8_t** [ToSByte](./tosbyte/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحوّل قيمة إلى **int8_t**. |
| virtual **float** [ToSingle](./tosingle/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحوّل قيمة إلى float. |
| virtual [String](../../system/string/) [ToString](./tostring/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحوّل قيمة إلى [String](../../system/string/). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| virtual **uint16_t** [ToUInt16](./touint16/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحوّل قيمة إلى **uint16_t**. |
| virtual **uint32_t** [ToUInt32](./touint32/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحوّل قيمة إلى **uint32_t**. |
| virtual **uint64_t** [ToUInt64](./touint64/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحوّل قيمة إلى **uint64_t**. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق إلغاء قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [Object](../../system/object/)
* النطاق [System::Runtime::Serialization](../)
* المكتبة [Aspose.Slides](../../)