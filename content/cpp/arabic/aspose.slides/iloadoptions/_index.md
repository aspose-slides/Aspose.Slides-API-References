---
title: ILoadOptions
second_title: مرجع Aspose.Slides للغة C++ API
description: يسمح بتحديد خيارات إضافية (مثل التنسيق أو الخط الافتراضي) عند تحميل عرض تقديمي.
type: docs
weight: 2796
url: /ar/aspose.slides/iloadoptions/
---
## ILoadOptions فئة


Allows to specify additional options (such as format or default font) when loading a presentation.

```cpp
class ILoadOptions : public virtual System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | تحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن وفقًا لـ IEC 60559:1989 فإن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | تحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن وفقًا لـ IEC 60559:1989 فإن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() | يمثل الخيارات التي يمكن استخدامها لإدارة سلوك معالجة الكائنات الثنائية الكبيرة (BLOBs)، مثل استخدام الملفات المؤقتة أو الحد الأقصى لعدد بايتات BLOBs في الذاكرة. تهدف هذه الخيارات إلى ضبط أفضل نسبة بين الأداء واستهلاك الذاكرة لبيئة أو متطلبات معينة. |
| virtual [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() | يعيد الخط الآسيوي المستخدم في حال عدم العثور على الخط المصدر. يقرأ [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() | يعيد الخط العادي المستخدم في حال عدم العثور على الخط المصدر. يقرأ [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() | يعيد خط الرمز المستخدم في حال عدم العثور على الخط المصدر. يقرأ [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() | يعيد اللغة الافتراضية لنص العرض التقديمي. يقرأ [System::String](../../system/string/). |
| virtual **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() | يحدد ما إذا كان [Aspose.Slides](../) سيحذف جميع الكائنات الثنائية المدمجة أثناء تحميل العرض التقديمي. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() | يحدد مصادر الخطوط الخارجية التي سيستخدمها العرض التقديمي. هذه الخطوط متاحة للعرض طوال عمره ولا تُشارك مع عروض تقديمية أخرى |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() | الرمز لمراقبة طلبات الإيقاف. |
| virtual [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() | يعيد تنسيق عرض تقديمي للتحميل. يقرأ [Slides::LoadFormat](../loadformat/). |
| virtual **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() | هذه الخاصية ذات معنى إذا كان ملف العرض التقديمي محميًا بكلمة مرور. القيمة true تعني أنه يجب تحميل خصائص المستند فقط من ملف عرض تقديمي مشفر ويجب تجاهل كلمة المرور. القيمة false تعني أنه يجب تحميل العرض التقديمي المشفر بالكامل باستخدام كلمة المرور الصحيحة. إذا لم يكن العرض مشفرًا فستُهمل قيمة الخاصية دائمًا. إذا لم تكن خصائص المستند لملف مشفر عامة وكانت قيمة الخاصية true فإن خصائص المستند لا يمكن تحميلها وسيتم رمي استثناء. يقرأ **bool**. |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | يحصل على كلمة المرور. يقرأ [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() | يعيد واجهة الاستدعاء التي تدير تحميل الموارد الخارجية. يقرأ [IResourceLoadingCallback](../iresourceloadingcallback/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() | يمثل الخيارات التي يمكن استخدامها لتحديد سلوك الجداول الإلكترونية الإضافية. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() | يعيد كائنًا يتلقى تحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُلغى. يقرأ [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل عداد الإشارة المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تناظر مشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يُنفّذ قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن بالمرجع كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشتركة بالقيمة المحددة. |
| virtual void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) | يمثل الخيارات التي يمكن استخدامها لإدارة سلوك معالجة الكائنات الثنائية الكبيرة (BLOBs)، مثل استخدام الملفات المؤقتة أو الحد الأقصى لعدد بايتات BLOBs في الذاكرة. تهدف هذه الخيارات إلى ضبط أفضل نسبة بين الأداء واستهلاك الذاكرة لبيئة أو متطلبات معينة. |
| virtual void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) | يضبط الخط الآسيوي المستخدم في حال عدم العثور على الخط المصدر. يكتب [System::String](../../system/string/). |
| virtual void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) | يضبط الخط العادي المستخدم في حال عدم العثور على الخط المصدر. يكتب [System::String](../../system/string/). |
| virtual void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) | يضبط خط الرمز المستخدم في حال عدم العثور على الخط المصدر. يكتب [System::String](../../system/string/). |
| virtual void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) | يضبط اللغة الافتراضية لنص العرض التقديمي. يكتب [System::String](../../system/string/). |
| virtual void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) | يحدد ما إذا كان [Aspose.Slides](../) سيحذف جميع الكائنات الثنائية المدمجة أثناء تحميل العرض التقديمي. |
| virtual void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) | يحدد مصادر الخطوط الخارجية التي سيستخدمها العرض التقديمي. هذه الخطوط متاحة للعرض طوال عمره ولا تُشارك مع عروض تقديمية أخرى |
| virtual void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) | الرمز لمراقبة طلبات الإيقاف. |
| virtual void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) | يضبط تنسيق عرض تقديمي للتحميل. يكتب [Slides::LoadFormat](../loadformat/). |
| virtual void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) | هذه الخاصية ذات معنى إذا كان ملف العرض التقديمي محميًا بكلمة مرور. القيمة true تعني أنه يجب تحميل خصائص المستند فقط من ملف عرض تقديمي مشفر ويجب تجاهل كلمة المرور. القيمة false تعني أنه يجب تحميل العرض التقديمي المشفر بالكامل باستخدام كلمة المرور الصحيحة. إذا لم يكون العرض مشفرًا فستُهمل قيمة الخاصية دائمًا. إذا لم تكن خصائص المستند لملف مشفر عامة وكانت قيمة الخاصية true فإن خصائص المستند لا يمكن تحميلها وسيتم رمي استثناء. يكتب **bool**. |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | يضبط كلمة المرور. يكتب [System::String](../../system/string/). |
| virtual void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) | يضبط واجهة الاستدعاء التي تدير تحميل الموارد الخارجية. يكتب [IResourceLoadingCallback](../iresourceloadingcallback/). |
| virtual void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) | يمثل الخيارات التي يمكن استخدامها لتحديد سلوك الجداول الإلكترونية الإضافية. |
| virtual void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | يضبط كائنًا يتلقى تحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُلغى. يكتب [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يعيّن الوسيط القالب الـ n'th كإشارة ضعيفة (بدلاً من مشتركة). يتيح تحويل الإشارات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشتركة. لا يجب استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد الإشارة المشتركة. لا يجب استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ فك قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا يجب استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا يجب استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |
## انظر أيضًا

* فئة [Object](../../system/object/)
* نطاق [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)