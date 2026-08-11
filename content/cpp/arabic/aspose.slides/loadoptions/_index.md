---
title: LoadOptions
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يسمح بتحديد خيارات إضافية (مثل التنسيق أو الخط الافتراضي) عند تحميل عرض تقديمي.
type: docs
weight: 4395
url: /ar/aspose.slides/loadoptions/
---
## فئة LoadOptions

يسمح بتحديد خيارات إضافية (مثل الصيغة أو الخط الافتراضي) عند تحميل عرض تقديمي.

```cpp
class LoadOptions : public Aspose::Slides::ILoadOptions
```

## الطرق

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوكيات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | محاكاة مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يوضح أن NaN ليس مساوياً لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | محاكاة مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يوضح أن NaN ليس مساوياً لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() override | يمثل الخيارات التي يمكن استخدامها لإدارة سلوك معالجة الكائنات الكبيرة الثنائية (BLOBs)، مثل استخدام الملفات المؤقتة أو الحد الأقصى لعدد بايتات BLOBs في الذاكرة. تُصمم هذه الخيارات لضبط أفضل نسبة أداء/استهلاك للذاكرة لبيئة أو متطلبات معينة. |
| [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() override | يعيد الخط الآسيوي المستخدم إذا لم يتم العثور على الخط المصدر. اقرأ [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() override | يعيد الخط العادي المستخدم إذا لم يتم العثور على الخط المصدر. اقرأ [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() override | يعيد خط الرموز المستخدم إذا لم يتم العثور على الخط المصدر. اقرأ [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() override | يعيد اللغة الافتراضية لنص العرض التقديمي. اقرأ [System::String](../../system/string/). |
| **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() override | يحدد ما إذا كان [Aspose.Slides](../) سيحذف جميع الكائنات الثنائية المدمجة أثناء تحميل العرض التقديمي. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() override | يحدد مصادر الخطوط الخارجية التي سيستخدمها العرض التقديمي. هذه الخطوط متاحة للعرض طوال عمره ولا يتم مشاركتها مع عروض تقديمية أخرى |
| [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() override | الرمز المميز لمراقبة طلبات الإيقاف. |
| [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() override | يعيد تنسيق العرض التقديمي للتحميل. اقرأ [Slides::LoadFormat](../loadformat/). |
| **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() override | هذه الخاصية ذات معنى إذا كان ملف العرض محمياً بكلمة مرور. القيمة true تعني أنه يجب تحميل خصائص المستند فقط من ملف عرض مشفر وتجاهل كلمة المرور. القيمة false تعني أنه يجب تحميل كامل العرض المشفر باستخدام كلمة المرور الصحيحة. إذا لم يكن العرض مشفراً فإن قيمة الخاصية تُهمل دائماً. إذا لم تكن خصائص المستند لملف مشفر عامة وكانت قيمة الخاصية true فإنه لا يمكن تحميل خصائص المستند وسيتم إلقاء استثناء. اقرأ **bool**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | يحصل على كلمة المرور. اقرأ [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() override | يعيد واجهة الاستدعاء التي تُدير تحميل الموارد الخارجية. اقرأ [IResourceLoadingCallback](../iresourceloadingcallback/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() override | يحصل على الخيارات لجداول البيانات. على سبيل المثال، تؤثر هذه الخيارات على حساب الصيغ للرسوم البيانية. |
| [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() override | يعيد كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم تُوقف. اقرأ [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير عامل C# 'is'. |
|  [LoadOptions](./loadoptions/)() | إنشاء خيارات تحميل افتراضية جديدة. |
|  [LoadOptions](./loadoptions/)([Aspose::Slides::LoadFormat](../loadformat/)) | إنشاء خيارات تحميل جديدة. |
| void [Lock](../../system/object/lock/)() | تنفيذ قفل تعليمة C# lock(). استدعِ مباشرةً أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | إنشاء الكائن. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن نوع قيم مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقوم بتقليل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) override | يمثل الخيارات التي يمكن استخدامها لإدارة سلوك معالجة الكائنات الكبيرة الثنائية (BLOBs)، مثل استخدام الملفات المؤقتة أو الحد الأقصى لعدد بايتات BLOBs في الذاكرة. تُصمم هذه الخيارات لضبط أفضل نسبة أداء/استهلاك للذاكرة لبيئة أو متطلبات معينة. |
| void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) override | يضبط الخط الآسيوي المستخدم إذا لم يتم العثور على الخط المصدر. اكتب [System::String](../../system/string/). |
| void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) override | يضبط الخط العادي المستخدم إذا لم يتم العثور على الخط المصدر. اكتب [System::String](../../system/string/). |
| void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) override | يضبط خط الرموز المستخدم إذا لم يتم العثور على الخط المصدر. اكتب [System::String](../../system/string/). |
| void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) override | يضبط اللغة الافتراضية لنص العرض التقديمي. اكتب [System::String](../../system/string/). |
| void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) override | يحدد ما إذا كان [Aspose.Slides](../) سيحذف جميع الكائنات الثنائية المدمجة أثناء تحميل العرض التقديمي. |
| void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) override | يحدد مصادر الخطوط الخارجية التي سيستخدمها العرض التقديمي. هذه الخطوط متاحة للعرض طوال عمره ولا يتم مشاركتها مع عروض تقديمية أخرى |
| void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) override | الرمز المميز لمراقبة طلبات الإيقاف. |
| void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) override | يضبط تنسيق العرض التقديمي للتحميل. اكتب [Slides::LoadFormat](../loadformat/). |
| void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) override | هذه الخاصية ذات معنى إذا كان ملف العرض محمياً بكلمة مرور. القيمة true تعني أنه يجب تحميل خصائص المستند فقط من ملف عرض مشفر وتجاهل كلمة المرور. القيمة false تعني أنه يجب تحميل كامل العرض المشفر باستخدام كلمة المرور الصحيحة. إذا لم يكن العرض مشفراً فإن قيمة الخاصية تُهمل دائماً. إذا لم تكن خصائص المستند لملف مشفر عامة وكانت قيمة الخاصية true فإنه لا يمكن تحميل خصائص المستند وسيتم إلقاء استثناء. اكتب **bool**. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | يضبط كلمة المرور. اكتب [System::String](../../system/string/). |
| void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) override | يضبط واجهة الاستدعاء التي تدير تحميل الموارد الخارجية. اكتب [IResourceLoadingCallback](../iresourceloadingcallback/). |
| void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) override | يحصل على الخيارات لجداول البيانات. على سبيل المثال، تؤثر هذه الخيارات على حساب الصيغ للرسوم البيانية. |
| void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | يضبط كائنًا يتلقى التحذيرات ويقرر ما إذا ستستمر عملية التحميل أو تُوقف. اكتب [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبية n'th إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقوم بتقليل وإرجاع عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | تنفيذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | تنفيذ إلغاء قفل تعليمة C# lock(). استدعِ مباشرةً أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقوم بتقليل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |
## انظر أيضًا

* الفئة [ILoadOptions](../iloadoptions/)
* المجال [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)