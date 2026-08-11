---
title: BasicSTDOStreamWrapper
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل طبقة تغليف مشابهة لـ System.IO.Stream لـ std::basic_ostream والكائنات المشتقة منه. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم أبداً بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء التأكيد. احرص دائمًا على تغليف هذه الفئة بمؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كوسيط."
type: docs
weight: 27
url: /ar/system.io/basicstdostreamwrapper/
---
## BasicSTDOStreamWrapper فئة

يمثل طبقة تغليف تشبه [System.IO.Stream](../stream/) لـ std::basic_ostream والكائنات المشتقة منه. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبداً بإنشاء مثيل من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء زمن التشغيل أو أخطاء التأكيد. قم دائماً بتغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط.

```cpp
template<typename T,typename>class BasicSTDOStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## الطرق

| طريقة | وصف |
| --- | --- |
|  [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(std::basic_ostream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | إنشاء مثيل جديد من [BasicSTDOStreamWrapper](./). |
|  [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(const [BasicSTDOStreamWrapper](./)\&) | منشئ النسخ. محذوف. |
|  virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | يبادر بعملية قراءة غير متزامنة. |
|  virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | يبادر بعملية كتابة غير متزامنة. |
|  virtual void [Close](../stream/close/)() | يغلق التدفق. |
|  void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | ينسخ البايتات إلى التدفق المحدد. |
|  void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | ينسخ البايتات إلى التدفق المحدد، باستخدام حجم الذاكرة المؤقتة المحدد. |
|  void [Dispose](../stream/dispose/)() override | يطلق جميع الموارد المستخدمة بواسطة الكائن الحالي ويغلق التدفق. |
|  virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | ينتظر حتى تكتمل عملية القراءة غير المتزامنة المحددة. |
|  virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | ينهي عملية كتابة غير متزامنة. ينتظر حتى تكتمل عملية الكتابة غير المتزامنة المحددة. |
|  virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
|  static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
|  static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
|  static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانين مساويين على الرغم من أنه وفقًا لـ IEC 60559:1989 لا يساوي NaN أي قيمة، بما فيها NaN. |
|  static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانين مساويين على الرغم من أنه وفقًا لـ IEC 60559:1989 لا يساوي NaN أي قيمة، بما فيها NaN. |
|  virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
|  void [Flush](./flush/)() override | يمسح مخازن التخزين المؤقت لهذا التدفق ويكتب جميع البيانات المخبأة إلى التخزين الأساسي. |
|  virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | يمسح جميع المخازن المؤقتة لهذا التدفق بشكل غير متزامن، مما يدفع بكتابة أي بيانات مخزنة إلى الجهاز الأساسي، ويراقب طلبات الإلغاء. |
|  [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | يمسح جميع المخازن المؤقتة لهذا التدفق بشكل غير متزامن، مما يدفع بكتابة أي بيانات مخزنة إلى الجهاز الأساسي، ويراقب طلبات الإلغاء. |
|  **bool** [get_CanRead](../stdiostreamwrapperbase/get_canread/)() const override | يحدد ما إذا كان التدفق يدعم القراءة. |
|  **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | يحدد ما إذا كان التدفق يدعم التقديم. |
|  virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | يحصل على قيمة تحدد ما إذا كان التدفق الحالي يمكن أن ينتهي مهله. |
|  **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | يعيد طول التدفق. |
|  **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | يعيد الموضع الحالي للتدفق. |
|  virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | يحصل على قيمة بالمليثانية تحدد المدة التي سيحاول فيها التدفق القراءة قبل انتهاء المهلة. |
|  virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | يحصل على قيمة بالمليثانية تحدد المدة التي سيحاول فيها التدفق الكتابة قبل انتهاء المهلة. |
|  Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
|  virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
|  virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
|  virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بواسطة targetType. مماثل لمشغل C# 'is'. |
|  void [Lock](../../system/object/lock/)() | ينفذ قفل تعبير C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
|  virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|   [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع هياكل البيانات الداخلية. |
|   [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، فقط يهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [BasicSTDOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDOStreamWrapper](./)\&) | عامل الإسناد النسخي. محذوف. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | عامل الإسناد النسخي. محذوف. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | إذا كان وضع التغليف ثنائيًا، يقرأ عدد البايتات المحدد من التدفق، وإلا يقرأ عدد الأحرف المحدد ويحولها إلى نوع **uint8_t**. يكتب نتيجة القراءة إلى مصفوفة البايت المحددة. غير مدعوم! |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | يقرأ عدد البايتات المحدد من التدفق ويكتبها إلى مصفوفة البايت المحددة. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | يقرأ عدد البايتات المحدد من التدفق ويكتبها إلى مصفوفة البايت المحددة. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | يقرأ عدد البايتات المحدد من التدفق ويكتبها إلى النطاق (span) البايت المحدد. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | يقرأ بشكل غير متزامن تسلسلًا من البايتات من التدفق الحالي، ويتقدم بالموقع داخل التدفق بعدد البايتات المقروءة، ويراقب طلبات الإلغاء. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يقرأ بشكل غير متزامن تسلسلًا من البايتات من التدفق الحالي، ويتقدم بالموقع داخل التدفق بعدد البايتات المقروءة، ويراقب طلبات الإلغاء. |
| int [ReadByte](./readbyte/)() override | إذا كان وضع التغليف ثنائيًا، يقرأ بايتًا واحدًا من تخزين الحرف المفكك الأخير، وإلا يقرأ حرفًا واحدًا من التدفق ويحوّله إلى نوع **uint8_t**. غير مدعوم! |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | معلومات RTTI. |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | يضبط موقع التدفق الممثل بالكائن الحالي. |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | يضبط موضع التدفق. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | يضبط قيمة تحدد ما إذا كان يمكن أن ينتهي مهلة التدفق الحالي. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | يضبط قيمة بالمليثانية تحدد مدة محاولة التدفق للقراءة قبل انتهاء المهلة. |
| void [SetLength](./setlength/)(**int64_t**) override | يضبط طول التدفق الممثل بالكائن الحالي. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط القالب المتعدد n كسند ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | منشئ النسخ. محذوف. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل تعبير C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | إذا كان وضع التغليف ثنائيًا، يكتب إلى التدفق النطاق الفرعي المحدد من البايتات من مصفوفة البايت المحددة، وإلا يحول النطاق الفرعي المحدد من البايتات إلى نوع char_type ثم يكتب النتيجة إلى التدفق. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايت المحددة إلى التدفق. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايت المحددة إلى التدفق. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | يكتب النطاق الفرعي المحدد من البايتات من النطاق (span) المحدد إلى التدفق. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | يكتب بشكل غير متزامن تسلسلًا من البايتات إلى التدفق الحالي، ويتقدم بالموقع الحالي داخل هذا التدفق بعدد البايتات المكتوبة، ويراقب طلبات الإلغاء. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يكتب بشكل غير متزامن تسلسلًا من البايتات إلى التدفق الحالي، ويتقدم بالموقع الحالي داخل هذا التدفق بعدد البايتات المكتوبة، ويراقب طلبات الإلغاء. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | إذا كان وضع التغليف ثنائيًا، يكتب إلى التدفق القيمة المحددة للعدد الصحيح غير الموقع 8-بت، وإلا يحولها إلى نوع char_type ثم يكتب النتيجة إلى التدفق. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## الحقول

| حقل | وصف |
| --- | --- |
| static [Null](../stream/null/) | تدفق لا يحتوي على تخزين أساسي. |

## التعريفات النوعية

| تعريف نوع | وصف |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |

## انظر أيضًا

* فئة [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)
* مساحة الأسماء [System::IO](../)
* مكتبة [Aspose.Slides](../../)