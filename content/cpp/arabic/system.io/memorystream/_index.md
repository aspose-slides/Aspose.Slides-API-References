---
title: MemoryStream
second_title: مرجع API Aspose.Slides للغة C++
description: "يمثل تدفقًا يقرأ من الذاكرة ويكتب إليها. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، حيث سيتسبب ذلك في أخطاء وقت التشغيل و/أو أعطال التأكيد. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 326
url: /ar/system.io/memorystream/
---
## فئة MemoryStream

يمثل تدفقًا يقرأ من الذاكرة ويكتب إليها. يجب إنشاء كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل و/أو أعطال التأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class MemoryStream : public System::IO::Stream
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | يبدأ عملية قراءة غير متزامنة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | يبدأ عملية كتابة غير متزامنة. |
| void [Close](./close/)() override | يغلق التدفق. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | ينسخ البايتات إلى التدفق المحدد. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | ينسخ البايتات إلى التدفق المحدد، باستخدام حجم المخزن المؤقت المحدد. |
| void [Dispose](../stream/dispose/)() override | يحرر جميع الموارد المستخدمة من قبل الكائن الحالي ويغلق التدفق. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | ينتظر حتى تكتمل عملية القراءة غير المتزامنة المحددة. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | ينهي عملية كتابة غير متزامنة. ينتظر حتى تكتمل عملية الكتابة غير المتزامنة المحددة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن وفقًا للمعيار IEC 60559:1989 فإن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن وفقًا للمعيار IEC 60559:1989 فإن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| void [Flush](./flush/)() override | لا يفعل شيئًا. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | يمسح جميع المخازن المؤقتة لهذا التدفق بشكل غير متزامن، ويتسبب في كتابة أي بيانات مخزنة مؤقتًا إلى الجهاز الأساسي، ويراقب طلبات الإلغاء. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | يمسح جميع المخازن المؤقتة لهذا التدفق بشكل غير متزامن، ويتسبب في كتابة أي بيانات مخزنة مؤقتًا إلى الجهاز الأساسي، ويراقب طلبات الإلغاء. |
| **bool** [get_CanRead](./get_canread/)() const override | يحدد ما إذا كان التدفق قابلاً للقراءة. |
| **bool** [get_CanSeek](./get_canseek/)() const override | يحدد ما إذا كان التدفق يدعم السعي. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | يحصل على قيمة تحدد ما إذا كان يمكن أن ينتهي وقت التدفق الحالي. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | يحدد ما إذا كان التدفق قابلًا للكتابة. |
| int [get_Capacity](./get_capacity/)() | يعيد السعة الحالية لمخزن الذاكرة الأساسي. |
| **int64_t** [get_Length](./get_length/)() const override | يعيد طول التدفق بالبايت. |
| **int64_t** [get_Position](./get_position/)() const override | يعيد الموضع الحالي للتدفق. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | يحصل على قيمة بالمليثانية تحدد مدة محاولة التدفق للقراءة قبل انتهاء المهلة. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | يحصل على قيمة بالمليثانية تحدد مدة محاولة التدفق للكتابة قبل انتهاء المهلة. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBuffer](./getbuffer/)() | يعيد مؤشرًا إلى المخزن الأساسي. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بواسطة targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [MemoryStream](./memorystream/)() | ينشئ مثيلًا جديدًا من الفئة [MemoryStream](./) بسعة أولية تساوي 0. |
|  [MemoryStream](./memorystream/)(int) | ينشئ مثيلًا جديدًا من الفئة [MemoryStream](./) التي تمثل تدفقًا يعتمد على مخزن الذاكرة بالحجم المحدد. |
|  [MemoryStream](./memorystream/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **bool**) | ينشئ مثيلًا جديدًا من الفئة [MemoryStream](./) التي تمثل تدفق ذاكرة متصل بالمخزن الذاكرة المحدد. المعامل يحدد ما إذا كان التدفق قابلًا للكتابة. |
|  [MemoryStream](./memorystream/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int, **bool**, **bool**) | ينشئ مثيلًا جديدًا من الفئة [MemoryStream](./) التي تمثل تدفق ذاكرة متصل بقطاع من المخزن الذاكرة المحدد يبدأ من الفهرس المحدد ويشمل العدد المحدد من العناصر. المعاملات تحدد ما إذا كان التدفق قابلًا للكتابة وما إذا كان يمكن استدعاء الطريقة GetBytes(). |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ البنى الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ البنى الفرعية. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | يقرأ العدد المحدد من البايتات من التدفق ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | يقرأ العدد المحدد من البايتات من التدفق ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | يقرأ العدد المحدد من البايتات من التدفق ويكتبها إلى مصفوفة البايت المحددة. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | يقرأ العدد المحدد من البايتات من التدفق ويكتبها إلى النطاق البايت المحدد. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | يقرأ تسلسلًا من البايتات من التدفق الحالي بشكل غير متزامن، يرفع الموضع داخل التدفق بعدد البايتات المقروءة، ويراقب طلبات الإلغاء. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يقرأ تسلسلًا من البايتات من التدفق الحالي بشكل غير متزامن، يرفع الموضع داخل التدفق بعدد البايتات المقروءة، ويراقب طلبات الإلغاء. |
| int [ReadByte](./readbyte/)() override | يقرأ بايتًا واحدًا من التدفق ويعيد قيمة عدد صحيح 32-بت مساوية لقيمة البايت المقروء. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | يضبط موضع التدفق الممثّل بالكائن الحالي. |
| void [set_Capacity](./set_capacity/)(int) | يضبط سعة مخزن الذاكرة الأساسي. |
| void [set_Position](./set_position/)(**int64_t**) override | يضبط موضع التدفق. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | يضبط قيمة تحدد ما إذا كان يمكن أن ينتهي وقت التدفق الحالي. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | يضبط قيمة بالمليثانية تحدد مدة محاولة التدفق للقراءة قبل انتهاء المهلة. |
| void [SetLength](./setlength/)(**int64_t**) override | يضبط طول التدفق الممثّل بالكائن الحالي. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضعية ضعيفة. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ToArray](./toarray/)() | يعيد نسخة من مخزن الذاكرة الأساسي كمصفوفة من البايتات. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| **bool** [TryGetBuffer](./trygetbuffer/)([ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\&) | يعيد مصفوفة البايتات غير الموقعة التي تم إنشاء هذا التدفق منها. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايت المحددة إلى التدفق. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايت المحددة إلى التدفق. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايت المحددة إلى التدفق. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | يكتب النطاق الفرعي المحدد من البايتات من النطاق البايت المحدد إلى التدفق. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | يكتب تسلسلًا من البايتات إلى التدفق الحالي بشكل غير متزامن، يرفع الموضع الحالي داخل هذا التدفق بعدد البايتات المكتوبة، ويراقب طلبات الإلغاء. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يكتب تسلسلًا من البايتات إلى التدفق الحالي بشكل غير متزامن، يرفع الموضع الحالي داخل هذا التدفق بعدد البايتات المكتوبة، ويراقب طلبات الإلغاء. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | يكتب القيمة المحددة للعدد الصحيح غير الموقّع 8-بت إلى التدفق. |
| virtual void [WriteTo](./writeto/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>) | يكتب محتوى المخزن الأساسي إلى التدفق المحدد. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static [Null](../stream/null/) | تدفق بدون تخزين أساسي. |

## التعاريف

| التعريف | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار لمؤشر مشترك إلى الذات. |

## انظر أيضًا

* الفئة [Stream](../stream/)
* النطاق [System::IO](../)
* المكتبة [Aspose.Slides](../../)