---
title: IPAddress
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثّل عنوان IP. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم أبداً بإنشاء مثيل من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. احرص دائماً على تغليف هذه الفئة بمؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 326
url: /ar/system.net/ipaddress/
---
## IPAddress فئة

يمثّل عنوان IP. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبداً بإنشاء مثيل من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. احرص دائماً على تغليف هذه الفئة بمؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class IPAddress : public System::Object
```

## الطرق

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان مساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان مساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لغايات داخلية فقط. |
| [System::Net::Sockets::AddressFamily](../../system.net.sockets/addressfamily/) [get_AddressFamily](./get_addressfamily/)() | يرجع عائلة العنوان. |
| **bool** [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | يرجع قيمة تشير إلى ما إذا كان العنوان عنوان IPv4 ومُطَبَّق إلى عنوان IPv6. |
| **bool** [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | يرجع قيمة تشير إلى ما إذا كان العنوان عنوان IPv6 محلي الرابط. |
| **bool** [get_IsIPv6Multicast](./get_isipv6multicast/)() | يرجع قيمة تشير إلى ما إذا كان العنوان عنوان IPv6 متعدد البث عالمي. |
| **bool** [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | يرجع قيمة تشير إلى ما إذا كان العنوان عنوان IPv6 محلي الموقع. |
| **bool** [get_IsIPv6Teredo](./get_isipv6teredo/)() | يرجع قيمة تشير إلى ما إذا كان العنوان عنوان IPv6 Teredo. |
| **int64_t** [get_ScopeId](./get_scopeid/)() | يحصل على معرف النطاق لعنوان IPv6. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetAddressBytes](./getaddressbytes/)() | يرجع مصفوفة بايت لعنوان IP. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عدّاد المرجع المرتبط بالكائن. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصّصة. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | يرجع مؤشرًا إلى التنفيذ. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| static **int64_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int64_t**) | يحول ترتيب البايت للمضيف المحدد إلى ترتيب الشبكة المقابل. |
| static **int32_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int32_t**) | يحول ترتيب البايت للمضيف المحدد إلى ترتيب الشبكة المقابل. |
| static **int16_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int16_t**) | يحول ترتيب البايت للمضيف المحدد إلى ترتيب الشبكة المقابل. |
| [IPAddress](./ipaddress/)(**int64_t**) | ينشئ مثيلًا جديدًا. |
| [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int64_t**) | ينشئ مثيلًا جديدًا. |
| [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | ينشئ مثيلًا جديدًا. |
| [IPAddress](./ipaddress/)() | ينشئ مثيلًا جديدًا. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. تماثل عامل C# 'is'. |
| static **bool** [IsLoopback](./isloopback/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>) | يرجع قيمة تشير إلى ما إذا كان العنوان المحدد عنوانًا للـ loopback. |
| void [Lock](../../system/object/lock/)() | ينفذ عملية القفل في بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv4](./maptoipv4/)() | يحوِّل العنوان إلى عنوان IPv4. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv6](./maptoipv6/)() | يحوِّل العنوان إلى عنوان IPv6. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصّصة. |
| static **int64_t** [NetworkToHostOrder](./networktohostorder/)(**int64_t**) | يحوّل ترتيب البايت للشبكة المحدد إلى ترتيب المضيف المقابل. |
| static **int32_t** [NetworkToHostOrder](./networktohostorder/)(**int32_t**) | يحوّل ترتيب البايت للشبكة المحدد إلى ترتيب المضيف المقابل. |
| static **int16_t** [NetworkToHostOrder](./networktohostorder/)(**int16_t**) | يحوّل ترتيب البايت للشبكة المحدد إلى ترتيب المضيف المقابل. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا؛ فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا؛ فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [Parse](./parse/)([String](../../system/string/)) | يحوّل السلسلة الممرّرة إلى مثيل من الفئة [IPAddress](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن بالمرجع كائن القيم مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينخفض عدّاد المرجع المشترك بالقيمة المحددة. |
| void [set_ScopeId](./set_scopeid/)(**int64_t**) | يضبط معرف النطاق لعنوان IPv6. |
| void [SetImpl](./setimpl/)([ImplPtr](./implptr/)) | يضبط مؤشرًا إلى التنفيذ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n't إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصّصة إلى سلسلة. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>\&) | يحاول تحويل السلسلة الممرّرة إلى مثيل من الفئة [IPAddress](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## الحقول

| Field | Description |
| --- | --- |
| static [Any](./any/) | عنوان IPv4 الذي يدل على ما إذا كان الخادم يجب أن يستمع إلى جميع واجهات الشبكة. |
| static [Broadcast](./broadcast/) | عنوان بث IPv4. |
| static [IPv6Any](./ipv6any/) | عنوان IPv6 الذي يدل على ما إذا كان الخادم يجب أن يستمع إلى جميع واجهات الشبكة. |
| static [IPv6Loopback](./ipv6loopback/) | عنوان IPv6 loopback. |
| static [IPv6None](./ipv6none/) | عنوان IPv6 الذي يدل على أن الخادم لا يجب أن يستمع إلى أي واجهة شبكة. |
| static [Loopback](./loopback/) | عنوان IPv4 loopback. |
| static [None](./none/) | عنوان IPv4 الذي يدل على أن الخادم لا يجب أن يستمع إلى أي واجهة شبكة. |

## التعريفات

| Typedef | Description |
| --- | --- |
| [ImplPtr](./implptr/) | مؤشر إلى نوع التنفيذ. |

## انظر أيضًا

* الفئة [Object](../../system/object/)
* النطاق [System::Net](../)
* المكتبة [Aspose.Slides](../../)