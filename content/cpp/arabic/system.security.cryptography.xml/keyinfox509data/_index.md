---
title: KeyInfoX509Data
second_title: مرجع API لبرنامج Aspose.Slides للغة C++
description: "يمثل عنصر 'X509Data'. يحتوي على معلومات شهادة X.509v3 المتعلقة بمفتاح التحقق أو التشفير. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت تشغيل و/أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 66
url: /ar/system.security.cryptography.xml/keyinfox509data/
---
## KeyInfoX509Data فئة


يمثل عنصر 'X509Data'. يحتوي على معلومات شهادة X.509v3 المتعلقة بمفتاح التحقق أو التشفير. يجب إنشاء كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبداً بإنشاء مثال من هذا النوع على المكدس أو باستخدام المُعامل new، حيث سيتسبب ذلك في أخطاء وقت تشغيل و/أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط.

```cpp
class KeyInfoX509Data : public System::Security::Cryptography::Xml::KeyInfoClause
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| void [AddCertificate](./addcertificate/)([SharedPtr](../../system/sharedptr/)\<[X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\>) |  |
| void [AddIssuerSerial](./addissuerserial/)([String](../../system/string/), [String](../../system/string/)) |  |
| void [AddSubjectKeyId](./addsubjectkeyid/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) |  |
| void [AddSubjectName](./addsubjectname/)([String](../../system/string/)) |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي نمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي نمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يتم اعتبار NaNين متساويين على الرغم من أنه وفقًا لمعيار IEC 60559:1989 لا يعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يتم اعتبار NaNين متساويين على الرغم من أنه وفقًا لمعيار IEC 60559:1989 لا يعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للأغراض الداخلية فقط. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[SharedPtr](../../system/sharedptr/)\<[X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\>\>\> [get_Certificates](./get_certificates/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[X509IssuerSerial](../x509issuerserial/)\>\> [get_IssuerSerials](./get_issuerserials/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\>\> [get_SubjectKeyIds](./get_subjectkeyids/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[String](../../system/string/)\>\> [get_SubjectNames](./get_subjectnames/)() |  |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لدالة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الحقيقي للكائن. مماثل للاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlElement](../../system.xml/xmlelement/)\> [GetXml](./getxml/)() override |  |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlElement](../../system.xml/xmlelement/)\> [GetXml](./getxml/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlDocument](../../system.xml/xmldocument/)\>) override |  |
| void [InternalAddIssuerSerial](./internaladdissuerserial/)([String](../../system/string/), [String](../../system/string/)) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق ما إذا كان الكائن يمثل مثيلًا لنوع يصفه targetType. مماثل للمشغل C# 'is'. |
|  [KeyInfoX509Data](./keyinfox509data/)() |  |
| void [LoadXml](./loadxml/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlElement](../../system.xml/xmlelement/)\>) override |  |
| void [Lock](../../system/object/lock/)() | يطبق قفل تعبير C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لدالة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا يقوم بنسخ أي شيء، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا يقوم بنسخ أي شيء، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلص عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط معامل القالب رقم n كمؤشر ضعيف (بدلاً من مشترك). يتيح تبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد المرجع المشترك ويعيده. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لدالة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق فك قفل تعبير C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## راجع أيضًا

* الفئة [KeyInfoClause](../keyinfoclause/)
* المجال [System::Security::Cryptography::Xml](../)
* المكتبة [Aspose.Slides](../../)