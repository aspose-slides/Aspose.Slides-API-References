---
title: FileStream
second_title: مرجع API Aspose.Slides للغة C++
description: "يمثل تدفق ملفات يدعم عمليات القراءة والكتابة المتزامنة وغير المتزامنة. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم أبداً بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت تشغيل و/أو أخطاء تأكيد. احرص دائماً على تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 287
url: /ar/system.io/filestream/
---
## FileStream فئة

يمثل تدفق ملفات يدعم عمليات القراءة والكتابة المتزامنة وغير المتزامنة. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبداً بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيسبب أخطاء وقت التشغيل و/أو أخطاء تأكيد. احرص دائماً على تغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class FileStream : public System::IO::Stream
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | يبادر ببدء عملية قراءة غير متزامنة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | يبادر ببدء عملية كتابة غير متزامنة. |
| void [Close](./close/)() override | يغلق كائن [FileStream](./) الحالي. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | ينسخ البايتات إلى التدفق المحدد. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | ينسخ البايتات إلى التدفق المحدد، باستخدام حجم المخزن المؤقت المحدد. |
| void [Dispose](../stream/dispose/)() override | يطلق جميع الموارد المستخدمة من قبل الكائن الحالي ويغلق التدفق. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | ينتظر حتى تكتمل عملية القراءة غير المتزامنة المحددة. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | ينهي عملية كتابة غير متزامنة. ينتظر حتى تكتمل عملية الكتابة غير المتزامنة المحددة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمة NaN غير العددية (NaN) مساوية رغم أنه وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمة NaN غير العددية (NaN) مساوية رغم أنه وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | يُنشئ نسخة جديدة من فئة [FileStream](./) ويُهيئها بالمعلمات المحددة. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/), **int32_t**, [FileOptions](../fileoptions/)) | يُنشئ نسخة جديدة من فئة [FileStream](./) ويُهيئها بالمعلمات المحددة. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/), **int32_t**, **bool**) | يُنشئ نسخة جديدة من فئة [FileStream](./) ويُهيئها بالمعلمات المحددة. |
|  [FileStream](./filestream/)(const [FileStream](./)\&) |  |
| void [Flush](./flush/)() override | يمسح مخازن هذا التدفق ويكتب كل البيانات المخزنة إلى الملف الأساسي. |
| void [Flush](./flush/)(**bool**) | يمسح مخازن هذا التدفق ويكتب كل البيانات المخزنة إلى الملف الأساسي. مرادف للطريقة [Flush()](./flush/). |
| [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | يمسح جميع المخازن لهذا التدفق بشكل غير متزامن، ويسبب كتابة أي بيانات مخزنة إلى الجهاز الأساسي، ويراقب طلبات الإلغاء. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | يمسح جميع المخازن لهذا التدفق بشكل غير متزامن، ويسبب كتابة أي بيانات مخزنة إلى الجهاز الأساسي، ويراقب طلبات الإلغاء. |
| **bool** [get_CanRead](./get_canread/)() const override | يحدد ما إذا كان التدفق قابلًا للقراءة. |
| **bool** [get_CanSeek](./get_canseek/)() const override | يحدد ما إذا كان التدفق يدعم السعي. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | يحصل على قيمة تحدد ما إذا كان التدفق الحالي يمكن أن ينتهي مهلة. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | يحدد ما إذا كان التدفق قابلًا للكتابة. |
| **int64_t** [get_Length](./get_length/)() const override | يعيد طول التدفق بالبايت. |
| [String](../../system/string/) [get_Name](./get_name/)() const | يعيد اسم الملف الذي يضمّه كائن [FileStream](./) الحالي. |
| **int64_t** [get_Position](./get_position/)() const override | يعيد الموقع الحالي للتدفق. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | يحصل على قيمة، بالملي ثانية، تحدد مدة محاولة القراءة من قبل التدفق قبل انتهاء المهلة. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | يحصل على قيمة، بالملي ثانية، تحدد مدة محاولة الكتابة من قبل التدفق قبل انتهاء المهلة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يمكّن تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الوصف بواسطة targetType. مماثل لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يمكّن استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويمكن الفئات الفرعية من النسخ. |
| [FileStream](./)\& [operator=](./operator_equal/)(const [FileStream](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء، فقط يهيئ كائنًا جديدًا ويمكن الفئات الفرعية من النسخ. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | يقرأ عدد البايتات المحدد من التدفق ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | يقرأ عدد البايتات المحدد من التدفق ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | يقرأ عدد البايتات المحدد من التدفق ويكتبها إلى مصفوفة البايت المحددة. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | يقرأ عدد البايتات المحدد من التدفق ويكتبها إلى المدى البايت المحدد. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | يقرأ بشكل غير متزامن تسلسلًا من البايتات من التدفق الحالي، ويُحَرّك الموقع داخل التدفق بمقدار عدد البايتات المقروءة، ويراقب طلبات الإلغاء. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يقرأ بشكل غير متزامن تسلسلًا من البايتات من التدفق الحالي، ويُحَرّك الموقع داخل التدفق بمقدار عدد البايتات المقروءة، ويراقب طلبات الإلغاء. |
| **int32_t** [ReadByte](./readbyte/)() override | يقرأ بايتًا واحدًا من التدفق ويعيد قيمة عدد صحيح 32 بت مكافئة لقيمة البايت المقروء. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) للحالة التي يكون فيها السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) للحالة التي تكون فيها سلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد المراجع المشتركة بالقيمة المحددة. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | يضبط موضع التدفق الممثل بالكائن الحالي. |
| void [set_Position](./set_position/)(**int64_t**) override | يفرغ التدفق ثم يضبط موضعه. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | يضبط قيمة تحدد ما إذا كان التدفق الحالي يمكن أن ينتهي مهلة. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | يضبط قيمة بالملي ثانية تحدد مدة محاولة القراءة من التدفق قبل انتهاء المهلة. |
| void [SetLength](./setlength/)(**int64_t**) override | يضبط طول التدفق المُمثل بالكائن الحالي. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي الـ n't كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعدد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عدد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يمكّن تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايت المحددة إلى التدفق. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايت المحددة إلى التدفق. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايت المحددة إلى التدفق. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | يكتب النطاق الفرعي المحدد من البايتات من المدى البايت المحدد إلى التدفق. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | يكتب بشكل غير متزامن تسلسلًا من البايتات إلى التدفق الحالي، ويُحَرّك الموقع الحالي داخل هذا التدفق بمقدار عدد البايتات المكتوبة، ويراقب طلبات الإلغاء. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يكتب بشكل غير متزامن تسلسلًا من البايتات إلى التدفق الحالي، ويُحَرّك الموقع الحالي داخل هذا التدفق بمقدار عدد البايتات المكتوبة، ويراقب طلبات الإلغاء. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | يكتب القيمة الصحيحة غير الموقعة 8 بت المحددة إلى التدفق. |
|  [~FileStream](./~filestream/)() | المدمر. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static constexpr [DefaultBufferSize](./defaultbuffersize/) | القيمة الافتراضية لعدد البايتات المخزنة مؤقتًا أثناء عمليات القراءة والكتابة. |
| static [Null](../stream/null/) | تدفق لا يحتوي على تخزين أساسي. |

## انظر أيضا

* فئة [Stream](../stream/)
* النطاق [System::IO](../)
* المكتبة [Aspose.Slides](../../)