---
title: DataLabel
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل تسميات السلسلة.
type: docs
weight: 365
url: /ar/aspose.slides.charts/datalabel/
---
## فئة DataLabel

Represents a series labels.

```cpp
class DataLabel : public Aspose::Slides::Charts::IDataLabel,
                  public Aspose::Slides::IDOMObject
```

## الأساليب

| طريقة | الوصف |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | تهيئة TextFrameForOverriding بالنص الموجود في المعامل "text". إذا تم تهيئة TextFrameForOverriding مسبقًا فسيتم تعديل نصه فقط. |
|  [DataLabel](./datalabel/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) | ينشئ مثالًا جديدًا من الفئة [DataLabel](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام أسلوب [Object.Equals](../../system/object/equals/) في C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمة NaN مزدوجة متساوية على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمة NaN مزدوجة متساوية على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **float** [get_ActualHeight](./get_actualheight/)() override | يحدد الارتفاع الفعلي لعنصر المخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولاً للحصول على القيم الفعلية. قراءة **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | يحدد العرض الفعلي لعنصر المخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولاً للحصول على القيم الفعلية. قراءة **float**. |
| **float** [get_ActualX](./get_actualx/)() override | يحدد الموقع الفعلي للمحور x (اليسار) لعنصر المخطط بالنسبة إلى الزاوية اليسرى العليا للمخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولاً للحصول على القيم الفعلية. قراءة **float**. |
| **float** [get_ActualY](./get_actualy/)() override | يحدد الجزء العلوي الفعلي لعنصر المخطط بالنسبة إلى الزاوية اليسرى العليا للمخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولاً للحصول على القيم الفعلية. قراءة **float**. |
| **float** [get_Bottom](./get_bottom/)() override | الأسفل. قراءة فقط **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | يعيد المخطط الأب. قراءة فقط [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() override | يعيد تنسيق تسمية البيانات. قراءة فقط [IDataLabelFormat](../idatalabelformat/). |
| **float** [get_Height](./get_height/)() override | يعيد ارتفاع العنوان كنسبة من ارتفاع المخطط. قراءة **float**. |
| **bool** [get_IsVisible](./get_isvisible/)() override | False يعني أن تسمية البيانات غير مرئية (وبالتالي جميع أعلام Show* (ShowValue, ...) تكون false). قراءة فقط **bool**. |
| **float** [get_Right](./get_right/)() override | اليمين. قراءة فقط **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | يعيد تنسيق النص. قراءة فقط [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | يمكن أن يحتوي على نص منسق غني. إذا لم تكن هذه الخاصية null فستتجاوز قيمة النص المنسق النص المُولد تلقائيًا لتسمية البيانات. النص المُولد تلقائيًا لتسمية البيانات يعني النص الذي تُديره خصائص ShowSeriesName، ShowValue، ... ويتم تنسيقه باستخدام خاصية TextFormatManager.TextFormat. قراءة فقط [ITextFrame](../../aspose.slides/itextframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() override | يحصل على خلية البيانات في دفتر العمل. يُطبق إذا كانت خاصية IDataLabelFormat::get(set)_ShowLabelValueFromCell تساوي true. |
| **float** [get_Width](./get_width/)() override | يعيد عرض العنوان كنسبة من عرض المخطط. قراءة **float**. |
| **float** [get_X](./get_x/)() override | يعيد إحداثي x للعنوان كنسبة من عرض المخطط. قراءة **float**. |
| **float** [get_Y](./get_y/)() override | يعيد إحداثي y للعنوان كنسبة من ارتفاع المخطط. قراءة **float**. |
| [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() override | يعيد نص التسمية الفعلي بناءً على إعدادات [DataLabelFormat](../datalabelformat/) أو قيمة [get_TextFrameForOverriding()](./get_textframeforoverriding/)->get(set)_Text(). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Hide](./hide/)() override | يجعل تسمية البيانات مخفيًا عن طريق ضبط جميع أعلام Show* (ShowValue, ...) إلى الحالة false. سيكون IsVisible false بعد ذلك. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يتهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن المرجعية كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجع المشترك بقيمة محددة. |
| void [set_Height](./set_height/)(**float**) override | يضبط ارتفاع العنوان كنسبة من ارتفاع المخطط. كتابة **float**. |
| void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) override | يضبط خلية بيانات دفتر العمل. يُطبق إذا كانت خاصية IDataLabelFormat::get(set)_ShowLabelValueFromCell تساوي true. |
| void [set_Width](./set_width/)(**float**) override | يضبط عرض العنوان كنسبة من عرض المخطط. كتابة **float**. |
| void [set_X](./set_x/)(**float**) override | يضبط إحداثي x للعنوان كنسبة من عرض المخطط. كتابة **float**. |
| void [set_Y](./set_y/)(**float**) override | يضبط إحداثي y للعنوان كنسبة من ارتفاع المخطط. كتابة **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط معامل القالب رقم n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتبديل المؤشرات في الحاويات إلى وضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعدد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |
## انظر أيضًا

* الفئة [IDataLabel](../idatalabel/)
* الفئة [IDOMObject](../../aspose.slides/idomobject/)
* النطاق [Aspose::Slides::Charts](../)
* المكتبة [Aspose.Slides](../../)