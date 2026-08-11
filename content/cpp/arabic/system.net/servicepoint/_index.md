---
title: ServicePoint
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يوفر إدارة اتصال HTTP. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم أبدًا بإنشاء مثيل من هذا النوع على المكدس أو باستخدام عامل new، حيث سيتسبب ذلك في أخطاء وقت التشغيل أو أخطاء تأكيد. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كوسيطة."
type: docs
weight: 417
url: /ar/system.net/servicepoint/
---
## الفئة ServicePoint

يوفر إدارة اتصال HTTP. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبدًا بإنشاء مثيل من هذا النوع على المكدس أو باستخدام عامل new، حيث سيتسبب ذلك في أخطاء وقت التشغيل أو أخطاء التأكيد. قم دائمًا بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيطة.

```cpp
class ServicePoint : public System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| **bool** [CloseConnectionGroup](./closeconnectiongroup/)([String](../../system/string/)) | يغلق ويحذف الاتصالات التي تنتمي إلى مجموعة الاتصال المحددة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNان متساويين رغم أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNان متساويين رغم أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Address](./get_address/)() | يرجع عنوان URI للخادم الذي يتصل به المثيل الحالي. |
| [BindIPEndPoint](../bindipendpoint/) [get_BindIPEndPointDelegate](./get_bindipendpointdelegate/)() | يحصل على المفوض الذي يُستخدم لربط [IPEndPoint](../ipendpoint/) المحلي بالمثيل الحالي. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_Certificate](./get_certificate/)() | يرجع شهادة تُستخدم بواسطة المثيل الحالي. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_ClientCertificate](./get_clientcertificate/)() | يرجع آخر شهادة عميل. |
| **int32_t** [get_ConnectionLeaseTimeout](./get_connectionleasetimeout/)() | يحصل على مهلة بالمللي ثانية التي بعد انتهائها سيتم إغلاق [ServicePoint](./) النشطة. |
| **int32_t** [get_ConnectionLimit](./get_connectionlimit/)() | يحصل على الحد الأقصى لعدد الاتصالات المسموح بها بواسطة المثيل الحالي. |
| [String](../../system/string/) [get_ConnectionName](./get_connectionname/)() | يرجع اسم الاتصال. |
| **int32_t** [get_CurrentConnections](./get_currentconnections/)() | يرجع عدد الاتصالات المفتوحة. |
| **bool** [get_Expect100Continue](./get_expect100continue/)() | يحصل على قيمة تشير إلى ما إذا تم استخدام سلوك 100-Continue. |
| [DateTime](../../system/datetime/) [get_IdleSince](./get_idlesince/)() | يرجع تاريخ ووقت آخر اتصال بمضيف. |
| **int32_t** [get_MaxIdleTime](./get_maxidletime/)() | يحصل على مقدار الوقت بالمللي ثانية الذي بعده سيتم إغلاق اتصال خامد. |
| virtual [Version](../../system/version/) [get_ProtocolVersion](./get_protocolversion/)() | يرجع نسخة HTTP. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | يحصل على حجم مخزن الاستقبال. |
| **bool** [get_SupportsPipelining](./get_supportspipelining/)() | يرجع قيمة تشير إلى ما إذا كان المثيل الحالي يدعم الاتصالات المتسلسلة. |
| **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | يحصل على قيمة تشير إلى ما إذا كان خوارزمية Nagle تُستخدم من قبل الاتصالات التي يديرها المثيل الحالي. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد الإشارة المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلاً للنوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ إقفال بيان C# lock(). استدعِ مباشرة أو استخدم الكائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد الإشارة المشترك بالقيمة المحددة. |
| void [set_BindIPEndPointDelegate](./set_bindipendpointdelegate/)([BindIPEndPoint](../bindipendpoint/)) | يضبط المفوض الذي يُستخدم لربط [IPEndPoint](../ipendpoint/) المحلي بالمثيل الحالي. |
| void [set_ConnectionLeaseTimeout](./set_connectionleasetimeout/)(**int32_t**) | يضبط مهلة بالمللي ثانية التي بعد انتهاءها سيتم إغلاق [ServicePoint](./) النشطة. |
| void [set_ConnectionLimit](./set_connectionlimit/)(**int32_t**) | يضبط الحد الأقصى لعدد الاتصالات المسموح بها بواسطة المثيل الحالي. |
| void [set_Expect100Continue](./set_expect100continue/)(**bool**) | يضبط قيمة تشير إلى ما إذا تم استخدام سلوك 100-Continue. |
| void [set_MaxIdleTime](./set_maxidletime/)(**int32_t**) | يضبط مقدار الوقت بالمللي ثانية الذي بعده سيتم إغلاق اتصال خامد. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | يضبط حجم مخزن الاستقبال. |
| void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان خوارزمية Nagle تُستخدم من قبل الاتصالات التي يديرها المثيل الحالي. |
| void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | يضبط القيمة التي تشير إلى ما إذا كان خيار 'Keep-Alive' مفعلاً. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي n بضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد الإشارة المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك إقفال بيان C# lock(). استدعِ مباشرة أو استخدم الكائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* الفئة [Object](../../system/object/)
* مساحة الأسماء [System::Net](../)
* المكتبة [Aspose.Slides](../../)