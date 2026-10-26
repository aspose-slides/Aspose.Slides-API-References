---
title: ServicePointManager
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: "يدير مراحل دورة الحياة (الإنشاء، الصيانة، والحذف) لنسخ فئة ServicePoint. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم أبداً بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيسبب ذلك أخطاء وقت التشغيل أو أخطاء التأكيد. دائمًا قم بتغليف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 430
url: /ar/system.net/servicepointmanager/
---
## ServicePointManager فئة


يدير مراحل دورة الحياة (الإنشاء، الصيانة، والحذف) لنسخ فئة [ServicePoint](../servicepoint/). يجب تخصيص كائنات هذه الفئة فقط باستخدام دالة [System::MakeObject()](../../system/makeobject/). لا تقم أبداً بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيتسبب ذلك في حدوث أخطاء وقت التشغيل و/أو أخطاء التأكيد. قم دائماً بتغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class ServicePointManager : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُ considered NaNانين مساويتين رغم أنه وفقًا لـ IEC 60559:1989 فإن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُ considered NaNانين مساويتين رغم أنه وفقًا لـ IEC 60559:1989 فإن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للأغراض الداخلية فقط. |
| static [System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\> [get_CertificatePolicy](./get_certificatepolicy/)() | يحصل على سياسة الشهادة. |
| static **bool** [get_CheckCertificateRevocationList](./get_checkcertificaterevocationlist/)() | يحصل على قيمة تشير إلى ما إذا كان يجب فحص الشهادة مقابل قائمة إبطال صلاحية سلطة الشهادات. |
| static **int32_t** [get_DefaultConnectionLimit](./get_defaultconnectionlimit/)() | يحصل على الحد الأقصى لعدد الاتصالات المتزامنة المسموح بها من قبل نسخ ServicePoint-class. |
| static **int32_t** [get_DnsRefreshTimeout](./get_dnsrefreshtimeout/)() | يحصل على مهلة بالمليثانية يتم خلالها اعتبار حل DNS صالحًا. |
| static **bool** [get_EnableDnsRoundRobin](./get_enablednsroundrobin/)() | يحصل على قيمة تشير إلى ما إذا كان حل DNS يتناوب بين عناوين IP القابلة للتطبيق. |
| static [System::Net::Security::EncryptionPolicy](../../system.net.security/encryptionpolicy/) [get_EncryptionPolicy](./get_encryptionpolicy/)() | يعيد سياسة التشفير المستخدمة من قبل النسخة الحالية. |
| static **bool** [get_Expect100Continue](./get_expect100continue/)() | يحصل على قيمة تشير إلى ما إذا كانت نسخ ServicePoint-class تستخدم سلوك 100-Continue. |
| static **int32_t** [get_MaxServicePointIdleTime](./get_maxservicepointidletime/)() | يحصل على الحد الأقصى للوقت الخامل لنسخ ServicePoint-class. |
| static **int32_t** [get_MaxServicePoints](./get_maxservicepoints/)() | يحصل على الحد الأقصى لعدد نسخ ServicePoint-class التي يمكن إدارتها بواسطة النسخة الحالية. |
| static **bool** [get_ReusePort](./get_reuseport/)() | يحصل على قيمة تشير إلى ما إذا كانت مقابس الاتصالات الخارجية تستخدم الخيار 'SO_REUSE_UNICASTPORT'. |
| static [SecurityProtocolType](../securityprotocoltype/) [get_SecurityProtocol](./get_securityprotocol/)() | يحصل على نوع بروتوكول الأمان المستخدم من قبل نسخ ServicePoint-class التي تديرها النسخة الحالية. |
| static [Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/) [get_ServerCertificateValidationCallback](./get_servercertificatevalidationcallback/)() | يحصل على استدعاء الارتداد المستخدم للتحقق من شهادة الخادم. |
| static **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | يحصل على قيمة تشير إلى ما إذا كانت نسخ ServicePoint-class تستخدم خوارزمية Nagle. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير مشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يطبق قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ للصفوف الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ للصفوف الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقوم بتقليل عداد المرجع المشترك بالقيمة المحددة. |
| static void [set_CertificatePolicy](./set_certificatepolicy/)([System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\>) | يضبط سياسة شهادة. |
| static void [set_CheckCertificateRevocationList](./set_checkcertificaterevocationlist/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب فحص الشهادة مقابل قائمة إبطال صلاحية سلطة الشهادات. |
| static void [set_DefaultConnectionLimit](./set_defaultconnectionlimit/)(**int32_t**) | يضبط الحد الأقصى لعدد الاتصالات المتزامنة المسموح بها من قبل نسخ ServicePoint-class. |
| static void [set_DnsRefreshTimeout](./set_dnsrefreshtimeout/)(**int32_t**) | يضبط مهلة بالمليثانية يتم خلالها اعتبار حل DNS صالحًا. |
| static void [set_EnableDnsRoundRobin](./set_enablednsroundrobin/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان حل DNS يتناوب بين عناوين IP القابلة للتطبيق. |
| static void [set_Expect100Continue](./set_expect100continue/)(**bool**) | يضبط قيمة تشير إلى ما إذا كانت نسخ ServicePoint-class تستخدم سلوك 100-Continue. |
| static void [set_MaxServicePointIdleTime](./set_maxservicepointidletime/)(**int32_t**) | يضبط الحد الأقصى للوقت الخامل لنسخ ServicePoint-class. |
| static void [set_MaxServicePoints](./set_maxservicepoints/)(**int32_t**) | يضبط الحد الأقصى لعدد نسخ ServicePoint-class التي يمكن إدارتها بواسطة النسخة الحالية. |
| static void [set_ReusePort](./set_reuseport/)(**bool**) | يضبط قيمة تشير إلى ما إذا كانت مقابس الاتصالات الخارجية تستخدم الخيار 'SO_REUSE_UNICASTPORT'. |
| static void [set_SecurityProtocol](./set_securityprotocol/)([SecurityProtocolType](../securityprotocoltype/)) | يضبط نوع بروتوكول الأمان المستخدم من قبل نسخ ServicePoint-class التي تديرها النسخة الحالية. |
| static void [set_ServerCertificateValidationCallback](./set_servercertificatevalidationcallback/)([Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/)) | يضبط استدعاء الارتداد المستخدم للتحقق من شهادة الخادم. |
| static void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | يضبط قيمة تشير إلى ما إذا كانت نسخ ServicePoint-class تستخدم خوارزمية Nagle. |
| static void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | يضبط القيمة التي تشير إلى ما إذا كان خيار 'Keep-Alive' مفعلاً. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي رقم n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتبديل المؤشرات في الحاويات إلى وضع الضعف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقوم بتقليل وإرجاع عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق فك قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقوم بتقليل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static [DefaultNonPersistentConnectionLimit](./defaultnonpersistentconnectionlimit/) | العدد الافتراضي للاتصالات غير المستدامة. |
| static [DefaultPersistentConnectionLimit](./defaultpersistentconnectionlimit/) | العدد الافتراضي للاتصالات المستدامة. |

## انظر أيضًا

* الفئة [Object](../../system/object/)
* مساحة الاسم [System::Net](../)
* المكتبة [Aspose.Slides](../../)