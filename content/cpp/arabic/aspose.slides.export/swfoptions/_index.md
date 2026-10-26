---
title: SwfOptions
second_title: مرجع API Aspose.Slides للغة C++
description: توفر خيارات تتحكم في طريقة حفظ العرض التقديمي بتنسيق Swf.
type: docs
weight: 742
url: /ar/aspose.slides.export/swfoptions/
---
## فئة SwfOptions

توفر خيارات تتحكم في كيفية حفظ العرض التقديمي بتنسيق Swf.

```cpp
class SwfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISwfOptions
```

## طرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام صيغ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNاناثان متساويتين على الرغم من أن معيار IEC 60559:1989 يوضح أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNاناثان متساويتين على الرغم من أن معيار IEC 60559:1989 يوضح أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **bool** [get_Compressed](./get_compressed/)() override | يحدد ما إذا كان يجب ضغط مستند SWF المُولد أم لا. القيمة الافتراضية هي **true**. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | يعيد الخط المستخدم في حالة عدم العثور على الخط المصدر. يقرأ [System::String](../../system/string/). |
| **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() override | تمكين/تعطيل قائمة السياق. القيمة الافتراضية هي true. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | يعيد النمط البصري للتدرج. يقرأ [GradientStyle](../../aspose.slides/gradientstyle/). |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | يحدد جودة صور JPEG. القيمة الافتراضية هي 95. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() override | الصورة التي ستُعرض كشعار في الزاوية العليا اليمنى للمشاهد. يجب أن تكون الصورة PNG بحجم 32x64 بكسل، وإلا قد يُعرض الشعار بصورة غير صحيحة. |
| [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() override | يحصل على عنوان الارتباط الكامل للشعار. له تأثير فقط إذا تم تحديد [set_LogoImageBytes()](./set_logoimagebytes/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | يمثل كائن استدعاء رجعي لتحديثات حفظ التقدم بالنسبة المئوية. انظر [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowBottomPane](./get_showbottompane/)() override | إظهار/إخفاء اللوحة السفلية. يمكن تعديلها في flashvars. القيمة الافتراضية هي true. |
| **bool** [get_ShowFullScreen](./get_showfullscreen/)() override | إظهار/إخفاء زر وضع ملء الشاشة. يمكن تعديلها في flashvars. القيمة الافتراضية هي true. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | يحدد ما إذا كان المستند المُولد يجب أن يتضمن الشرائح المخفية أم لا. القيمة الافتراضية هي **false**. |
| **bool** [get_ShowLeftPane](./get_showleftpane/)() override | إظهار/إخفاء اللوحة اليسرى. يمكن تعديلها في flashvars. القيمة الافتراضية هي true. |
| **bool** [get_ShowPageBorder](./get_showpageborder/)() override | يحدد ما إذا كان يجب إظهار الحد حول الصفحات. القيمة الافتراضية هي true. |
| **bool** [get_ShowPageStepper](./get_showpagestepper/)() override | إظهار/إخفاء أداة تنقل الصفحات. يمكن تعديلها في flashvars. القيمة الافتراضية هي true. |
| **bool** [get_ShowSearch](./get_showsearch/)() override | إظهار/إخفاء قسم البحث. يمكن تعديلها في flashvars. القيمة الافتراضية هي true. |
| **bool** [get_ShowTopPane](./get_showtoppane/)() override | إظهار/إخفاء اللوحة العلوية بالكامل. يمكن تعديلها في flashvars. القيمة الافتراضية هي true. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | يحدد ما إذا كان يجب تخطى الروابط التي تستدعي جافاسكريبت عند حفظ العرض التقديمي. اقرأ **bool**. القيمة الافتراضية هي **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | يحصل على الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../islideslayoutoptions/). هذه الخاصية لا تدعم تعيين كائنات من النوع [HandoutLayoutingOptions](../handoutlayoutingoptions/). |
| **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() override | ابدأ باللوحة اليسرى المفتوحة. يمكن تعديلها في flashvars. القيمة الافتراضية هي false. |
| **bool** [get_ViewerIncluded](./get_viewerincluded/)() override | يحدد ما إذا كان يجب أن يتضمن مستند SWF المُولد عارض المستندات المدمج أم لا. القيمة الافتراضية هي **true**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | يعيد أو يحدد كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو تُجهَز. اقرأ [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عدّاد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لدالة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. مماثل لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل جملة C# lock(). استدعِه مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لدالة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع بنى البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | بناء نسخة. لا ينسخ أي شيء فعليًا، بل يهيء كائنًا جديدًا ويتيح بناء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | مُعامل التعيين. لا ينسخ أي شيء فعليًا، بل يهيء كائنًا جديدًا ويتيح بناء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعًا لكائن من نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشتركة بالقيمة المحددة. |
| [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_Compressed](./set_compressed/)(**bool**) override | يحدد ما إذا كان يجب ضغط مستند SWF المُولد أم لا. القيمة الافتراضية هي **true**. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | يضبط الخط المستخدم في حالة عدم العثور على الخط المصدر. يكتب [System::String](../../system/string/). |
| void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) override | تمكين/تعطيل قائمة السياق. القيمة الافتراضية هي true. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | يضبط النمط البصري للتدرج. يكتب [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | يحدد جودة صور JPEG. القيمة الافتراضية هي 95. |
| void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | الصورة التي ستُعرض كشعار في الزاوية العليا اليمنى للمشاهد. يجب أن تكون الصورة PNG بحجم 32x64 بكسل، وإلا قد يُعرض الشعار بصورة غير صحيحة. |
| void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) override | يضبط عنوان الارتباط الكامل للشعار. له تأثير فقط إذا تم تحديد [set_LogoImageBytes()](./set_logoimagebytes/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | يمثل كائن استدعاء رجعي لتحديثات حفظ التقدم بالنسبة المئوية. انظر [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowBottomPane](./set_showbottompane/)(**bool**) override | إظهار/إخفاء اللوحة السفلية. يمكن تعديلها في flashvars. القيمة الافتراضية هي true. |
| void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) override | إظهار/إخفاء زر وضع ملء الشاشة. يمكن تعديلها في flashvars. القيمة الافتراضية هي true. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | يحدد ما إذا كان يجب أن يتضمن المستند المُولد الشرائح المخفية أم لا. القيمة الافتراضية هي **false**. |
| void [set_ShowLeftPane](./set_showleftpane/)(**bool**) override | إظهار/إخفاء اللوحة اليسرى. يمكن تعديلها في flashvars. القيمة الافتراضية هي true. |
| void [set_ShowPageBorder](./set_showpageborder/)(**bool**) override | يحدد ما إذا كان يجب إظهار الحد حول الصفحات. القيمة الافتراضية هي true. |
| void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) override | إظهار/إخفاء أداة تنقل الصفحات. يمكن تعديلها في flashvars. القيمة الافتراضية هي true. |
| void [set_ShowSearch](./set_showsearch/)(**bool**) override | إظهار/إخفاء قسم البحث. يمكن تعديلها في flashvars. القيمة الافتراضية هي true. |
| void [set_ShowTopPane](./set_showtoppane/)(**bool**) override | إظهار/إخفاء اللوحة العلوية بالكامل. يمكن تعديلها في flashvars. القيمة الافتراضية هي true. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | يحدد ما إذا كان يجب تخطى الروابط التي تستدعي جافاسكريبت عند حفظ العرض التقديمي. اكتب **bool**. القيمة الافتراضية هي **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | يضبط الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../islideslayoutoptions/). هذه الخاصية لا تدعم تعيين كائنات من النوع [HandoutLayoutingOptions](../handoutlayoutingoptions/). |
| void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) override | ابدأ باللوحة اليسرى المفتوحة. يمكن تعديلها في flashvars. القيمة الافتراضية هي false. |
| void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) override | يحدد ما إذا كان يجب أن يتضمن مستند SWF المُولد عارض المستندات المدمج أم لا. القيمة الافتراضية هي **true**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | يعيد أو يحدد كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو تُجهَز. اكتب [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي الـ n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| [SwfOptions](./swfoptions/)() | منشئ افتراضي. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لدالة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل جملة C# lock(). استدعِه مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## ملاحظات

المثال التالي يُظهر كيفية تحويل PowerPoint إلى SWF Flash.
```cpp
auto presentation = System::MakeObject<Presentation>(u"HelloWorld.pptx");
auto swfOptions = System::MakeObject<SwfOptions>();

swfOptions->set_ViewerIncluded(false);
auto notesOptions = swfOptions->get_NotesCommentsLayouting();
notesOptions->set_NotesPosition(NotesPositions::BottomFull);

// Saving presentation and notes pages
presentation->Save(u"SaveAsSwf_out.swf", SaveFormat::Swf, swfOptions);
swfOptions->set_ViewerIncluded(true);
presentation->Save(u"SaveNotes_out.swf", SaveFormat::Swf, swfOptions);
```

## انظر أيضًا

* الفئة [SaveOptions](../saveoptions/)
* الفئة [ISwfOptions](../iswfoptions/)
* النطاق [Aspose::Slides::Export](../)
* المكتبة [Aspose.Slides](../../)