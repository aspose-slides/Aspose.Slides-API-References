---
title: SoapHeader
second_title: "Aspose.Slides للغة C++ – مرجع API"
description: "يمثل محتوى رأس SOAP. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقوم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء تأكيد. دائمًا غلف هذه الفئة بمؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط."
type: docs
weight: 79
url: /ar/system.web.services.protocols/soapheader/
---
## SoapHeader الفئة

يمثل محتوى رأس SOAP. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبدًا بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء تأكيد. دائمًا قم بتغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط.

```cpp
class SoapHeader : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سيمانتكس C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة عددية بنمط C# حيث تُconsider قيمة NaN واحدة مساوية للأخرى، رغم أنه وفقًا للمعيار IEC 60559:1989 فإن NaN لا تساوي أي قيمة، بما في ذلك NaN نفسها. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة عددية بنمط C# حيث تُconsider قيمة NaN واحدة مساوية للأخرى، رغم أنه وفقًا للمعيار IEC 60559:1989 فإن NaN لا تساوي أي قيمة، بما في ذلك NaN نفسها. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [String](../../system/string/) [get_Actor](./get_actor/)() | يحصل على URI لمستقبل رأس SOAP عند استخدام نسخة SOAP 1.1. |
| **bool** [get_DidUnderstand](./get_didunderstand/)() | يحصل على قيمة تشير إلى ما إذا تم معالجة رأس SOAP بشكل صحيح. |
| [String](../../system/string/) [get_EncodedMustUnderstand](./get_encodedmustunderstand/)() | يحصل على قيمة الخاصية 'mustUnderstand' عند استخدام نسخة SOAP 1.1. |
| [String](../../system/string/) [get_EncodedMustUnderstand12](./get_encodedmustunderstand12/)() | يحصل على قيمة الخاصية 'mustUnderstand' عند استخدام نسخة SOAP 1.2. |
| [String](../../system/string/) [get_EncodedRelay](./get_encodedrelay/)() | يحصل على تمثيل نصي لقيمة الخاصية 'relay'. |
| **bool** [get_MustUnderstand](./get_mustunderstand/)() | يحصل على قيمة تشير إلى ما إذا كان يجب فهم رأس SOAP. |
| **bool** [get_Relay](./get_relay/)() | يحصل على قيمة الخاصية 'relay'. |
| [String](../../system/string/) [get_Role](./get_role/)() | يحصل على URI لمستقبل رأس SOAP عند استخدام نسخة SOAP 1.2. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثالًا للنوع الموصوف بـ targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمراجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمراجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلسلة والـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Actor](./set_actor/)([String](../../system/string/)) | يضبط URI لمستقبل رأس SOAP عند استخدام نسخة SOAP 1.1. |
| void [set_DidUnderstand](./set_didunderstand/)(**bool**) | يضبط قيمة تشير إلى ما إذا تم معالجة رأس SOAP بشكل صحيح. |
| void [set_EncodedMustUnderstand](./set_encodedmustunderstand/)([String](../../system/string/)) | يضبط قيمة الخاصية 'mustUnderstand' عند استخدام نسخة SOAP 1.1. |
| void [set_EncodedMustUnderstand12](./set_encodedmustunderstand12/)([String](../../system/string/)) | يضبط قيمة الخاصية 'mustUnderstand' عند استخدام نسخة SOAP 1.2. |
| void [set_EncodedRelay](./set_encodedrelay/)([String](../../system/string/)) | يضبط تمثيلًا نصيًا لقيمة الخاصية 'relay'. |
| void [set_MustUnderstand](./set_mustunderstand/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب فهم رأس SOAP. |
| void [set_Relay](./set_relay/)(**bool**) | يضبط قيمة الخاصية 'relay'. |
| void [set_Role](./set_role/)([String](../../system/string/)) | يضبط URI لمستقبل رأس SOAP عند استخدام نسخة SOAP 1.2. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كإشارة ضعيفة (بدلاً من المشتركة). يتيح تبديل الإشارات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
|  [SoapHeader](./soapheader/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlElement](../../system.xml/xmlelement/)\>) | يبني مثيلًا جديدًا. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة نصية. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [Object](../../system/object/)
* النطاق [System::Web::Services::Protocols](../)
* المكتبة [Aspose.Slides](../../)