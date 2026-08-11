---
title: UdpClient
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "توفر خدمات شبكة بروتوكول حزم المستخدم (UDP). يجب إنشاء كائنات هذه الفئة باستخدام دالة System::MakeObject() فقط. لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام عامل new، لأن ذلك سيؤدي إلى أخطاء تشغيلية و/أو أعطال تأكيدية. احرص دائمًا على تغليف هذه الفئة داخل مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 92
url: /ar/system.net.sockets/udpclient/
---
## الفئة UdpClient


يوفر خدمات شبكة بروتوكول حزم المستخدم (UDP). يجب إنشاء كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام عامل new، لأن ذلك سيؤدي إلى أخطاء تشغيلية و/أو أعطال تأكيدية. احرص دائمًا على وضع هذه الفئة داخل مؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class UdpClient : public System::IDisposable
```

## الأساليب

| Method | Description |
| --- | --- |
| void [Close](./close/)() | يغلق اتصال UDP. |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | يؤسس اتصالًا بالمنفذ المحدد على المضيف المحدد. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | يؤسس اتصالًا بالمضيف على العنوان المحدد على المنفذ المحدد. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | يؤسس اتصالًا بنقطة النهاية البعيدة. |
| void [Dispose](./dispose/)() override | يحرر الموارد التي تديرها والتي لا تديرها [UdpClient](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNين متساويتين على الرغم من أن IEC 60559:1989 لا تعتبر NaN مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNين متساويتين على الرغم من أن IEC 60559:1989 لا تعتبر NaN مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\> [get_Client](./get_client/)() | يُستخدم لتوفير مقبس الشبكة الأساسي. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المراجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلاً للنمط الموصوف بواسطة targetType. نظير عامل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | ينفّذ بيان القفل C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنشئ نسخة. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>\&) | يُعيد حزمة البيانات المرسلة بواسطة خادم. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائنًا قيميًا بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | يرسل حزمة UDP إلى المضيف عند نقطة النهاية البعيدة. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [String](../../system/string/), **int32_t**) | يرسل حزمة UDP إلى المنفذ المحدد على المضيف البعيد المحدد. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**) | يرسل حزمة UDP إلى مضيف بعيد. |
| void [set_Client](./set_client/)([System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\>) | يُستخدم لتوفير مقبس الشبكة الأساسي. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يحدد الوسيط القالبي الـ n كإشارة ضعيفة (بدلاً من مشاركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد المرجع المشترك ويعيد القيمة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
|  [UdpClient](./udpclient/)() | يهيئ مثيلاً جديدًا من الفئة [UdpClient](./). |
|  [UdpClient](./udpclient/)([AddressFamily](../addressfamily/)) | يهيئ مثيلاً جديدًا من الفئة [UdpClient](./). |
|  [UdpClient](./udpclient/)(**int32_t**) | يهيئ مثيلاً جديدًا من الفئة [UdpClient](./). |
|  [UdpClient](./udpclient/)(**int32_t**, [AddressFamily](../addressfamily/)) | يهيئ مثيلاً جديدًا من الفئة [UdpClient](./). |
|  [UdpClient](./udpclient/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | يهيئ مثيلاً جديدًا من الفئة [UdpClient](./). المعامل local EP هو نقطة النهاية المحلية التي تربط بها اتصال UDP. |
|  [UdpClient](./udpclient/)([String](../../system/string/), **int32_t**) | ينشئ مثيلاً جديدًا من الفئة [UdpClient](./) ويتصل بالمضيف البعيد المحدد على المنفذ المحدد. |
| void [Unlock](../../system/object/unlock/)() | ينفّذ بيان إلغاء القفل C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.Slides](../../)