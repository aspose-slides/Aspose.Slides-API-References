---
title: SoapMessage
second_title: مرجع API Aspose.Slides للغة C++
description: "يمثل رسالة SOAP. يجب تخصيص كائنات هذه الفئة باستخدام دالة System::MakeObject() فقط. لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام العامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء التأكيد. احرص دائمًا على تغليف هذه الفئة بمؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 131
url: /ar/system.web.services.protocols/soapmessage/
---
## فئة SoapMessage

يمثل رسالة SOAP. يجب إنشاء كائنات هذه الفئة باستخدام دالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام العامل new، إذ سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة بمؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class SoapMessage : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| void [CollectHeaders](./collectheaders/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>, [SoapHeaderDirection](../soapheaderdirection/)) | يضبط مجموعة رؤوس SOAP الداخلية. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة الأعداد العائمة بأسلوب C# حيث يُعامل NaNانان كمتساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة الأعداد العائمة بأسلوب C# حيث يُعامل NaNانان كمتساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\> [FindHeader](./findheader/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>, const [TypeInfo](../../system/typeinfo/)\&) | يبحث عن خريطة الرأس حسب نوع الرأس المحدد. |
| virtual [String](../../system/string/) [get_Action](./get_action/)() | إرجاع قيمة خاصية 'SOAPAction'. |
| [String](../../system/string/) [get_ContentEncoding](./get_contentencoding/)() | يحصل على قيمة رأس 'Content-Encoding'. |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() | يحصل على قيمة رأس 'Content-Type'. |
| [SoapException](../soapexception/) [get_Exception](./get_exception/)() | يحصل على الاستثناء الذي يتم إلقاؤه بواسطة طريقة الخدمة XML [Web](../../system.web/). |
| [System::SharedPtr](../../system/sharedptr/)\<[SoapHeaderCollection](../soapheadercollection/)\> [get_Headers](./get_headers/)() | إرجاع مجموعة رؤوس SOAP. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [get_InParameters](./get_inparameters/)() | يحصل على المعلمات الممررة إلى طريقة الخدمة XML [Web](../../system.web/). |
| **bool** [get_IsSoap12](./get_issoap12/)() | إرجاع قيمة تشير إلى ما إذا كان يُستخدم إصدار SOAP 1.2. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [get_OutParameters](./get_outparameters/)() | يحصل على معلمات الإخراج الممررة إلى طريقة الخدمة XML [Web](../../system.web/). |
| virtual [SoapProtocolVersion](../soapprotocolversion/) [get_SoapVersion](./get_soapversion/)() | إرجاع إصدار SOAP المستخدم. |
| [SoapMessageStage](../soapmessagestage/) [get_Stage](./get_stage/)() | يحصل على مرحلة معالجة رسالة SOAP. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [get_Stream](./get_stream/)() | يحصل على التدفق الذي يحتوي على بيانات رسالة SOAP. |
| virtual [String](../../system/string/) [get_Url](./get_url/)() | إرجاع عنوان URL الخاص بخدمة XML [Web](../../system.web/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تشابه طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetInParameterValue](./getinparametervalue/)(**int32_t**) | يحصل على قيمة معلمة الإدخال في الفهرس المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetOutParameterValue](./getoutparametervalue/)(**int32_t**) | يحصل على قيمة معلمة الإخراج في الفهرس المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetReturnValue](./getreturnvalue/)() | يحصل على قيمة الإرجاع لطريقة الخدمة XML [Web](../../system.web/). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تشابه استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بواسطة targetType. تشابه مشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعها مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تشابه طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالات السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجع المشترك بالقيمة المحددة. |
| void [set_ContentEncoding](./set_contentencoding/)([String](../../system/string/)) | يضبط قيمة رأس 'Content-Encoding'. |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) | يضبط قيمة رأس 'Content-Type'. |
| void [set_InParameters](./set_inparameters/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>) | يضبط المعلمات الممررة إلى طريقة الخدمة XML [Web](../../system.web/). |
| void [set_InternalStream](./set_internalstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | يضبط التدفق الذي يحتوي على بيانات رسالة SOAP. |
| void [set_OutParameters](./set_outparameters/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>) | يضبط معلمات الإخراج الممررة إلى طريقة الخدمة XML [Web](../../system.web/). |
| void [SetException](./setexception/)([SoapException](../soapexception/)) | يضبط الاستثناء الذي يتم إلقاؤه بواسطة طريقة الخدمة XML [Web](../../system.web/). |
| void [SetHeaders](./setheaders/)([System::SharedPtr](../../system/sharedptr/)\<[SoapHeaderCollection](../soapheadercollection/)\>) | يضبط مجموعة رؤوس SOAP. |
| void [SetStage](./setstage/)([SoapMessageStage](../soapmessagestage/)) | يضبط مرحلة معالجة رسالة SOAP. |
| void [SetStream](./setstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | يضبط التدفق الذي يحتوي على بيانات رسالة SOAP. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يحدد الوسيط القالب رقم n مؤشراً ضعيفاً (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويُعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
|  [SoapMessage](./soapmessage/)() | ينشئ مثيلًا جديدًا. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تشابه طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعها مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| void [UpdateHeaderValues](./updateheadervalues/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>) | تحديث مجموعة رؤوس SOAP الداخلية. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [Object](../../system/object/)
* مساحة الاسم [System::Web::Services::Protocols](../)
* مكتبة [Aspose.Slides](../../)