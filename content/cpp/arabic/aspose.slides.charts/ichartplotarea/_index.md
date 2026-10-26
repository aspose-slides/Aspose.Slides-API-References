---
title: IChartPlotArea
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يمثل خصائص عنوان المخطط.
type: docs
weight: 794
url: /ar/aspose.slides.charts/ichartplotarea/
---
## IChartPlotArea فئة

يمثل خصائص عنوان المخطط.

```cpp
class IChartPlotArea : public Aspose::Slides::Charts::ILayoutable,
                       public Aspose::Slides::Charts::IActualLayout
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يعتبر اثنان من NaN متساويين رغم أنه وفقًا لـ IEC 60559:1989 لا يعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يعتبر اثنان من NaN متساويين رغم أنه وفقًا لـ IEC 60559:1989 لا يعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | يحدد الارتفاع الفعلي لعنصر المخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولاً للحصول على القيم الفعلية. قراءة **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | يحدد العرض الفعلي لعنصر المخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولاً للحصول على القيم الفعلية. قراءة **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | يحدد الموقع الفعلي للمحور س (اليسار) لعنصر المخطط بالنسبة إلى الزاوية العليا اليسرى للمخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولاً للحصول على القيم الفعلية. قراءة **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | يحدد الجزء العلوي الفعلي لعنصر المخطط بالنسبة إلى الزاوية العليا اليسرى للمخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولاً للحصول على القيم الفعلية. قراءة **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | يحصل على الجزء العلوي لعنصر المخطط كنسبة من ارتفاع المخطط. **float** للقراءة فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | يعيد المخطط. [IChart](../ichart/) للقراءة فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | يعيد تنسيق مساحة الرسم. [IFormat](../iformat/) للقراءة فقط. |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | يحدد ارتفاع عنصر المخطط كنسبة من ارتفاع المخطط. قراءة **float**. |
| virtual [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() | إذا تم تعريف تخطيط مساحة الرسم يدويًا، تحدد هذه الخاصية ما إذا كان يتم تخطيط مساحة الرسم من الداخل (بدون المحاور وعناوين المحاور) أو من الخارج (مع المحاور وعناوين المحاور). [LayoutTargetType](../layouttargettype/) للقراءة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | يعيد العرض. [IPresentation](../../aspose.slides/ipresentation/) للقراءة فقط. |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | يحصل على الجانب الأيمن لعنصر المخطط كنسبة من عرض المخطط. **float** للقراءة فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | يعيد الشريحة الأساسية. [IBaseSlide](../../aspose.slides/ibaseslide/) للقراءة فقط. |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | يحدد عرض عنصر المخطط كنسبة من عرض المخطط. قراءة **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | يحدد موقع س (اليسار) لعنصر المخطط كنسبة من عرض المخطط. قراءة **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | يحدد الجزء العلوي لعنصر المخطط كنسبة من ارتفاع المخطط. قراءة **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد الإشارة المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يمكّن تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير معامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ تأمين عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يمكّن استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، فقط يهيّئ كائنًا جديدًا ويمكّن من إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيّئ كائنًا جديدًا ويمكّن من إنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجعية مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد الإشارة المشتركة بالقيمة المحددة. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | يحدد ارتفاع عنصر المخطط كنسبة من ارتفاع المخطط. كتابة **float**. |
| virtual void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) | إذا تم تعريف تخطيط مساحة الرسم يدويًا، تحدد هذه الخاصية ما إذا كان يتم تخطيط مساحة الرسم من الداخل (بدون المحاور وعناوين المحاور) أو من الخارج (مع المحاور وعناوين المحاور). اكتب [LayoutTargetType](../layouttargettype/). |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | يحدد عرض عنصر المخطط كنسبة من عرض المخطط. كتابة **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | يحدد موقع س (اليسار) لعنصر المخطط كنسبة من عرض المخطط. كتابة **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | يحدد الجزء العلوي لعنصر المخطط كنسبة من ارتفاع المخطط. كتابة **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب النوني كإشارة ضعيفة (بدلاً من مشاركة). يتيح تحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد الإشارة المشترك. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عدّاد الإشارة المشترك ويعيده. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يمكّن تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء تأمين عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد الإشارة الضعيفة. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد الإشارة الضعيفة. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* الفئة [ILayoutable](../ilayoutable/)
* الفئة [IActualLayout](../iactuallayout/)
* النطاق [Aspose::Slides::Charts](../)
* المكتبة [Aspose.Slides](../../)