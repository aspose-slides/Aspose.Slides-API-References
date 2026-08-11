---
title: IChartTitle
second_title: Aspose.Slides للغة C++ مرجع API
description: يمثل خصائص عنوان المخطط.
type: docs
weight: 911
url: /ar/aspose.slides.charts/icharttitle/
---
## IChartTitle فئة

يمثل خصائص عنوان المخطط.

```cpp
class IChartTitle : public Aspose::Slides::Charts::ILayoutable,
                    public Aspose::Slides::Charts::IOverridableText,
                    public Aspose::Slides::Charts::IActualLayout
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | تهيئ TextFrameForOverriding بالنص الموجود في المعامل "text". إذا كان TextFrameForOverriding متهيئاً بالفعل فسيتم تغيير نصه فقط. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | محاكاة مقارنة النقطة العائمة بنمط C# حيث يتم اعتبار NaNين متساويين رغم أنه وفقاً لـ IEC 60559:1989 فإن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | محاكاة مقارنة النقطة العائمة بنمط C# حيث يتم اعتبار NaNين متساويين رغم أنه وفقاً لـ IEC 60559:1989 فإن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | يحدد الارتفاع الفعلي لعنصر المخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) مسبقاً للحصول على القيم الفعلية. قراءة **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | يحدد عرض عنصر المخطط كجزء من عرض المخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) مسبقاً للحصول على القيم الفعلية. قراءة **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | يحدد الموقع الفعلي للمحور x (اليسار) لعنصر المخطط نسبةً إلى الزاوية اليسرى العليا للمخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) مسبقاً للحصول على القيم الفعلية. قراءة **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | يحدد الجزء العلوي الفعلي لعنصر المخطط نسبةً إلى الزاوية اليسرى العليا للمخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) مسبقاً للحصول على القيم الفعلية. قراءة **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | يحصل على الجزء العلوي لعنصر المخطط كجزء من ارتفاع المخطط. **float** للقراءة فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | يعيد المخطط. [IChart](../ichart/) للقراءة فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | يعيد أنماط التعبئة، الخط، التأثير للعنوان. [IFormat](../iformat/) للقراءة فقط. |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | يحدد ارتفاع عنصر المخطط كجزء من ارتفاع المخطط. قراءة **float**. |
| virtual **bool** [get_Overlay](./get_overlay/)() | يحدد ما إذا كان يُسمح للعناصر الأخرى في المخطط بالتداخل مع العنوان. قراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | يعيد العرض التقديمي. [IPresentation](../../aspose.slides/ipresentation/) للقراءة فقط. |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | يحصل على الجزء الأيمن لعنصر المخطط كجزء من عرض المخطط. **float** للقراءة فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | يعيد الشريحة الأساسية. [IBaseSlide](../../aspose.slides/ibaseslide/) للقراءة فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | يعيد تنسيق نص المخطط. [IChartTextFormat](../icharttextformat/) للقراءة فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | يمكن أن يحتوي على نص منسق غني. إذا لم يكن هذا الخاصية فارغاً (null) فإن قيمة النص المنسق ستحل محل النص المُولد تلقائياً. النص المُولد تلقائياً هو خاصية ضمنية لتسمية البيانات، تسمية وحدة العرض لمحور القيم، عنوان المحور، عنوان المخطط، تسمية خط الاتجاه. يتم تنسيق النص المُولد تلقائياً باستخدام الخاصية [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). [ITextFrame](../../aspose.slides/itextframe/) للقراءة فقط. |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | يحدد عرض عنصر المخطط كجزء من عرض المخطط. قراءة **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | يحدد موقع x (اليسار) لعنصر المخطط كجزء من عرض المخطط. قراءة **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | يحدد الجزء العلوي لعنصر المخطط كجزء من ارتفاع المخطط. قراءة **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموضح بواسطة targetType. مماثل لمعامل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | يطبق قفل جملة C# lock(). استدعِها مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | يحدد ارتفاع عنصر المخطط كجزء من ارتفاع المخطط. كتابة **float**. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | يحدد ما إذا كان يُسمح للعناصر الأخرى بالتداخل مع العنوان. كتابة **bool**. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | يحدد عرض عنصر المخطط كجزء من عرض المخطط. كتابة **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | يحدد موقع x (اليسار) لعنصر المخطط كجزء من عرض المخطط. كتابة **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | يحدد الجزء العلوي لعنصر المخطط كجزء من ارتفاع المخطط. كتابة **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلًا من ذلك المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلًا من ذلك المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق فك قفل جملة C# lock(). استدعِها مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلًا من ذلك المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلًا من ذلك المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [ILayoutable](../ilayoutable/)
* الفئة [IOverridableText](../ioverridabletext/)
* الفئة [IActualLayout](../iactuallayout/)
* النطاق [Aspose::Slides::Charts](../)
* المكتبة [Aspose.Slides](../../)