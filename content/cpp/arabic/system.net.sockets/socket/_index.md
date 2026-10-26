---
title: Socket
second_title: مرجع API لـ Aspose.Slides للغة C++
description: فئة Socket تنفّذ واجهة مآخذ بركلي.
type: docs
weight: 53
url: /ar/system.net.sockets/socket/
---
## فئة Socket

The [Socket](./) class implements the Berkeley sockets interface.

```cpp
class Socket : public System::IDisposable
```

## الأساليب

| Method | الوصف |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](./)\> [Accept](./accept/)() | ينشئ مقبسًا جديدًا للاتصال الذي تم إنشاؤه حديثًا. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يبدأ عملية اتصال غير متزامنة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يبدأ عملية اتصال غير متزامنة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يبدأ عملية اتصال غير متزامنة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يبدأ عملية اتصال غير متزامنة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginReceive](./beginreceive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يبدأ عملية كتابة غير متزامنة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginSend](./beginsend/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يبدأ عملية إرسال غير متزامنة. |
| void [Bind](./bind/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | يربط المقبس بنقطة النهاية المحلية المحددة. |
| void [Close](./close/)() | يغلق اتصال المقبس. |
| void [Close](./close/)(int) | يغلق اتصال المقبس مع المهلة المحددة للسماح بإرسال البيانات المصفوفة. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | يقيم اتصالًا بنقطة النهاية البعيدة المحددة. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | يقيم اتصالًا بنقطة النهاية البعيدة المحددة. |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | يقيم اتصالًا بنقطة النهاية البعيدة المحددة. |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | يقيم اتصالًا بنقطة النهاية البعيدة المحددة. |
| void [Dispose](./dispose/)() override | لا يفعل شيئًا. |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | ينتظر حتى تكتمل عملية الاتصال غير المتزامنة المحددة. |
| **int32_t** [EndReceive](./endreceive/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | ينتظر حتى تكتمل عملية الاستلام غير المتزامنة المحددة. |
| **int32_t** [EndReceive](./endreceive/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>, [SocketError](../socketerror/)\&) | ينتظر حتى تكتمل عملية الاستلام غير المتزامنة المحددة. |
| **int32_t** [EndSend](./endsend/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | ينتظر حتى تكتمل عملية الإرسال غير المتزامنة المحددة. |
| **int32_t** [EndSend](./endsend/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>, [SocketError](../socketerror/)\&) | ينتظر حتى تكتمل عملية الإرسال غير المتزامنة المحددة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة الأعداد العائمة بنمط C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة الأعداد العائمة بنمط C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::Net::Sockets::AddressFamily](../addressfamily/) [get_AddressFamily](./get_addressfamily/)() | يرجع عائلة العناوين. |
| **int32_t** [get_Available](./get_available/)() | يحصل على عدد البايتات المستلمة من الشبكة والمتاحة للقراءة. |
| **bool** [get_Blocking](./get_blocking/)() | يحصل على قيمة تشير إلى ما إذا كان المقبس في وضع الحجب. |
| **bool** [get_Connected](./get_connected/)() | يرجع قيمة تشير إلى ما إذا كان المقبس متصلًا بالمضيف البعيد. |
| **bool** [get_DontFragment](./get_dontfragment/)() | يحصل على قيمة تشير إلى ما إذا كان المقبس يسمح بتجزئة حزم IP. |
| **bool** [get_DualMode](./get_dualmode/)() | يحصل على قيمة تشير إلى ما إذا كان المقبس في الوضع المزدوج. |
| **bool** [get_EnableBroadcast](./get_enablebroadcast/)() | يحصل على قيمة تشير إلى ما إذا كان المقبس يسمح بحزم البث. |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | يحصل على قيمة تشير إلى ما إذا كان عملية واحدة فقط يمكنها ربط المقبس بمنفذ. |
| **bool** [get_IsBound](./get_isbound/)() | يرجع قيمة تشير إلى ما إذا كان المقبس مرتبطًا بمنفذ محلي محدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | يحصل على قيمة تشير إلى ما إذا كان المقبس سيؤخر الإغلاق في محاولة لإرسال جميع البيانات المعلقة. |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\> [get_LocalEndPoint](./get_localendpoint/)() | يرجع نقطة النهاية المحلية. |
| **bool** [get_MulticastLoopback](./get_multicastloopback/)() | يحصل على قيمة تشير إلى ما إذا كان المقبس يتلقى حزم البث المتعددة الصادرة. |
| **bool** [get_NoDelay](./get_nodelay/)() | يحصل على قيمة تشير إلى ما إذا كان المقبس يستخدم خوارزمية Nagle. |
| static **bool** [get_OSSupportsIPv4](./get_ossupportsipv4/)() | يرجع قيمة تشير إلى ما إذا كان نظام التشغيل ومحوّلات الشبكة يدعمان IPv4. |
| static **bool** [get_OSSupportsIPv6](./get_ossupportsipv6/)() | يرجع قيمة تشير إلى ما إذا كان نظام التشغيل ومحوّلات الشبكة يدعمان IPv6. |
| [System::Net::Sockets::ProtocolType](../protocoltype/) [get_ProtocolType](./get_protocoltype/)() | يرجع نوع البروتوكول. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | يحصل على حجم مخزن الاستلام. |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | يحصل على فترة بعد انتهائها ستنتهي مهلة استدعاء 'Receive'. |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\> [get_RemoteEndPoint](./get_remoteendpoint/)() | يرجع نقطة النهاية البعيدة. |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | يحصل على حجم مخزن الإرسال. |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | يحصل على فترة بعد انتهائها ستنتهي مهلة استدعاء 'Send'. |
| [System::Net::Sockets::SocketType](../sockettype/) [get_SocketType](./get_sockettype/)() | يرجع نوع المقبس. |
| static **bool** [get_SupportsIPv4](./get_supportsipv4/)() | يرجع قيمة تشير إلى ما إذا كان المضيف الحالي يدعم IPv4. |
| **int16_t** [get_Ttl](./get_ttl/)() | يحصل على قيمة TTL. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | يرجع مؤشرًا إلى التنفيذ. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/)) | يرجع القيمة التي تتطابق مع اسم الخيار المحدد. |
| void [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يحصل على القيمة التي تتطابق مع اسم الخيار المحدد. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **int32_t**) | يرجع القيمة التي تتطابق مع اسم الخيار المحدد. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| **int32_t** [IOControl](./iocontrol/)(**int32_t**, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يضبط أوضاع التشغيل منخفضة المستوى للمقبس. |
| **int32_t** [IOControl](./iocontrol/)([IOControlCode](../iocontrolcode/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يضبط أوضاع التشغيل منخفضة المستوى للمقبس. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل مثيلًا للنوع الموضح بـ targetType. تناظر عامل C# 'is'. |
| void [Listen](./listen/)(**int32_t**) | يغيّر حالة المقبس إلى 'listen'. |
| void [Lock](../../system/object/lock/)() | ينفّذ عملية القفل الخاصة بتعبير C# lock(). يتم الاستدعاء مباشرةً أو باستخدام كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويفعل إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويفعل إنشاء نسخ فرعية. |
| **bool** [Poll](./poll/)(**int32_t**, [SelectMode](../selectmode/)) | يرجع حالة المقبس بناءً على وضع الاستطلاع المحدد. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/)) | يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/)) | يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/)) | يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/)) | يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>) | يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&) | يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | يتلقى البيانات من المقبس ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>) | يتلقى البيانات من المقبس ويكتبها إلى مصفوفات البايت المحددة. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/)) | يتلقى البيانات من المقبس ويكتبها إلى مصفوفات البايت المحددة. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | يتلقى البيانات من المقبس ويكتبها إلى مصفوفات البايت المحددة. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | يتلقى البيانات من نقطة النهاية المحددة ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | يتلقى البيانات من نقطة النهاية المحددة ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | يتلقى البيانات من نقطة النهاية المحددة ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | يتلقى البيانات من نقطة النهاية المحددة ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | يتلقى البيانات من نقطة النهاية المحددة ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | يتلقى البيانات من نقطة النهاية المحددة ويكتبها في مصفوفة البايت المحددة. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | يتلقى البيانات من نقطة النهاية المحددة ويكتبها في مصفوفة البايت المحددة. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | يتلقى البيانات من نقطة النهاية المحددة ويكتبها في مصفوفة البايت المحددة. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | يتلقى البيانات من نقطة النهاية المحددة ويكتبها في مصفوفة البايت المحددة. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | يتلقى البيانات من نقطة النهاية المحددة ويكتبها في مصفوفة البايت المحددة. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | يتلقى البيانات من نقطة النهاية المحددة ويكتبها في مصفوفة البايت المحددة. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | يتلقى البيانات من نقطة النهاية المحددة ويكتبها في مصفوفة البايت المحددة. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | يتلقى البيانات من نقطة النهاية المحددة ويكتبها في مصفوفة البايت المحددة. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | يتلقى البيانات من نقطة النهاية المحددة ويكتبها في مصفوفة البايت المحددة. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | يتلقى البيانات من نقطة النهاية المحددة ويكتبها في مصفوفة البايت المحددة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد الإشارة المشترك بالقيمة المحددة. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | يرسل البيانات المحددة إلى المقبس. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | يرسل البيانات المحددة إلى المقبس. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/)) | يرسل البيانات المحددة إلى المقبس. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/)) | يرسل البيانات المحددة إلى المقبس. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/)) | يرسل البيانات المحددة إلى المقبس. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/)) | يرسل البيانات المحددة إلى المقبس. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يرسل البيانات المحددة إلى المقبس. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>) | يرسل البيانات المحددة إلى المقبس. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&) | يرسل البيانات المحددة إلى المقبس. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>) | يرسل البيانات المحددة إلى المقبس. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/)) | يرسل البيانات المحددة إلى المقبس. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | يرسل البيانات المحددة إلى المقبس. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | يرسل البيانات المحددة إلى المقبس. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | يرسل البيانات المحددة إلى المقبس. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | يرسل البيانات المحددة إلى المقبس. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | يرسل البيانات المحددة إلى المقبس. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | يرسل البيانات المحددة إلى المقبس. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | يرسل البيانات المحددة إلى المقبس. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | يرسل البيانات المحددة إلى نقطة النهاية المحددة. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | يرسل البيانات المحددة إلى نقطة النهاية المحددة. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | يرسل البيانات المحددة إلى نقطة النهاية المحددة. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | يرسل البيانات المحددة إلى نقطة النهاية المحددة. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | يرسل البيانات المحددة إلى نقطة النهاية المحددة. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | يرسل البيانات المحددة إلى نقطة النهاية المحددة. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | يرسل البيانات المحددة إلى نقطة النهاية المحددة. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | يرسل البيانات المحددة إلى نقطة النهاية المحددة. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | يرسل البيانات المحددة إلى نقطة النهاية المحددة. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | يرسل البيانات المحددة إلى نقطة النهاية المحددة. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | يرسل البيانات المحددة إلى نقطة النهاية المحددة. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | يرسل البيانات المحددة إلى نقطة النهاية المحددة. |
| void [set_Blocking](./set_blocking/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان المقبس في وضع الحجب. |
| void [set_ConnectionTimeout](./set_connectiontimeout/)(**int32_t**) | يضبط مهلة الاتصال. |
| void [set_DontFragment](./set_dontfragment/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان المقبس يسمح بتجزئة حزم IP. |
| void [set_DualMode](./set_dualmode/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان المقبس في الوضع المزدوج. |
| void [set_EnableBroadcast](./set_enablebroadcast/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان المقبس يسمح بحزم البث. |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يمكن لعملية واحدة فقط ربط المقبس بمنفذ. |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | يضبط قيمة تشير إلى ما إذا كان المقبس سيؤخر الإغلاق في محاولة لإرسال جميع البيانات المعلقة. |
| void [set_MulticastLoopback](./set_multicastloopback/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان المقبس يتلقى حزم متعددة البث الصادرة. |
| void [set_NoDelay](./set_nodelay/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان المقبس يستخدم خوارزمية ناغل. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | يضبط حجم المخزن المؤقت للاستقبال. |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | يضبط فترة بعد انتهاءها ستنتهي مهلة استدعاء 'Receive'. |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | يضبط حجم المخزن المؤقت للإرسال. |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | يضبط فترة بعد انتهاءها ستنتهي مهلة استدعاء 'Send'. |
| void [set_Ttl](./set_ttl/)(**int16_t**) | يضبط قيمة TTL. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **int32_t**) | يضبط خيار المقبس المحدد إلى القيمة المحددة. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يضبط خيار المقبس المحدد إلى القيمة المحددة. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **bool**) | يضبط خيار المقبس المحدد إلى القيمة المحددة. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يضبط خيار المقبس المحدد إلى القيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط وسيط القالب رقم n إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشترك. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد الإشارة المشترك. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [Shutdown](./shutdown/)([SocketShutdown](../socketshutdown/)) | يعطل عمليات الإرسال والاستقبال للمقبس. |
|  [Socket](./socket/)([System::Net::Sockets::SocketType](../sockettype/), [System::Net::Sockets::ProtocolType](../protocoltype/)) | يبني نسخة جديدة. |
|  [Socket](./socket/)([System::Net::Sockets::AddressFamily](../addressfamily/), [System::Net::Sockets::SocketType](../sockettype/), [System::Net::Sockets::ProtocolType](../protocoltype/)) | يبني نسخة جديدة. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | تنفيذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك القفل لبيان C# lock(). يُستدعى مباشرة أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |
| virtual  [~Socket](./~socket/)() | يدمر النسخة الحالية. |

## تعريفات الأنواع

| التعريف | الوصف |
| --- | --- |
| [ImplPtr](./implptr/) | تنفيذ المقبس. |

## انظر أيضًا

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.Slides](../../)