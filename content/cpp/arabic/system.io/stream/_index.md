---
title: Stream
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "فئة أساسية لمجموعة متنوعة من تطبيقات التدفق. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيؤدي إلى أخطاء وقت تشغيل و/أو أخطاء تأكيد. دائماً قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 365
url: /ar/system.io/stream/
---
## فئة التدفق

فئة أساسية لمجموعة متنوعة من تطبيقات التدفق. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقوم أبداً بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، لأن ذلك سيسبب أخطاء وقت تشغيل و/أو أخطاء تأكيد. دائماً قم بلف هذه الفئة ضمن مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيطة.

```cpp
class Stream : public System::IDisposable
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | يبدأ عملية قراءة غير متزامنة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | يبدأ عملية كتابة غير متزامنة. |
| virtual void [Close](./close/)() | يغلق التدفق. |
| void [CopyTo](./copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](./)\>\&) | ينسخ البايتات إلى التدفق المحدد. |
| void [CopyTo](./copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](./)\>\&, **int32_t**) | ينسخ البايتات إلى التدفق المحدد، باستخدام حجم الذاكرة المؤقتة المحدد. |
| void [Dispose](./dispose/)() override | يطلق جميع الموارد المستخدمة من قبل الكائن الحالي ويغلق التدفق. |
| virtual int [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | ينتظر حتى تكتمل عملية القراءة غير المتزامنة المحددة. |
| virtual void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | ينهي عملية كتابة غير متزامنة. ينتظر حتى تكتمل عملية الكتابة غير المتزامنة المحددة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة عائمة بأسلوب C# حيث تُعتبر قيمتي NaN متساويتين بالرغم من أن وفقاً للمعيار IEC 60559:1989 فإن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة عائمة بأسلوب C# حيث تُعتبر قيمتي NaN متساويتين بالرغم من أن وفقاً للمعيار IEC 60559:1989 فإن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| virtual void [Flush](./flush/)() | يمسح مخازن المؤقت لهذا التدفق ويكتب جميع البيانات المخزنة إلى التخزين الأساسي. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | يمسح جميع المخازن المؤقتة لهذا التدفق بشكل غير متزامن، ويؤدي إلى كتابة أي بيانات مخزنة إلى الجهاز الأساسي، ويراقب طلبات الإلغاء. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)() | يمسح جميع المخازن المؤقتة لهذا التدفق بشكل غير متزامن، ويؤدي إلى كتابة أي بيانات مخزنة إلى الجهاز الأساسي، ويراقب طلبات الإلغاء. |
| virtual **bool** [get_CanRead](./get_canread/)() const | يحدد ما إذا كان التدفق قابلًا للقراءة. |
| virtual **bool** [get_CanSeek](./get_canseek/)() const | يحدد ما إذا كان التدفق يدعم التحريك. |
| virtual **bool** [get_CanTimeout](./get_cantimeout/)() const | يحصل على قيمة تحدد ما إذا كان يمكن للتدفق الحالي انتهاء المهلة. |
| virtual **bool** [get_CanWrite](./get_canwrite/)() const | يحدد ما إذا كان التدفق قابلًا للكتابة. |
| virtual **int64_t** [get_Length](./get_length/)() const | يعيد طول التدفق بالبايت. |
| virtual **int64_t** [get_Position](./get_position/)() const | يعيد الموضع الحالي للتدفق. |
| virtual int [get_ReadTimeout](./get_readtimeout/)() const | يحصل على قيمة بالمليثانية تحدد مدة محاولات القراءة قبل انتهاء المهلة. |
| virtual int [get_WriteTimeout](./get_writetimeout/)() const | يحصل على قيمة بالمليثانية تحدد مدة محاولات الكتابة قبل انتهاء المهلة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | تنفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع البنى الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ أي شيء فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| virtual **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يقرأ العدد المحدد من البايتات من التدفق ويكتبها إلى مصفوفة البايت المحددة. |
| virtual **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يقرأ العدد المحدد من البايتات من التدفق ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [Read](./read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | يقرأ العدد المحدد من البايتات من التدفق ويكتبها إلى مصفوفة البايت المحددة. |
| virtual **int32_t** [Read](./read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | يقرأ العدد المحدد من البايتات من التدفق ويكتبها إلى المدى البايتي المحدد. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | يقرأ بشكل غير متزامن تسلسلًا من البايتات من التدفق الحالي، ويزيد الموضع داخل التدفق بعدد البايتات المقروءة، ويراقب طلبات الإلغاء. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يقرأ بشكل غير متزامن تسلسلًا من البايتات من التدفق الحالي، ويزيد الموضع داخل التدفق بعدد البايتات المقروءة، ويراقب طلبات الإلغاء. |
| virtual int [ReadByte](./readbyte/)() | يقرأ بايتًا واحدًا من التدفق ويعيد قيمة عدد صحيح 32 بت مساوية لقيمة البايت المقروء. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن قيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد المراجع المشتركة بالقيمة المحددة. |
| virtual **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) | يضع موضع التدفق الممثل بالكائن الحالي. |
| virtual void [set_Position](./set_position/)(**int64_t**) | يضبط موضع التدفق. |
| virtual void [set_ReadTimeout](./set_readtimeout/)(int) | يضبط قيمة تحدد ما إذا كان يمكن للتدفق الحالي انتهاء المهلة. |
| virtual void [set_WriteTimeout](./set_writetimeout/)(int) | يضبط قيمة بالمليثانية تحدد مدة محاولات القراءة قبل انتهاء المهلة. |
| virtual void [SetLength](./setlength/)(**int64_t**) | يضبط طول التدفق الممثل بالكائن الحالي. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضعية ضعيفة. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عدد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | تنفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | تنفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايت المحددة إلى التدفق. |
| virtual void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايت المحددة إلى التدفق. |
| void [Write](./write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايت المحددة إلى التدفق. |
| virtual void [Write](./write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | يكتب النطاق الفرعي المحدد من البايتات من المدى البايتي المحدد إلى التدفق. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | يكتب بشكل غير متزامن تسلسلًا من البايتات إلى التدفق الحالي، ويزيد الموضع الحالي داخل هذا التدفق بعدد البايتات المكتوبة، ويراقب طلبات الإلغاء. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يكتب بشكل غير متزامن تسلسلًا من البايتات إلى التدفق الحالي، ويزيد الموضع الحالي داخل هذا التدفق بعدد البايتات المكتوبة، ويراقب طلبات الإلغاء. |
| virtual void [WriteByte](./writebyte/)(**uint8_t**) | يكتب القيمة غير الموقعة 8-بت إلى التدفق. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع البنى الداخلية. |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static [Null](./null/) | تدفق لا يحتوي على تخزين أساسي. |

## تعريفات الأنواع

| النوع المعرّف | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار لمؤشر مشترك إلى هذه الفئة. |

## انظر أيضًا

* الفئة [IDisposable](../../system/idisposable/)
* النطاق [System::IO](../)
* المكتبة [Aspose.Slides](../../)