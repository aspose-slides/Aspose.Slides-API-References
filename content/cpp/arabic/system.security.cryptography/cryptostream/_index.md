---
title: CryptoStream
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "تنفيذ تدفق يلتف حول تدفق موجود بوظيفة تشفير. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل و/أو أعطال التحقق. احرص دائمًا على تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كوسيط."
type: docs
weight: 53
url: /ar/system.security.cryptography/cryptostream/
---
## فئة CryptoStream

تنفيذ تدفق يلتف حول تدفق موجود بوظيفة تشفير. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل و/أو أعطال التحقق. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كوسيط.

```cpp
class CryptoStream : public System::IO::Stream
```

## الطرق

| طريقة | وصف |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | يباشر عملية قراءة غير متزامنة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | يباشر عملية كتابة غير متزامنة. |
| void [Close](./close/)() override | يغلق الاتصال. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | ينسخ البايتات إلى التدفق المحدد. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | ينسخ البايتات إلى التدفق المحدد، باستخدام حجم الذاكرة المؤقتة المحدد. |
|  [CryptoStream](./cryptostream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\>\&, [CryptoStreamMode](../cryptostreammode/)) | منشئ. |
| void [Dispose](../../system.io/stream/dispose/)() override | يطلق جميع الموارد المستخدمة بواسطة الكائن الحالي ويغلق التدفق. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | ينتظر حتى تكتمل عملية القراءة غير المتزامنة المحددة. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | ينهي عملية كتابة غير متزامنة. ينتظر حتى تكتمل عملية الكتابة غير المتزامنة المحددة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين حتى وإن وفقًا لـ IEC 60559:1989 فإن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين حتى وإن وفقًا لـ IEC 60559:1989 فإن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| void [Flush](./flush/)() override | يفرغ الذاكرة المؤقتة إلى التدفق المغلف. لا يفعل شيئًا لأن خوارزمية التحويل قد لا تزال تنتظر المزيد من البيانات. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | يمسح جميع الذاكرات المؤقتة لهذا التدفق بشكل غير متزامن، يسبب كتابة أي بيانات مخزنة مؤقتًا إلى الجهاز الأساسي، ويراقب طلبات الإلغاء. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | يمسح جميع الذاكرات المؤقتة لهذا التدفق بشكل غير متزامن، يسبب كتابة أي بيانات مخزنة مؤقتًا إلى الجهاز الأساسي، ويراقب طلبات الإلغاء. |
| void [FlushFinalBlock](./flushfinalblock/)() | يكتب البيانات المتبقية في الذاكرة المؤقتة إلى التدفق. |
| **bool** [get_CanRead](./get_canread/)() const override | يتحقق مما إذا كان التدفق قابلاً للقراءة. |
| **bool** [get_CanSeek](./get_canseek/)() const override | يتحقق مما إذا كان التدفق قابلًا للتموضع. |
| virtual **bool** [get_CanTimeout](../../system.io/stream/get_cantimeout/)() const | يحصل على قيمة تحدد ما إذا كان يمكن أن ينتهي مهلة التدفق الحالي. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | يتحقق مما إذا كان التدفق قابلًا للكتابة. |
| **int64_t** [get_Length](./get_length/)() const override | يحصل على طول التدفق. غير مدعوم. |
| **int64_t** [get_Position](./get_position/)() const override | يحصل على الموضع الحالي في التدفق. غير مدعوم. |
| virtual int [get_ReadTimeout](../../system.io/stream/get_readtimeout/)() const | يحصل على قيمة، بالميليثانية، تحدد مدة محاولة التدفق للقراءة قبل انتهاء المهلة. |
| virtual int [get_WriteTimeout](../../system.io/stream/get_writetimeout/)() const | يحصل على قيمة، بالميليثانية، تحدد مدة محاولة التدفق للكتابة قبل انتهاء المهلة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير عامِل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخة. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ من الفئات الفرعية. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | يقرأ البيانات من التدفق. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | يقرأ البيانات من التدفق. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | يقرأ عددًا محددًا من البايتات من التدفق ويكتبها إلى مصفوفة البايت المحددة. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | يقرأ عددًا محددًا من البايتات من التدفق ويكتبها إلى المدى البايت المحدد. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | يباشر قراءة غير متزامنة لتسلسل من البايتات من التدفق الحالي، يقدِّم الموضع داخل التدفق بعدد البايتات المقروءة، ويراقب طلبات الإلغاء. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يباشر قراءة غير متزامنة لتسلسل من البايتات من التدفق الحالي، يقدِّم الموضع داخل التدفق بعدد البايتات المقروءة، ويراقب طلبات الإلغاء. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | يقرأ بايتًا واحدًا من التدفق ويُعيد قيمة عدد صحيح 32-بت مكافئة لقيمة البايت المقروء. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | يحدد موضعًا في التدفق. غير مدعوم. |
| void [set_Position](./set_position/)(**int64_t**) override | يحدد موضعًا في التدفق. غير مدعوم. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | يضبط قيمة تحدد ما إذا كان يمكن أن ينتهي مهلة التدفق الحالي. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | يضبط قيمة، بالميليثانية، تحدد مدة محاولة التدفق للقراءة قبل انتهاء المهلة. |
| void [SetLength](./setlength/)(**int64_t**) override | يحدد حجم التدفق. غير مدعوم. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | يكتب البيانات إلى التدفق. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | يكتب البيانات إلى التدفق. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايت المحددة إلى التدفق. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | يكتب النطاق الفرعي المحدد من البايتات من المدى البايت المحدد إلى التدفق. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | يباشر كتابة غير متزامنة لتسلسل من البايتات إلى التدفق الحالي، يقدِّم الموضع داخل هذا التدفق بعدد البايتات المكتوبة، ويراقب طلبات الإلغاء. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يباشر كتابة غير متزامنة لتسلسل من البايتات إلى التدفق الحالي، يقدِّم الموضع داخل هذا التدفق بعدد البايتات المكتوبة، ويراقب طلبات الإلغاء. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | يكتب القيمة العددية غير الموقعة 8-بت إلى التدفق. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## الحقول

| حقل | وصف |
| --- | --- |
| static [Null](../../system.io/stream/null/) | تدفق بدون تخزين أساسي. |

## انظر أيضًا

* الفئة [Stream](../../system.io/stream/)
* النطاق [System::Security::Cryptography](../)
* المكتبة [Aspose.Slides](../../)