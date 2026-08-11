---
title: ILegend
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يمثل خصائص أسطورة المخطط.
type: docs
weight: 1080
url: /ar/aspose.slides.charts/ilegend/
---
## ILegend الفئة

يمثل خصائص أسطورة المخطط.

```cpp
class ILegend : public Aspose::Slides::Charts::ILayoutable,
                public Aspose::Slides::Charts::IFormattedTextContainer,
                public Aspose::Slides::Charts::IActualLayout
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوكيات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين رغم أنه وفقًا لـ IEC 60559:1989 فإن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين رغم أنه وفقًا لـ IEC 60559:1989 فإن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | يحدد الارتفاع الفعلي لعنصر المخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولاً للحصول على القيم الفعلية. قراءة **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | يحدد العرض الفعلي لعنصر المخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولاً للحصول على القيم الفعلية. قراءة **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | يحدد الموقع الفعلي لمحور x (اليسار) لعنصر المخطط بالنسبة للزاوية العلوية اليسرى للمخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولاً للحصول على القيم الفعلية. قراءة **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | يحدد الجزء العلوي الفعلي لعنصر المخطط بالنسبة للزاوية العلوية اليسرى للمخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولاً للحصول على القيم الفعلية. قراءة **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | يحصل على الجزء العلوي لعنصر المخطط كنسبة من ارتفاع المخطط. للقراءة فقط **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | يعيد المخطط. للقراءة فقط [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() | يحصل على مدخلات الأسطورة. للقراءة فقط [ILegendEntryCollection](../ilegendentrycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) | يحصل على خصائص مدخل الأسطورة المقابل لنقطة البيانات في المخطط عند الفهرس المحدد. في حالة أنواع المخططات: شريط-دائري، دائري منفصل، دائري منفصل ثلاثي الأبعاد، دائري، دائري ثلاثي الأبعاد، دائري داخل دائري، تُؤخذ نقطة البيانات من السلسلة الأولى. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | يعيد تنسيق الأسطورة. للقراءة فقط [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | يحدد ارتفاع عنصر المخطط كنسبة من ارتفاع المخطط. قراءة **float**. |
| virtual **bool** [get_Overlay](./get_overlay/)() | يحدد ما إذا كان يُسمح لعناصر المخطط الأخرى بتغطية الأسطورة. قراءة **bool**. |
| virtual [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() | يحدد موضع الأسطورة على المخطط. قيم X وY والعرض والارتفاع غير NaN تتجاوز تأثير هذه الخاصية. قراءة [LegendPositionType](../legendpositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | يعيد العرض التقديمي. للقراءة فقط [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | يحصل على الجانب الأيمن لعنصر المخطط كنسبة من عرض المخطط. للقراءة فقط **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | يعيد الشريحة الأساسية. للقراءة فقط [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | يعيد تنسيق نص المخطط. للقراءة فقط [IChartTextFormat](../icharttextformat/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | يحدد عرض عنصر المخطط كنسبة من عرض المخطط. قراءة **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | يحدد موقع x (اليسار) لعنصر المخطط كنسبة من عرض المخطط. قراءة **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | يحدد الجزء العلوي لعنصر المخطط كنسبة من ارتفاع المخطط. قراءة **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لأسلوب C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بواسطة targetType. مماثل لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل تعبير C# lock(). استدعِ مباشرةً أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لأسلوب C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يتهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات حسب المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات حسب المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | يحدد ارتفاع عنصر المخطط كنسبة من ارتفاع المخطط. كتابة **float**. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | يحدد ما إذا كان يُسمح لعناصر المخطط الأخرى بتغطية الأسطورة. كتابة **bool**. |
| virtual void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) | يحدد موضع الأسطورة على المخطط... كتابة [LegendPositionType](../legendpositiontype/). |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | يحدد عرض عنصر المخطط كنسبة من عرض المخطط. كتابة **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | يحدد موقع x (اليسار) لعنصر المخطط كنسبة من عرض المخطط. كتابة **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | يحدد الجزء العلوي لعنصر المخطط كنسبة من ارتفاع المخطط. كتابة **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من المشتركة). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعدد عداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لأسلوب C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل تعبير C# lock(). استدعِ مباشرةً أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [ILayoutable](../ilayoutable/)
* الفئة [IFormattedTextContainer](../iformattedtextcontainer/)
* الفئة [IActualLayout](../iactuallayout/)
* النطاق [Aspose::Slides::Charts](../)
* المكتبة [Aspose.Slides](../../)