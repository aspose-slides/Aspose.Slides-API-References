---
title: ContentDispositionHeaderValue
second_title: مرجع API Aspose.Slides للـ C++
description: "يمثل قيمة رأس 'Content-Disposition'. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام operator new، لأنه سيؤدي إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 27
url: /ar/system.net.http.headers/contentdispositionheadervalue/
---
## ContentDispositionHeaderValue فئة


يمثل قيمة رأس 'Content-Disposition'. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام operator new، لأنه سيؤدي إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. احفظ دائمًا هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class ContentDispositionHeaderValue : public System::ICloneable
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
|  [ContentDispositionHeaderValue](./contentdispositionheadervalue/)() | ينشئ مثيلاً جديدًا. |
|  [ContentDispositionHeaderValue](./contentdispositionheadervalue/)([String](../../system/string/)) | ينشئ مثيلاً جديدًا. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة بنمط C# حيث تُعتبر NaNانّتين متساويتين بالرغم من أن IEC 60559:1989 يحدد أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة بنمط C# حيث تُعتبر NaNانّتين متساويتين بالرغم من أن IEC 60559:1989 يحدد أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_CreationDate](./get_creationdate/)() | يحصل على تاريخ إنشاء الملف. |
| [String](../../system/string/) [get_DispositionType](./get_dispositiontype/)() | يحصل على نوع التوزيع. |
| [String](../../system/string/) [get_FileName](./get_filename/)() | يحصل على قيمة تحدد كيفية إنشاء اسم ملف لتخزين حمولة الرسالة. يُستخدم عندما يكون الكيان منفصلًا ويُخزن في ملف منفصل. |
| [String](../../system/string/) [get_FileNameStar](./get_filenamestar/)() | يحصل على قيمة تحدد كيفية إنشاء أسماء ملفات لتخزين حمولة الرسالة. يُستخدم عندما تكون الكيانات منفصلة وتُخزن في ملفات منفصلة. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_ModificationDate](./get_modificationdate/)() | يحصل على تاريخ تعديل الملف. |
| [String](../../system/string/) [get_Name](./get_name/)() | يحصل على اسم لجزء من محتوى الجسم. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Parameters](./get_parameters/)() | يرجع مجموعة من المتغيرات لرأس 'Content-Disposition'. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_ReadDate](./get_readdate/)() | يحصل على التاريخ الذي قُرئ فيه الملف آخر مرة. |
| [Nullable](../../system/nullable/)\<**int64_t**\> [get_Size](./get_size/)() | يحصل على حجم تقريبي للملف. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المراجع المرتبط بالكائن. |
| static **int32_t** [GetDispositionTypeLength](./getdispositiontypelength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | يحوّل السلسلة المُمرَّرة من الفهرس المحدد إلى مثيل من الفئة [ContentDispositionHeaderValue](./). |
| **int32_t** [GetHashCode](./gethashcode/)() const override | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. نظير معامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ عملية قفل بيان C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، وإنما يهيئ كائنًا جديدًا ويسمح بإنشاء نسخة من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، وإنما يهيئ كائنًا جديدًا ويسمح بإنشاء نسخة من الفئات الفرعية. |
| static [System::SharedPtr](../../system/sharedptr/)\<[ContentDispositionHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | يحوّل السلسلة المُمرَّرة إلى مثيل من الفئة [ContentDispositionHeaderValue](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائنًا من نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المراجع المشتركة بمقدار القيمة المحددة. |
| void [set_CreationDate](./set_creationdate/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | يضبط تاريخ إنشاء الملف. |
| void [set_DispositionType](./set_dispositiontype/)([String](../../system/string/)) | يضبط نوع التوزيع. |
| void [set_FileName](./set_filename/)([String](../../system/string/)) | يضبط قيمة تحدد كيفية إنشاء اسم ملف لتخزين حمولة الرسالة. يُستخدم عندما يكون الكيان منفصلًا ويُخزن في ملف منفصل. |
| void [set_FileNameStar](./set_filenamestar/)([String](../../system/string/)) | يضبط قيمة تحدد كيفية إنشاء أسماء ملفات لتخزين حمولة الرسالة. يُستخدم عندما تكون الكيانات منفصلة وتُخزن في ملفات منفصلة. |
| void [set_ModificationDate](./set_modificationdate/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | يضبط تاريخ تعديل الملف. |
| void [set_Name](./set_name/)([String](../../system/string/)) | يضبط اسمًا لجزء من محتوى الجسم. |
| void [set_ReadDate](./set_readdate/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | يضبط التاريخ الذي قُرئ فيه الملف آخر مرة. |
| void [set_Size](./set_size/)([Nullable](../../system/nullable/)\<**int64_t**\>) | يضبط حجمًا تقريبيًا للملف. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويُعيد عداد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك استخدم المؤشرات الذكية أو ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة نصية. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ContentDispositionHeaderValue](./)\>\&) | يحاول تحويل السلسلة المُمرَّرة إلى مثيل من الفئة [ContentDispositionHeaderValue](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل بيان C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* الفئة [ICloneable](../../system/icloneable/)
* النطاق [System::Net::Http::Headers](../)
* المكتبة [Aspose.Slides](../../)