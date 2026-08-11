---
title: HttpWebClientProtocol
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "تُستخدم هذه الفئة الأساسية في جميع وكلاء عميل خدمة الويب XML الذين يستخدمون HTTP. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تُنشئ أبداً مثيلاً من هذا النوع على المكدس أو باستخدام المُشغل new، لأن ذلك سيؤدي إلى أخطاء زمن التشغيل و/أو أخطاء تأكيد. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 14
url: /ar/system.web.services.protocols/httpwebclientprotocol/
---
## فئة HttpWebClientProtocol

تُستَخدم هذه الفئة الأساسية في جميع وكلاء عميل الخدمة XML [Web](../../system.web/) الذين يستخدمون HTTP. يجب إنشاء كائنات هذه الفئة فقط باستخدام دالة [System::MakeObject()](../../system/makeobject/). لا تقم أبداً بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء زمن التشغيل و/أو أخطاء التأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class HttpWebClientProtocol : public System::Web::Services::Protocols::WebClientProtocol
```

## الأساليب

| Method | Description |
| --- | --- |
| virtual void [Abort](../webclientprotocol/abort/)() | يلغي الطلب. |
| virtual void [CheckForCookies](./checkforcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Net::HttpWebResponse](../../system.net/httpwebresponse/)\>) | يضيف ملفات تعريف الارتباط من الطلب المحدد إلى حاوية ملفات تعريف الارتباط الداخلية. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقاط العائمة بأسلوب C# حيث تُعتبر NaNّان متساويتين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقاط العائمة بأسلوب C# حيث تُعتبر NaNّان متساويتين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | يحصل على قيمة تشير إلى ما إذا كان العميل يتبع إعادة توجيه الخادم. |
| [System::SharedPtr](../../system/sharedptr/)\<[Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | يعيد مجموعة شهادات العميل. |
| [String](../../system/string/) [get_ConnectionGroupName](../webclientprotocol/get_connectiongroupname/)() | يحصل على اسم مجموعة الاتصال. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | يحصل على حاوية تُستخدم لتخزين ملفات تعريف الارتباط. |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\> [get_Credentials](../webclientprotocol/get_credentials/)() | يحصل على معلومات المصادقة. |
| **bool** [get_EnableDecompression](./get_enabledecompression/)() | يحصل على قيمة تشير إلى ما إذا كان فك الضغط مُفعَّلًا. |
| **bool** [get_PreAuthenticate](../webclientprotocol/get_preauthenticate/)() | يحصل على قيمة تشير إلى ما إذا كان المصادقة المسبقة مُفعَّلة. |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\> [get_Proxy](./get_proxy/)() | يحصل على معلومات الوكيل. |
| [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_RequestEncoding](../webclientprotocol/get_requestencoding/)() | يحصل على الترميز المستخدم في طلبات العميل. |
| **int32_t** [get_Timeout](../webclientprotocol/get_timeout/)() | يحصل على المدة التي يجب الانتظار قبل انتهاء مهلة الطلب. |
| **bool** [get_UnsafeAuthenticatedConnectionSharing](./get_unsafeauthenticatedconnectionsharing/)() | يحصل على قيمة تشير إلى ما إذا كان مشاركة الاتصال مُفعَّلة عندما يستخدم العميل مصادقة NTLM. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Uri](../webclientprotocol/get_uri/)() | يحصل على URI خدمة XML [Web](../../system.web/). |
| [String](../../system/string/) [get_Url](../webclientprotocol/get_url/)() | يحصل على عنوان URL لخدمة XML [Web](../../system.web/). |
| **bool** [get_UseDefaultCredentials](../webclientprotocol/get_usedefaultcredentials/)() | يحصل على قيمة تشير إلى ما إذا كانت الخاصية 'Credential' مساوية للخاصية 'DefaultCredentials'. |
| [String](../../system/string/) [get_UserAgent](./get_useragent/)() | يحصل على قيمة ترويسة 'User-Agent'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تمثيل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تمثيل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تمثيل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل جملة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تمثيل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان العميل يتبع إعادة توجيه الخادم. |
| void [set_ConnectionGroupName](../webclientprotocol/set_connectiongroupname/)([String](../../system/string/)) | يضبط اسم مجموعة الاتصال. |
| void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\>) | يضبط حاوية تُستخدم لتخزين ملفات تعريف الارتباط. |
| void [set_Credentials](../webclientprotocol/set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\>) | يضبط معلومات المصادقة. |
| void [set_EnableDecompression](./set_enabledecompression/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان فك الضغط مُفعَّلًا. |
| void [set_PreAuthenticate](../webclientprotocol/set_preauthenticate/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان المصادقة المسبقة مُفعَّلة. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\>) | يضبط معلومات الوكيل. |
| void [set_RequestEncoding](../webclientprotocol/set_requestencoding/)([System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>) | يضبط الترميز المستخدم في طلبات العميل. |
| void [set_Timeout](../webclientprotocol/set_timeout/)(**int32_t**) | يضبط المدة التي يجب الانتظار قبل انتهاء مهلة الطلب. |
| void [set_UnsafeAuthenticatedConnectionSharing](./set_unsafeauthenticatedconnectionsharing/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان مشاركة الاتصال مُفعَّلة عندما يستخدم العميل مصادقة NTLM. |
| void [set_Uri](../webclientprotocol/set_uri/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | يضبط URI خدمة XML [Web](../../system.web/). |
| void [set_Url](../webclientprotocol/set_url/)([String](../../system/string/)) | يضبط عنوان URL لخدمة XML [Web](../../system.web/). |
| void [set_UseDefaultCredentials](../webclientprotocol/set_usedefaultcredentials/)(**bool**) | يضبط قيمة تشير إلى ما إذا كانت الخاصية 'Credential' مساوية للخاصية 'DefaultCredentials'. |
| void [set_UserAgent](./set_useragent/)([String](../../system/string/)) | يضبط قيمة ترويسة 'User-Agent'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص عداد المرجع المشترك ويعيده. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تمثيل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل جملة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| void [UnregisterMapping](./unregistermapping/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) |  |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [WebClientProtocol](../webclientprotocol/)
* مساحة الأسماء [System::Web::Services::Protocols](../)
* المكتبة [Aspose.Slides](../../)