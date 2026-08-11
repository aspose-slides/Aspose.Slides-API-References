---
title: IStreamWrapper
second_title: مرجع API لـ Aspose.Slides للغة C++
description: مغلف Aspose.IO.Stream لواجهة COM.
type: docs
weight: 3875
url: /ar/aspose.slides/istreamwrapper/
---
## الفئة IStreamWrapper

Aspose.IO.Stream wrapper for COM interface.

```cpp
class IStreamWrapper : public System::IDisposable
```

## الطرق

| Method | Description |
| --- | --- |
| virtual void [Close](./close/)() | يغلق الدفق الحالي ويحرر أي موارد. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | لا يقوم بأي شيء. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُنظر إلى NaNين على أنهما متساويين رغم أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُنظر إلى NaNين على أنهما متساويين رغم أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للأغراض الداخلية فقط. |
| virtual void [Flush](./flush/)() | يمسح جميع المخازن المؤقتة لهذا الدفق ويؤدي إلى كتابة أي بيانات مخزنة مؤقتًا إلى الجهاز الأساسي. |
| virtual **bool** [get_CanRead](./get_canread/)() | يحصل على قيمة تشير إلى ما إذا كان الدفق الحالي يدعم القراءة. **bool** للقراءة فقط. |
| virtual **bool** [get_CanSeek](./get_canseek/)() | يحصل على قيمة تشير إلى ما إذا كان الدفق الحالي يدعم التمرير. **bool** للقراءة فقط. |
| virtual **bool** [get_CanWrite](./get_canwrite/)() | يحصل على قيمة تشير إلى ما إذا كان الدفق الحالي يدعم الكتابة. **bool** للقراءة فقط. |
| virtual **int64_t** [get_Length](./get_length/)() | يحصل على طول الدفق بالبايت. **int64_t** للقراءة فقط. |
| virtual **int64_t** [get_Position](./get_position/)() | يحصل على الموضع داخل الدفق الحالي. **int64_t** للقراءة فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [get_Stream](./get_stream/)() | يحصل على دفق. [System::IO::Stream](../../system.io/stream/) للقراءة فقط. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يمكّن تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثلاً للنوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يمكّن استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعلياً، بل يهيئ كائنًا جديدًا ويمكّن بناء نسخ الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعلياً، بل يهيئ كائنًا جديدًا ويمكّن بناء نسخ الفئات الفرعية. |
| virtual void [Read](./read/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | يقرأ تسلسلًا من البايتات من الدفق الحالي ويحرّك الموضع داخل الدفق بعدد البايتات المقروءة. |
| virtual **int32_t** [ReadByte](./readbyte/)() | يقرأ بايتًا من الدفق ويحرّك الموضع داخل الدفق بايتًا واحدًا، أو يُرجع -1 إذا كان عند نهاية الدفق. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن بالمرجع كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجع المشترك بالقيمة المحددة. |
| virtual **int64_t** [Seek](./seek/)(**int64_t**, [System::IO::SeekOrigin](../../system.io/seekorigin/)) | يحدد الموضع داخل الدفق الحالي |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n't إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويُرجع عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يمكّن تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual void [Write](./write/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | يكتب تسلسلًا من البايتات إلى الدفق الحالي ويحرّك الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة. |
| virtual void [WriteByte](./writebyte/)(**uint8_t**) | يكتب بايتًا إلى الموضع الحالي في الدفق ويحرّك الموضع داخل الدفق بايتًا واحدًا. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |
## أنظر أيضًا

* الصنف [IDisposable](../../system/idisposable/)
* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)