---
title: AuthenticatedStream
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: "يحتوي على الأساليب لتمرير بيانات الاعتماد عبر الدفق. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تنشئ أبدًا نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيؤدي إلى أخطاء وقت تشغيل و/أو أخطاء التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 1
url: /ar/system.net.security/authenticatedstream/
---
## فئة AuthenticatedStream

يحتوي على الأساليب لتمرير بيانات الاعتماد عبر الدفق. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبدًا بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أخطاء التأكيد. احرص دائمًا على تغليف هذه الفئة إلى مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class AuthenticatedStream : public System::IO::Stream
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | يباشر عملية قراءة غير متزامنة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | يباشر عملية كتابة غير متزامنة. |
| virtual void [Close](../../system.io/stream/close/)() | يغلق الدفق. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | ينسخ البايتات إلى الدفق المحدد. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | ينسخ البايتات إلى الدفق المحدد، باستخدام حجم المخزن المؤقت المحدد. |
| void [Dispose](../../system.io/stream/dispose/)() override | يطلق جميع الموارد المستخدمة بواسطة الكائن الحالي ويغلق الدفق. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | ينتظر حتى تكتمل عملية القراءة غير المتزامنة المحددة. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | ينهي عملية كتابة غير متزامنة. ينتظر حتى تكتمل عملية الكتابة غير المتزامنة المحددة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNين متساويين على الرغم من أن وفقًا لمعيار IEC 60559:1989 لا يُعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNين متساويين على الرغم من أن وفقًا لمعيار IEC 60559:1989 لا يُعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual void [Flush](../../system.io/stream/flush/)() | يمسح مخازن هذا الدفق ويكتب جميع البيانات المخزنة إلى التخزين الأساسي. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | يمسح بشكل غير متزامن جميع المخازن لهذا الدفق، ويسبب كتابة أي بيانات مخزنة إلى الجهاز الأساسي، ويراقب طلبات الإلغاء. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | يمسح بشكل غير متزامن جميع المخازن لهذا الدفق، ويسبب كتابة أي بيانات مخزنة إلى الجهاز الأساسي، ويراقب طلبات الإلغاء. |
| virtual **bool** [get_CanRead](../../system.io/stream/get_canread/)() const | يحدد ما إذا كان الدفق قابلًا للقراءة. |
| virtual **bool** [get_CanSeek](../../system.io/stream/get_canseek/)() const | يحدد ما إذا كان الدفق يدعم السعي. |
| virtual **bool** [get_CanTimeout](../../system.io/stream/get_cantimeout/)() const | يحصل على قيمة تحدد ما إذا كان الدفق الحالي يمكن أن ينتهي مهلةً. |
| virtual **bool** [get_CanWrite](../../system.io/stream/get_canwrite/)() const | يحدد ما إذا كان الدفق قابلًا للكتابة. |
| virtual **bool** [get_IsAuthenticated](./get_isauthenticated/)() const | يعيد قيمة تشير إلى ما إذا تم تمرير المصادقة بنجاح. |
| virtual **bool** [get_IsEncrypted](./get_isencrypted/)() const | يعيد قيمة تشير إلى ما إذا كانت البيانات المرسلة باستخدام هذا الدفق مشفرة. |
| virtual **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const | يعيد قيمة تشير إلى ما إذا كان الخادم والعميل قد تم المصادقة عليهما. |
| virtual **bool** [get_IsServer](./get_isserver/)() const | يعيد قيمة تشير إلى ما إذا كان الطرف المحلي للاتصال هو الخادم. |
| virtual **bool** [get_IsSigned](./get_issigned/)() const | يعيد قيمة تشير إلى ما إذا كانت البيانات المرسلة باستخدام هذا الدفق موقعة. |
| **bool** [get_LeaveInnerStreamOpen](./get_leaveinnerstreamopen/)() const | يعيد الدفق المستخدم من قبل كائنات الفئة الحالية لإرسال واستقبال البيانات. |
| virtual **int64_t** [get_Length](../../system.io/stream/get_length/)() const | يعيد طول الدفق بالبايت. |
| virtual **int64_t** [get_Position](../../system.io/stream/get_position/)() const | يعيد الموقع الحالي للدفق. |
| virtual int [get_ReadTimeout](../../system.io/stream/get_readtimeout/)() const | يحصل على قيمة، بالميليثانية، تحدد المدة التي سيحاول فيها الدفق القراءة قبل انتهاء المهلة. |
| virtual int [get_WriteTimeout](../../system.io/stream/get_writetimeout/)() const | يحصل على قيمة، بالميليثانية، تحدد المدة التي سيحاول فيها الدفق الكتابة قبل انتهاء المهلة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل تعليمة C# lock(). استدعِ مباشرةً أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يقرأ عدد البايتات المحدد من الدفق ويكتبها إلى مصفوفة البايتات المحددة. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يقرأ عدد البايتات المحدد من الدفق ويكتبها إلى مصفوفة البايتات المحددة. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | يقرأ عدد البايتات المحدد من الدفق ويكتبها إلى مصفوفة البايتات المحددة. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | يقرأ عدد البايتات المحدد من الدفق ويكتبها إلى المدى البايت المحدد. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | يقوم بقراءة تسلسل من البايتات من الدفق الحالي بشكل غير متزامن، ويحرّك الموقع داخل الدفق بمقدار عدد البايتات المقروئة، ويراقب طلبات الإلغاء. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يقوم بقراءة تسلسل من البايتات من الدفق الحالي بشكل غير متزامن، ويحرّك الموقع داخل الدفق بمقدار عدد البايتات المقروئة، ويراقب طلبات الإلغاء. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | يقرأ بايتًا واحدًا من الدفق ويعيد قيمة عدد صحيح 32 بت تماثل قيمة البايت المقروء. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلص عداد المرجع المشترك بالقيمة المحددة. |
| virtual **int64_t** [Seek](../../system.io/stream/seek/)(**int64_t**, [SeekOrigin](../../system.io/seekorigin/)) | يضبط موضع الدفق الممثل بالكائن الحالي. |
| virtual void [set_Position](../../system.io/stream/set_position/)(**int64_t**) | يضبط موضع الدفق. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | يضبط قيمة تحدد ما إذا كان الدفق الحالي يمكن أن ينتهي مهلةً. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | يضبط قيمة، بالميليثانية، تحدد المدة التي سيحاول فيها الدفق القراءة قبل انتهاء المهلة. |
| virtual void [SetLength](../../system.io/stream/setlength/)(**int64_t**) | يضبط طول الدفق الممثل بالكائن الحالي. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي n كإشارة ضعيفة (بدلاً من مشاركة). يسمح بتحويل المؤشرات في الحاويات إلى نمط الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل تعليمة C# lock(). استدعِ مباشرةً أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual void [Write](../../system.io/stream/write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايتات المحددة إلى الدفق. |
| virtual void [Write](../../system.io/stream/write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايتات المحددة إلى الدفق. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايتات المحددة إلى الدفق. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | يكتب النطاق الفرعي المحدد من البايتات من المدى البايت المحدد إلى الدفق. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | يكتب بشكل غير متزامن تسلسلًا من البايتات إلى الدفق الحالي، ويحرك الموقع الحالي داخل هذا الدفق بمقدار عدد البايتات المكتوبة، ويراقب طلبات الإلغاء. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يكتب بشكل غير متزامن تسلسلًا من البايتات إلى الدفق الحالي، ويحرك الموقع الحالي داخل هذا الدفق بمقدار عدد البايتات المكتوبة، ويراقب طلبات الإلغاء. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | يكتب القيمة المحددة للعدد غير الموقّع 8-بت إلى الدفق. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static [Null](../../system.io/stream/null/) | دفق بدون تخزين أساسي. |

## أنظر أيضًا

* الفئة [Stream](../../system.io/stream/)
* النطاق [System::Net::Security](../)
* المكتبة [Aspose.Slides](../../)