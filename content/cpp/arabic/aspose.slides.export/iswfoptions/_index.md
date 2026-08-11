---
title: ISwfOptions
second_title: مرجع API Aspose.Slides للغة C++
description: يوفر خيارات تتحكم في طريقة حفظ العرض التقديمي بتنسيق SWF.
type: docs
weight: 469
url: /ar/aspose.slides.export/iswfoptions/
---
## ISwfOptions فئة

توفر خيارات تتحكم في طريقة حفظ العرض التقديمي بتنسيق SWF.

```cpp
class ISwfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## طرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي على نمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي على نمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقطية عائمة على نمط C# حيث تُعامل قيمة NaN مزدوجة كمتساوية رغم أن معيار IEC 60559:1989 ينص على أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقطية عائمة على نمط C# حيث تُعامل قيمة NaN مزدوجة كمتساوية رغم أن معيار IEC 60559:1989 ينص على أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual **bool** [get_Compressed](./get_compressed/)() | يحدد ما إذا كان مستند SWF المُنشأ يجب أن يُضغط أم لا. القيمة الافتراضية هي **true**. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | يعيد الخط المستخدم في حال عدم العثور على الخط الأصلي. يقرأ [System::String](../../system/string/). |
| virtual **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() | تمكين/تعطيل قائمة السياق. القيمة الافتراضية هي true. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | يعيد النمط البصري للتدرج. يقرأ [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | يحدد جودة صور JPEG.\n\n القيمة الافتراضية هي 95. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() | الصورة التي ستُعرض كشعار في الزاوية العليا اليمنى للمُعرض.\n\n يجب أن تكون الصورة PNG بدقة 32×64 بكسل، وإلا قد يُعرض الشعار بشكل غير صحيح. |
| virtual [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() | يحصل على عنوان الارتباط الكامل للشعار. يكون له تأثير فقط إذا تم تحديد [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | يمثل كائن رد نداء لتحديثات حفظ التقدم بالنسبة المئوية. راجع [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_ShowBottomPane](./get_showbottompane/)() | إظهار/إخفاء اللوحة السفلية. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true. |
| virtual **bool** [get_ShowFullScreen](./get_showfullscreen/)() | إظهار/إخفاء زر ملء الشاشة. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | يحدد ما إذا كان المستند المُولد يجب أن يتضمن الشرائح المخفية أم لا. القيمة الافتراضية هي **false**. |
| virtual **bool** [get_ShowLeftPane](./get_showleftpane/)() | إظهار/إخفاء اللوحة اليسرى. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true. |
| virtual **bool** [get_ShowPageBorder](./get_showpageborder/)() | يحدد ما إذا كان ينبغي إظهار الحدود حول الصفحات. القيمة الافتراضية هي true. |
| virtual **bool** [get_ShowPageStepper](./get_showpagestepper/)() | إظهار/إخفاء متحرك الصفحات. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true. |
| virtual **bool** [get_ShowSearch](./get_showsearch/)() | إظهار/إخفاء قسم البحث. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true. |
| virtual **bool** [get_ShowTopPane](./get_showtoppane/)() | إظهار/إخفاء اللوحة العلوية بأكملها. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | يحدد ما إذا كان يجب تخطي الروابط ذات استدعاءات JavaScript عند حفظ العرض التقديمي. يقرأ **bool**. القيمة الافتراضية هي **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | يحصل على الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../islideslayoutoptions/). لا يدعم هذا الخاصية تعيين كائنات من النوع **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** |
| virtual **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() | ابدأ باللوحة اليسرى المفتوحة. يمكن تجاوزها في flashvars. القيمة الافتراضية هي false. |
| virtual **bool** [get_ViewerIncluded](./get_viewerincluded/)() | يحدد ما إذا كان مستند SWF المُولد يجب أن يتضمن العارض المدمج للمستندات أم لا. القيمة الافتراضية هي **true**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | يعيد كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم ستُجهَز. يقرأ [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح إنشاء تجزئة للكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلًا لنوع موضح بواسطة targetType. نظير عامل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | يُنفّذ عملية القفل في عبارة C# lock(). استدعِ مباشرة أو استخدم كائن [LockContext](../../system/lockcontext/) الحراس. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | إنشاء كائن. يهيء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخة. لا ينسخ شيئًا فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمراجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمراجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمؤشر nullptr باستخدام المرجع. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_Compressed](./set_compressed/)(**bool**) | يحدد ما إذا كان مستند SWF المُنشأ يجب أن يُضغط أم لا. القيمة الافتراضية هي **true**. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | يضبط الخط المستخدم في حال عدم العثور على الخط الأصلي. يكتب [System::String](../../system/string/). |
| virtual void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) | تمكين/تعطيل قائمة السياق. القيمة الافتراضية هي true. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | يضبط النمط البصري للتدرج. يكتب [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | يحدد جودة صور JPEG.\n\n القيمة الافتراضية هي 95. |
| virtual void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | الصورة التي ستُعرض كشعار في الزاوية العليا اليمنى للمُعرض.\n\n يجب أن تكون الصورة PNG بدقة 32×64 بكسل، وإلا قد يُعرض الشعار بشكل غير صحيح. |
| virtual void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) | يضبط عنوان الارتباط الكامل للشعار. يكون له تأثير فقط إذا تم تحديد [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | يمثل كائن رد نداء لتحديثات حفظ التقدم بالنسبة المئوية. راجع [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShowBottomPane](./set_showbottompane/)(**bool**) | إظهار/إخفاء اللوحة السفلية. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true. |
| virtual void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) | إظهار/إخفاء زر ملء الشاشة. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | يحدد ما إذا كان المستند المُولد يجب أن يتضمن الشرائح المخفية أم لا. القيمة الافتراضية هي **false**. |
| virtual void [set_ShowLeftPane](./set_showleftpane/)(**bool**) | إظهار/إخفاء اللوحة اليسرى. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true. |
| virtual void [set_ShowPageBorder](./set_showpageborder/)(**bool**) | يحدد ما إذا كان ينبغي إظهار الحدود حول الصفحات. القيمة الافتراضية هي true. |
| virtual void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) | إظهار/إخفاء متحرك الصفحات. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true. |
| virtual void [set_ShowSearch](./set_showsearch/)(**bool**) | إظهار/إخفاء قسم البحث. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true. |
| virtual void [set_ShowTopPane](./set_showtoppane/)(**bool**) | إظهار/إخفاء اللوحة العلوية بأكملها. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | يحدد ما إذا كان يجب تخطي الروابط ذات استدعاءات JavaScript عند حفظ العرض التقديمي. يكتب **bool**. القيمة الافتراضية هي **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../islideslayoutoptions/). لا يدعم هذا الخاصية تعيين كائنات من النوع **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** |
| virtual void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) | ابدأ باللوحة اليسرى المفتوحة. يمكن تجاوزها في flashvars. القيمة الافتراضية هي false. |
| virtual void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) | يحدد ما إذا كان مستند SWF المُولد يجب أن يتضمن العارض المدمج للمستندات أم لا. القيمة الافتراضية هي **true**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | يضبط كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم ستُجهَز. يكتب [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً منه. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً منه. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يُنفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يُنفّذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً منه. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً منه. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## أنظر أيضًا

* فئة [ISaveOptions](../isaveoptions/)
* مساحة الأسماء [Aspose::Slides::Export](../)
* مكتبة [Aspose.Slides](../../)