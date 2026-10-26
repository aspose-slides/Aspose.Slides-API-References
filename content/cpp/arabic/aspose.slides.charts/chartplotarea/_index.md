---
title: ChartPlotArea
second_title: مرجع API Aspose.Slides للغة C++
description: يمثل المستطيل الذي يجب رسم المخطط فيه.
type: docs
weight: 248
url: /ar/aspose.slides.charts/chartplotarea/
---
## ChartPlotArea فئة

يمثل المستطيل الذي يجب أن يُرسم فيه المخطط.

```cpp
class ChartPlotArea : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                      public Aspose::Slides::Charts::IChartPlotArea
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوكيات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | محاكاة مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | محاكاة مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **float** [get_ActualHeight](./get_actualheight/)() override | يحدد الارتفاع الفعلي لعنصر المخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولاً للحصول على القيم الفعلية. قراءة **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | يحدد العرض الفعلي لعنصر المخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولاً للحصول على القيم الفعلية. قراءة **float**. |
| **float** [get_ActualX](./get_actualx/)() override | يحدد الموقع الفعلي للمحور x (اليسار) لعنصر المخطط بالنسبة للزاوية اليسرى العليا للمخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولاً للحصول على القيم الفعلية. قراءة **float**. |
| **float** [get_ActualY](./get_actualy/)() override | يحدد أعلى عنصر المخطط بالنسبة للزاوية اليسرى العليا للمخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولاً للحصول على القيم الفعلية. قراءة **float**. |
| **float** [get_Bottom](./get_bottom/)() override | الأسفل. قراءة فقط **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | [Chart](../chart/). قراءة فقط [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | يعيد تنسيق مساحة الرسم. قراءة فقط [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | يعيد ارتفاع صندوق الحد لمنطقة الرسم كنسبة من ارتفاع المخطط (من 0 إلى 1). قراءة **float**. |
| **bool** [get_IsLocationAutocalculated](./get_islocationautocalculated/)() | يحدد كيف يجب حساب الموقع: true \\u2013 محسوب تلقائيًا؛ معرف بواسطة خصائص X, Y, Width, Height. قراءة فقط **bool**. |
| [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() override | إذا تم تعريف تخطيط مساحة الرسم يدويًا، تحدد هذه الخاصية ما إذا كان يجب تخطيط مساحة الرسم من الداخل (بدون المحاور وعناوين المحاور) أو من الخارج (مع المحاور وعناوين المحاور). قراءة [LayoutTargetType](../layouttargettype/). |
| **float** [get_Right](./get_right/)() override | اليمين. قراءة فقط **float**. |
| **float** [get_Width](./get_width/)() override | يعيد عرض صندوق الحد لمنطقة الرسم كنسبة من عرض المخطط (من 0 إلى 1). قراءة **float**. |
| **float** [get_X](./get_x/)() override | يعيد إحداثي x للزاوية العليا اليسرى لصندوق حد مساحة الرسم كنسبة من عرض المخطط (من 0 إلى 1). قراءة **float**. |
| **float** [get_Y](./get_y/)() override | يعيد إحداثي y للزاوية العليا اليسرى لصندوق حد مساحة الرسم كنسبة من ارتفاع المخطط (من 0 إلى 1). قراءة **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجعية المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموضح بواسطة targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل بيان C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يتهيء جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ أي شيء فعليًا، فقط يتهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يتهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Height](./set_height/)(**float**) override | يضبط ارتفاع صندوق الحد لمنطقة الرسم كنسبة من ارتفاع المخطط (من 0 إلى 1). كتابة **float**. |
| void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) override | إذا تم تعريف تخطيط مساحة الرسم يدويًا، تحدد هذه الخاصية ما إذا كان يجب تخطيط مساحة الرسم من الداخل (بدون المحاور وعناوين المحاور) أو من الخارج (مع المحاور وعناوين المحاور). كتابة [LayoutTargetType](../layouttargettype/). |
| void [set_Width](./set_width/)(**float**) override | يضبط عرض صندوق الحد لمنطقة الرسم كنسبة من عرض المخطط (من 0 إلى 1). كتابة **float**. |
| void [set_X](./set_x/)(**float**) override | يضبط إحداثي x للزاوية العليا اليسرى لصندوق حد مساحة الرسم كنسبة من عرض المخطط (من 0 إلى 1). كتابة **float**. |
| void [set_Y](./set_y/)(**float**) override | يضبط إحداثي y للزاوية العليا اليسرى لصندوق حد مساحة الرسم كنسبة من ارتفاع المخطط (من 0 إلى 1). كتابة **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | يضبط الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد المرجع المشترك ويعيده. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل بيان C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحري جميع بنى البيانات الداخلية. |

## انظر أيضاً

* الفئة [DomObject](../../aspose.slides/domobject/)
* الفئة [IChartPlotArea](../ichartplotarea/)
* مساحة الأسماء [Aspose::Slides::Charts](../)
* مكتبة [Aspose.Slides](../../)