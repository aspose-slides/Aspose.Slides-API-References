---
title: UriBuilder
second_title: Aspose.Slides للغة C++ مرجع API
description: "توفر طرقًا لإنشاء وتعديل معرفات الموارد العالمية (URIs). يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أعطال تأكيدية. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 1405
url: /ar/system/uribuilder/
---
## فئة UriBuilder

توفر طرقًا لإنشاء وتعديل معرفات الموارد العالمية (URIs). يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../makeobject/) فقط. لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أعطال تأكيدية. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class UriBuilder : public System::Object
```

## الأساليب

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبر NaNانان مساويين رغم أن IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبر NaNانان مساويين رغم أن IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| [String](../string/) [get_Scheme](./get_scheme/)() const | يعيد المخطط (scheme) الخاص بـ URI الذي أنشأه الكائن الحالي. |
| [SharedPtr](../sharedptr/)\<[Uri](../uri/)\> [get_Uri](./get_uri/)() const | يعيد كائن [Uri](../uri/) الذي أنشأه الكائن الحالي. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | يحصل على بنية بيانات عداد الإشارة المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../object/gethashcode/). يتيح تجزئة (hashing) الكائنات المخصصة. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن المراقبة [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../object/object/)() | ينشئ كائنًا. يتهيء جميع بنى البيانات الداخلية. |
|  [Object](../object/object/)([Object](../object/) const\&) | مُنشئ نسخة. لا ينسخ أي شيء فعلاً، بل يتهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعلاً، بل يتهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع قيم بالإشارة إلى nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشتركة بالقيمة المحددة. |
| void [set_Port](./set_port/)(int) | يحدد رقم المنفذ لـ URI. |
| void [set_Scheme](./set_scheme/)(const [String](../string/)\&) | يحدد مخطط URI الذي أنشأه الكائن الحالي إلى القيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | يعيّن الوسيط القالبي n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | يزداد عداد الإشارة المشتركة. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ينقص عداد الإشارة المشتركة ويعيد قيمته. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | يعيد تمثيل السلسلة لـ URI الذي أنشأه الكائن الحالي. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ينفّذ بناء C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن المراقبة [LockContext](../lockcontext/). |
|  [UriBuilder](./uribuilder/)(const [String](../string/)\&) | ينشئ كائن [UriBuilder](./) يمثل الـ URI المحدد. |
|  [UriBuilder](./uribuilder/)(const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\&) | ينشئ كائن [UriBuilder](./) يمثل الـ URI المحدد. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | يزداد عداد الإشارة الضعيفة. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضاً

* فئة [Object](../object/)
* نطاق [System](../)
* مكتبة [Aspose.Slides](../../)