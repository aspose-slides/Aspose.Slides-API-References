---
title: SoapHeaderAttribute
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يحدد رأس SOAP الذي يمكن للطريقة خدمة الويب XML أو عميل خدمة الويب XML معالجته. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم أبدًا بإنشاء مثال من هذا النوع على المكدس أو باستخدام العامل new، لأنه سيسبب أخطاء وقت تشغيل و/أو أخطاء تأكيد. يجب دائمًا لف هذه الفئة داخل مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 92
url: /ar/system.web.services.protocols/soapheaderattribute/
---
## فئة SoapHeaderAttribute

يحدد رأس SOAP الذي يمكن للطريقة خدمة XML [Web](../../system.web/) أو عميل خدمة XML [Web](../../system.web/) معالجته. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبداً بإنشاء مثال من هذا النوع على المكدس أو باستخدام المُعامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. دائمًا قم بلف هذه الفئة داخل مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريرها إلى الدوال كمعامل.

```cpp
class SoapHeaderAttribute : public System::Attribute
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | محاكاة مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبَر NaNين متساويين رغم أنه وفقًا للمعيار IEC 60559:1989 NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | محاكاة مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبَر NaNين متساويين رغم أنه وفقًا للمعيار IEC 60559:1989 NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [SoapHeaderDirection](../soapheaderdirection/) [get_Direction](./get_direction/)() | يحصل على اتجاه رأس SOAP. |
| [String](../../system/string/) [get_MemberName](./get_membername/)() | يحصل على اسم المتغيّر العضو في خدمة XML SOAP التي تُستخدم لاستلام محتويات رأس SOAP. |
| **bool** [get_Required](./get_required/)() | يحصل على قيمة تُشير إلى ما إذا كان يجب على مستقبل خدمة XML [Web](../../system.web/) أو عميل خدمة XML [Web](../../system.web/) فهم ومعالجة رأس SOAP. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| static [Object::ptr](../../system/object/ptr/) [GetCustomAttribute](../../system/attribute/getcustomattribute/)(const [TypeInfo](../../system/typeinfo/)\&, const [TypeInfo](../../system/typeinfo/)\&) | يعيد سمة مخصصة من نوع محدد مطبقة على النوع المحدد. |
| static [ArrayPtr](../../system/arrayptr/)\<[Object::ptr](../../system/object/ptr/)\> [GetCustomAttributes](../../system/attribute/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)\&) | يعيد جميع السمات المخصصة المطبقة على النوع المحدد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثلاً للنوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | بناء نسخة. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويفوض بناء نسخ الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويفوض بناء نسخ الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع قيم مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يخفّض عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Direction](./set_direction/)([SoapHeaderDirection](../soapheaderdirection/)) | يضبط اتجاه رأس SOAP. |
| void [set_MemberName](./set_membername/)([String](../../system/string/)) | يضبط اسم المتغيّر العضو في خدمة XML SOAP التي تُستخدم لاستلام محتويات رأس SOAP. |
| void [set_Required](./set_required/)(**bool**) | يضبط قيمة تُشير إلى ما إذا كان يجب على مستقبل خدمة XML [Web](../../system.web/) أو عميل خدمة XML [Web](../../system.web/) فهم ومعالجة رأس SOAP. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط المتغيّر القالب الـ n't مؤشرًا ضعيفًا (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
|  [SoapHeaderAttribute](./soapheaderattribute/)([String](../../system/string/)) | يبني مثلاً جديدًا. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [Attribute](../../system/attribute/)
* مساحة الاسم [System::Web::Services::Protocols](../)
* مكتبة [Aspose.Slides](../../)