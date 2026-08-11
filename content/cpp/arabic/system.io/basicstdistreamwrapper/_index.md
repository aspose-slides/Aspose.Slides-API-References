---
title: BasicSTDIStreamWrapper
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل غلافًا شبيهًا بـ System.IO.Stream لـ std::basic_istream والكائنات المشتقة منه. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام عامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أعطال تأكيد. دائمًا غلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كوسيطة."
type: docs
weight: 14
url: /ar/system.io/basicstdistreamwrapper/
---
## BasicSTDIStreamWrapper فئة


يمثل تغليفًا شبيهاً بـ [System.IO.Stream](../stream/) لـ std::basic_istream والكائنات المشتقة منه. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام оператор new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أعطال تأكيد. دائمًا غلّف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط.

```cpp
template<typename T,typename>class BasicSTDIStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## الطرق

| طريقة | الوصف |
| --- | --- |
|  [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(std::basic_istream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | يبني مثالًا جديدًا من [BasicSTDIStreamWrapper](./). |
|  [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(const [BasicSTDIStreamWrapper](./)\&) | منشئ نسخة. محذوف. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | يبدأ عملية قراءة غير متزامنة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | يبدأ عملية كتابة غير متزامنة. |
| virtual void [Close](../stream/close/)() | يغلق الدفق. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | ينسخ البايتات إلى الدفق المحدد. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | ينسخ البايتات إلى الدفق المحدد، باستخدام حجم الذاكرة المؤقتة المحدد. |
| void [Dispose](../stream/dispose/)() override | يطلق جميع الموارد المستخدمة من قبل الكائن الحالي ويغلق الدفق. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | ينتظر حتى تكتمل عملية القراءة غير المتزامنة المحددة. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | ينهي عملية كتابة غير متزامنة. ينتظر حتى تكتمل عملية الكتابة غير المتزامنة المحددة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوك C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث تُعتبر القيمتان NaN متساويتين رغم أنه وفقًا لـ IEC 60559:1989 فإن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث تُعتبر القيمتان NaN متساويتين رغم أنه وفقًا لـ IEC 60559:1989 فإن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| void [Flush](./flush/)() override | يمسح مخازن هذا الدفق ويكتب جميع البيانات المخزنة إلى التخزين الأساسي. غير مدعوم! |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | يمسح جميع المخازن لهذا الدفق بشكل غير متزامن، مما يؤدي إلى كتابة أي بيانات مخزنة إلى الجهاز الأساسي، ويراقب طلبات الإلغاء. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | يمسح جميع المخازن لهذا الدفق بشكل غير متزامن، مما يؤدي إلى كتابة أي بيانات مخزنة إلى الجهاز الأساسي، ويراقب طلبات الإلغاء. |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | يحدد ما إذا كان الدفق يدعم الانتقال. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | يحصل على قيمة تحدد ما إذا كان الدفق الحالي يمكن أن ينتهي مهلة. |
| **bool** [get_CanWrite](../stdiostreamwrapperbase/get_canwrite/)() const override | يحدد ما إذا كان الدفق يدعم الكتابة. |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | يعيد طول الدفق. |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | يعيد الموضع الحالي للدفق. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | يحصل على قيمة (بالمليثانية) تحدد مدة محاولات القراءة قبل انتهاء المهلة. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | يحصل على قيمة (بالمليثانية) تحدد مدة محاولات الكتابة قبل انتهاء المهلة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المراجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يمكن تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير نداء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلاً للنوع الموصوف بواسطة targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يمكن استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع البنى الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بنية الفئات الفرعية. |
| [BasicSTDIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDIStreamWrapper](./)\&) | عامل إسناد نسخة. محذوف. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | عامل إسناد نسخة. محذوف. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل إسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بنية الفئات الفرعية. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | إذا كان وضع التغليف ثنائيًا، يقرأ عدد البايتات المحدد من الدفق، وإلا يقرأ عدد الأحرف المحدد ويحوّلها إلى نوع **uint8_t**. يكتب نتيجة القراءة إلى الم مصفوفة البايتية المحددة. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | يقرأ عدد البايتات المحدد من الدفق ويكتبها إلى المصفوفة البايتية المحددة. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | يقرأ عدد البايتات المحدد من الدفق ويكتبها إلى المصفوفة البايتية المحددة. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | يقرأ عدد البايتات المحدد من الدفق ويكتبها إلى المدى البايتى المحدد. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | يقرأ بشكل غير متزامن تسلسلًا من البايتات من الدفق الحالي، ويزيد الموضع داخل الدفق بعدد البايتات المقروءة، ويراقب طلبات الإلغاء. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يقرأ بشكل غير متزامن تسلسلًا من البايتات من الدفق الحالي، ويزيد الموضع داخل الدفق بعدد البايتات المقروءة، ويراقب طلبات الإلغاء. |
| int [ReadByte](./readbyte/)() override | إذا كان وضع التغليف ثنائيًا، يقرأ بايتًا واحدًا من مخزن آخر حرف مُفك، وإلا يقرأ حرفًا واحدًا من الدفق ويحوّله إلى نوع **uint8_t**. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | معلومات RTTI. |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | يضبط موضع الدفق الممثّل بالكائن الحالي. |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | يضبط موضع الدفق. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | يضبط قيمة تحدد ما إذا كان الدفق الحالي يمكن أن ينتهي مهلة. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | يضبط قيمة (بالمليثانية) تحدد مدة محاولات القراءة قبل انتهاء المهلة. |
| void [SetLength](./setlength/)(**int64_t**) override | يضبط طول الدفق الممثّل بالكائن الحالي. غير مدعوم! |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعدد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص عدّاد المرجع المشترك ويعيده. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | منشئ نسخة. محذوف. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يمكن تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | إذا كان وضع التغليف ثنائيًا، يكتب إلى الدفق النطاق الفرعي المحدد من البايتات من المصفوفة البايتية المحددة، وإلا يحول النطاق الفرعي المحدد من البايتات إلى نوع char_type ثم يكتب النتيجة إلى الدفق. غير مدعوم! |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | يكتب النطاق الفرعي المحدد من البايتات من المصفوفة البايتية المحددة إلى الدفق. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | يكتب النطاق الفرعي المحدد من البايتات من المصفوفة البايتية المحددة إلى الدفق. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | يكتب النطاق الفرعي المحدد من البايتات من المدى البايتى المحدد إلى الدفق. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | يكتب بشكل غير متزامن تسلسلًا من البايتات إلى الدفق الحالي، ويزيد الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة، ويراقب طلبات الإلغاء. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يكتب بشكل غير متزامن تسلسلًا من البايتات إلى الدفق الحالي، ويزيد الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة، ويراقب طلبات الإلغاء. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | إذا كان وضع التغليف ثنائيًا، يكتب إلى الدفق القيمة غير الموقعة 8-بت المحددة، وإلا يحولها إلى نوع char_type ثم يكتب النتيجة إلى الدفق. غير مدعوم! |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع البنى الداخلية. |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static [Null](../stream/null/) | دفق لا يحتوي على تخزين أساسي. |

## تعريفات الأنواع

| تعريف | الوصف |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |

## انظر أيضًا

* فئة [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)
* نطاق [System::IO](../)
* مكتبة [Aspose.Slides](../../)