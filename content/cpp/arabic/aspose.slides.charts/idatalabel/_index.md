---
title: IDataLabel
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل تسميات السلسلة.
type: docs
weight: 937
url: /ar/aspose.slides.charts/idatalabel/
---
## IDataLabel فئة

يمثل تسميات السلسلة.

```cpp
class IDataLabel : public Aspose::Slides::Charts::ILayoutable,
                   public Aspose::Slides::Charts::IOverridableText,
                   public Aspose::Slides::Charts::IActualLayout
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | تهيئة TextFrameForOverriding بالنص الموجود في المعامل "text". إذا كان TextFrameForOverriding مُهيّئًا بالفعل فسيقوم ببساطة بتغيير نصه. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان متساويين على الرغم من أن وفقًا لـ IEC 60559:1989 فإن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان متساويين على الرغم من أن وفقًا لـ IEC 60559:1989 فإن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للأغراض الداخلية فقط. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | يحدد الارتفاع الفعلي لعنصر المخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) قبل للحصول على القيم الفعلية. قراءة **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | يحدد العرض الفعلي لعنصر المخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) قبل للحصول على القيم الفعلية. قراءة **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | يحدد الموقع الفعلي للمحور س (اليسار) لعنصر المخطط نسبةً إلى الزاوية اليسرى العليا للمخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) قبل للحصول على القيم الفعلية. قراءة **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | يحدد الجزء العلوي الفعلي لعنصر المخطط نسبةً إلى الزاوية اليسرى العليا للمخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) قبل للحصول على القيم الفعلية. قراءة **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | يحصل على الجزء العلوي لعنصر المخطط كجزء من ارتفاع المخطط. قراءة فقط **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | يرجع المخطط. قراءة فقط [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() | يرجع تنسيق تسمية البيانات. قراءة فقط [IDataLabelFormat](../idatalabelformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | يحدد ارتفاع عنصر المخطط كجزء من ارتفاع المخطط. قراءة **float**. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | False يعني أن تسمية البيانات غير مرئية (وبالتالي جميع أعلام Show*-flags (ShowValue, ...) تكون false). قراءة فقط **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | يرجع العرض التقديمي. قراءة فقط [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | يحصل على الجانب الأيمن لعنصر المخطط كجزء من عرض المخطط. قراءة فقط **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | يرجع الشريحة القاعدية. قراءة فقط [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | يرجع تنسيق نص المخطط. قراءة فقط [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | يمكن أن يحتوي على نص منسق غني. إذا لم تكن هذه الخاصية null، فإن قيمة النص المنسق ستتجاوز النص المولد تلقائيًا. النص المولد تلقائيًا هو خاصية ضمنية لتسمية البيانات، تسمية وحدة عرض محور القيم، عنوان المحور، عنوان المخطط، تسمية خط الاتجاه. يتم تنسيق النص المولد تلقائيًا باستخدام الخاصية [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). قراءة فقط [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() | يحصل على خلية بيانات دفتر العمل. يُطبق إذا كانت الخاصية IDataLabelFormat::get(set)_ShowLabelValueFromCell تساوي true. |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | يحدد عرض عنصر المخطط كجزء من عرض المخطط. قراءة **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | يحدد موقع س (اليسار) لعنصر المخطط كجزء من عرض المخطط. قراءة **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | يحدد الجزء العلوي لعنصر المخطط كجزء من ارتفاع المخطط. قراءة **float**. |
| virtual [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() | يرجع النص الفعلي للتسمية بناءً على إعدادات [DataLabelFormat](../datalabelformat/) أو قيمة TextFrameForOverriding.Text. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual void [Hide](./hide/)() | اجعل تسمية البيانات مخفية بتعيين جميع أعلام Show*-flags (ShowValue, ...) إلى حالة false. ستكون IsVisible false بعد ذلك. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل مثيلًا من النوع الموصوف بـ targetType. تناظر عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | تنفيذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشىء النسخ. لا ينسخ أي شيء فعليًا، إنه يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، إنه يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | يحدد ارتفاع عنصر المخطط كجزء من ارتفاع المخطط. كتابة **float**. |
| virtual void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) | يضبط خلية بيانات دفتر العمل. يُطبق إذا كانت الخاصية IDataLabelFormat::get(set)_ShowLabelValueFromCell تساوي true. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | يحدد عرض عنصر المخطط كجزء من عرض المخطط. كتابة **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | يحدد موقع س (اليسار) لعنصر المخطط كجزء من عرض المخطط. كتابة **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | يحدد الجزء العلوي لعنصر المخطط كجزء من ارتفاع المخطط. كتابة **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | تعيين الوسيط القالب الـ n't إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | تنفيذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | تنفيذ فك قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [ILayoutable](../ilayoutable/)
* الفئة [IOverridableText](../ioverridabletext/)
* الفئة [IActualLayout](../iactuallayout/)
* النطاق [Aspose::Slides::Charts](../)
* المكتبة [Aspose.Slides](../../)