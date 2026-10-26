---
title: TcpClient
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثِّل عميلًا لخدمات شبكة TCP. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام operator new، إذ سيؤدي ذلك إلى أخطاء وقت التشغيل و/أو أعطال التأكيد. دائمًا قم بتغليف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 66
url: /ar/system.net.sockets/tcpclient/
---
## TcpClient فئة

يمثِّل عميلًا لخدمات شبكة TCP. يجب تخصيص كائنات هذه الفئة باستخدام دالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبدًا بإنشاء نسخة من هذا النوع على مكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل و/أو أعطال التأكيد. دائمًا قم بتغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class TcpClient : public System::IDisposable
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يَبْدَأ عملية اتصال غير متزامنة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يَبْدَأ عملية اتصال غير متزامنة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يَبْدَأ عملية اتصال غير متزامنة. |
| void [Close](./close/)() | يغلق الاتصال ويحرّر الكائن الحالي. |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | يُقِيم اتصالًا مع المضيف البعيد المحدد. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | يُقِيم اتصالًا مع المضيف البعيد المحدد. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | يُقِيم اتصالًا مع المضيف البعيد المحدد. |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | يُقِيم اتصالًا مع المضيف البعيد المحدد. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | لا يفعل شيئًا. |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | ينتظر حتى تكتمل عملية الاتصال غير المتزامنة المحددة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد [Object.Equals](../../system/object/equals/) في C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة الأعداد العائمة على نمط C# حيث تُعتبر قيمتا NaN متساويتين رغم أن وفقًا لمعيار IEC 60559:1989 لا يُعد NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة الأعداد العائمة من نوع double على نمط C# حيث تُعتبر قيمتا NaN متساويتين رغم أن وفقًا لمعيار IEC 60559:1989 لا يُعد NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **int32_t** [get_Available](./get_available/)() | يُعيد عدد البايتات المستلمة والجاهزة للقراءة. |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\> [get_Client](./get_client/)() | يحصل على المقبس. |
| **bool** [get_Connected](./get_connected/)() | يُعيد قيمة تُشير إلى ما إذا كان المقبس متصلًا بالمضيف البعيد. |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | يحصل على قيمة تُشير إلى ما إذا كانت العينة الحالية تسمح لعميل واحد فقط باستخدام المنفذ. |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | يحصل على قيمة تُشير إلى ما إذا كان المقبس سيؤخر الإغلاق في محاولة لإرسال جميع البيانات المعلقة. |
| **bool** [get_NoDelay](./get_nodelay/)() | يحصل على قيمة تُشير إلى ما إذا كانت العينة الحالية تستخدم خوارزمية Nagle. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | يحصل على حجم المخبأ المستخدم لاستلام البيانات. |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | يحصل على قيمة تُشير إلى زمن انتهاء استلام البيانات. |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | يحصل على حجم المخبأ المستخدم لإرسال البيانات. |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | يحصل على قيمة تُشير إلى زمن انتهاء إرسال البيانات. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المراجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة [Object.GetHashCode()](../../system/object/gethashcode/) في C#. يتيح حساب تجزئة للكائنات المخصصة. |
| [System::SharedPtr](../../system/sharedptr/)\<[NetworkStream](../networkstream/)\> [GetStream](./getstream/)() | يُعيد الدفق المستخدم لإرسال واستلام البيانات. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء [System.Object.GetType()](../../system/object/gettype/) في C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير معامل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | ينفذ عملية القفل في عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة [Object.MemberwiseClone()](../../system/object/memberwiseclone/) في C#. يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | إنشاء كائن. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | بناء نسخ. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | مشغل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Client](./set_client/)([System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\>) | يضبط المقبس. |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | يضبط قيمة تُشير إلى ما إذا كانت العينة الحالية تسمح لعميل واحد فقط باستخدام المنفذ. |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | يضبط قيمة تُشير إلى ما إذا كان المقبس سيؤخر الإغلاق في محاولة لإرسال جميع البيانات المعلقة. |
| void [set_NoDelay](./set_nodelay/)(**bool**) | يضبط قيمة تُشير إلى ما إذا كانت العينة الحالية تستخدم خوارزمية Nagle. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | يضبط حجم المخبأ المستخدم لاستلام البيانات. |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | يضبط قيمة تُشير إلى زمن انتهاء استلام البيانات. |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | يضبط حجم المخبأ المستخدم لإرسال البيانات. |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | يضبط قيمة تُشير إلى زمن انتهاء إرسال البيانات. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الحجة النّ المتقنـة إلى مؤشر ضعيف (بدلاً من مشترك). يتيح تبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم مؤشرات ذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويُعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم مؤشرات ذكية أو ThisProtector. |
|  [TcpClient](./tcpclient/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | ينشئ نسخة جديدة. |
|  [TcpClient](./tcpclient/)() | ينشئ نسخة جديدة. |
|  [TcpClient](./tcpclient/)([AddressFamily](../addressfamily/)) | ينشئ نسخة جديدة. |
|  [TcpClient](./tcpclient/)([String](../../system/string/), **int32_t**) | ينشئ نسخة جديدة. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة [Object.ToString()](../../system/object/tostring/) في C#. يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء typeof([System.Object](../../system/object/)) في C#. |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك القفل في عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم مؤشرات ذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم مؤشرات ذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |
| virtual  [~TcpClient](./~tcpclient/)() | يدمر العينة الحالية. |

## انظر أيضًا

* الفئة [IDisposable](../../system/idisposable/)
* النطاق [System::Net::Sockets](../)
* المكتبة [Aspose.Slides](../../)