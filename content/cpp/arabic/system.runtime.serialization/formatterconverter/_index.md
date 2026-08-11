---
title: FormatterConverter
second_title: Aspose.Slides للغة C++ مرجع API
description: "يمثل تنفيذًا أساسيًا لواجهة System::Runtime::Serialization::IFormatterConverter."
type: docs
weight: 14
url: /ar/system.runtime.serialization/formatterconverter/
---
## FormatterConverter فئة

Represents a base implementation of the [System::Runtime::Serialization::IFormatterConverter](../iformatterconverter/) interface.

```cpp
class FormatterConverter : public System::Runtime::Serialization::IFormatterConverter
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Convert](./convert/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, const [TypeInfo](../../system/typeinfo/)\&) override | يحول قيمة إلى [System::TypeInfo](../../system/typeinfo/) المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Convert](./convert/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [TypeCode](../../system/typecode/)) override | يحول قيمة إلى [System::TypeCode](../../system/typecode/) المحدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات [Object.Equals](../../system/object/equals/) في C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNين متساويين بالرغم من أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNين متساويين بالرغم من أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة [Object.GetHashCode()](../../system/object/gethashcode/) في C#. يُمكّن من تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء [System.Object.GetType()](../../system/object/gettype/) في C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير عامل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | يفّعل قفل عبارة lock() في C#. استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة [Object.MemberwiseClone()](../../system/object/memberwiseclone/) في C#. يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع تراكيب البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، وإنما يهيئ كائنًا جديدًا ويُمكّن من إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل إسناد. لا ينسخ أي شيء فعليًا، وإنما يهيئ كائنًا جديدًا ويُمكّن من إنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع الضعف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| **bool** [ToBoolean](./toboolean/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يحول قيمة إلى bool. |
| **uint8_t** [ToByte](./tobyte/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يحول قيمة إلى **uint8_t**. |
| char16_t [ToChar](./tochar/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يحول قيمة إلى char16_t. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يحول قيمة إلى [DateTime](../../system/datetime/). |
| [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يحول قيمة إلى [Decimal](../../system/decimal/). |
| **double** [ToDouble](./todouble/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يحول قيمة إلى double. |
| **int16_t** [ToInt16](./toint16/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يحول قيمة إلى **int16_t**. |
| **int32_t** [ToInt32](./toint32/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يحول قيمة إلى **int32_t**. |
| **int64_t** [ToInt64](./toint64/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يحول قيمة إلى **int64_t**. |
| **int8_t** [ToSByte](./tosbyte/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يحول قيمة إلى **int8_t**. |
| **float** [ToSingle](./tosingle/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يحول قيمة إلى float. |
| [String](../../system/string/) [ToString](./tostring/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يحول قيمة إلى [String](../../system/string/). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة [Object.ToString()](../../system/object/tostring/) في C#. يتيح تحويل الكائنات المخصصة إلى نص. |
| **uint16_t** [ToUInt16](./touint16/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يحول قيمة إلى **uint16_t**. |
| **uint32_t** [ToUInt32](./touint32/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يحول قيمة إلى **uint32_t**. |
| **uint64_t** [ToUInt64](./touint64/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يحول قيمة إلى **uint64_t**. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يفّعل بنية typeof([System.Object](../../system/object/)) في C#. |
| void [Unlock](../../system/object/unlock/)() | يفّعل إلغاء قفل عبارة lock() في C#. استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع تراكيب البيانات الداخلية. |

## انظر أيضًا

* فئة [IFormatterConverter](../iformatterconverter/)
* نطاق [System::Runtime::Serialization](../)
* مكتبة [Aspose.Slides](../../)