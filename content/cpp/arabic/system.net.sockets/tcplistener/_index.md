---
title: TcpListener
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يمثل مستمعًا لخدمات الشبكة TCP. يجب إنشاء كائنات هذا الصنف باستخدام الدالة System::MakeObject() فقط. لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أعطال التأكيد. دائمًا قم بلف هذا الصنف في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط."
type: docs
weight: 79
url: /ar/system.net.sockets/tcplistener/
---
## TcpListener الصنف

يمثل مستمعًا لخدمات الشبكة TCP. يجب إنشاء كائنات هذه الصنف باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبدًا بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، لأنه سيؤدي إلى أخطاء وقت التشغيل أو أعطال التأكيد. احWrap دائمًا هذه الصنف في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط.

```cpp
class TcpListener : public System::Object
```

## الطرق

| Method | الوصف |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\> [AcceptSocket](./acceptsocket/)() | يقبل طلب الاتصال المعلق ويعيد الـsocket الذي يُستخدم لإرسال واستقبال البيانات. |
| [System::SharedPtr](../../system/sharedptr/)\<[TcpClient](../tcpclient/)\> [AcceptTcpClient](./accepttcpclient/)() | يقبل طلب الاتصال المعلق ويعيد كائن TcpClient-class الذي يُستخدم لإرسال واستقبال البيانات. |
| void [AllowNatTraversal](./allownattraversal/)(**bool**) | يقوم بتمكين أو تعطيل التجاوز عبر NAT. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginAcceptSocket](./beginacceptsocket/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يبادَر بعملية قبول غير متزامنة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginAcceptTcpClient](./beginaccepttcpclient/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يبادَر بعملية قبول غير متزامنة. |
| static [System::SharedPtr](../../system/sharedptr/)\<[TcpListener](./)\> [Create](./create/)(**int32_t**) | ينشئ مثيلًا جديدًا باستخدام رقم المنفذ المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\> [EndAcceptSocket](./endacceptsocket/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | ينتظر حتى تكتمل عملية القبول غير المتزامنة المحددة. |
| [System::SharedPtr](../../system/sharedptr/)\<[TcpClient](../tcpclient/)\> [EndAcceptTcpClient](./endaccepttcpclient/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | ينتظر حتى تكتمل عملية القبول غير المتزامنة المحددة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوكيات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة الأعداد العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة الأعداد العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدامات الداخلية فقط. |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | يحصل على قيمة تشير إلى ما إذا كان المثيل الحالي يسمح بعميل واحد فقط باستخدام المنفذ. |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\> [get_LocalEndpoint](./get_localendpoint/)() | يرجع نقطة النهاية الأساسية. |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\> [get_Server](./get_server/)() | يرجع الـsocket الشبكي الأساسي. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. مماثل لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل جملة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| **bool** [Pending](./pending/)() | يرجع قيمة تشير إلى وجود طلبات اتصال معلقة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن بالمرجع كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان المثيل الحالي يسمح بعميل واحد فقط باستخدام المنفذ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـn إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعن بالمؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعن بالمؤشرات الذكية أو ThisProtector. |
| void [Start](./start/)() | يبدأ الاستماع للاتصالات الواردة. |
| void [Start](./start/)(**int32_t**) | يبدأ الاستماع للاتصالات الواردة. |
| void [Stop](./stop/)() | يوقف الاستماع للاتصالات الواردة. |
|  [TcpListener](./tcplistener/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | ينشئ مثيلًا جديدًا. |
|  [TcpListener](./tcplistener/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | ينشئ مثيلًا جديدًا. |
|  [TcpListener](./tcplistener/)(**int32_t**) | ينشئ مثيلًا جديدًا. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل جملة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعن بالمؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعن بالمؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الصنف [Object](../../system/object/)
* النطاق [System::Net::Sockets](../)
* المكتبة [Aspose.Slides](../../)