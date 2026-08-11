---
title: Legend
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل خصائص وسيلة إيضاح المخطط.
type: docs
weight: 1262
url: /ar/aspose.slides.charts/legend/
---
## Legend فئة

يمثل خصائص وسيلة إيضاح المخطط.

```cpp
class Legend : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
               public Aspose::Slides::Charts::ILegend
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن IEC 60559:1989 تنص على أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن IEC 60559:1989 تنص على أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **float** [get_ActualHeight](./get_actualheight/)() override | يحدد الارتفاع الفعلي لعنصر المخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولًا للحصول على القيم الفعلية. قراءة **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | يحدد العرض الفعلي لعنصر المخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولًا للحصول على القيم الفعلية. قراءة **float**. |
| **float** [get_ActualX](./get_actualx/)() override | يحدد الموقع الفعلي x (اليسار) لعنصر المخطط نسبة إلى الزاوية العليا اليسرى للمخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولًا للحصول على القيم الفعلية. قراءة **float**. |
| **float** [get_ActualY](./get_actualy/)() override | يحدد أعلى عنصر المخطط الفعلي نسبة إلى الزاوية العليا اليسرى للمخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولًا للحصول على القيم الفعلية. قراءة **float**. |
| **float** [get_Bottom](./get_bottom/)() override | أسفل. قراءة فقط **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | يرجع المخطط. قراءة فقط [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() override | يحصل على مدخلات الأسطورة. قراءة فقط [ILegendEntryCollection](../ilegendentrycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) override | يحصل على خصائص مدخل الأسطورة المقابل لنقطة البيانات في المخطط عند الفهرس المحدد. بالنسبة لأنواع المخططات: شريط-دائري, دائري منفصل, دائري منفصل ثلاثي الأبعاد, دائري, دائري ثلاثي الأبعاد, دائري-دائري، تُؤخذ نقطة البيانات من السلسلة الأولى. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | يرجع تنسيق الأسطورة. قراءة فقط [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | يرجع ارتفاع الأسطورة كنسبة من ارتفاع المخطط. قراءة **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | يحدد ما إذا كان يُسمح لعناصر المخطط الأخرى بتغطية الأسطورة. قراءة **bool**. |
| [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() override | يحدد موضع الأسطرة على المخطط. القيم غير NaN للخصائص X و Y و Width و Heigt تتجاوز تأثير هذه الخاصية. قراءة [LegendPositionType](../legendpositiontype/). |
| **float** [get_Right](./get_right/)() override | يمين. قراءة فقط **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | تنسيق النص. قراءة فقط [IChartTextFormat](../icharttextformat/). |
| **float** [get_Width](./get_width/)() override | يرجع عرض الأسطورة كنسبة من عرض المخطط. قراءة **float**. |
| **float** [get_X](./get_x/)() override | يرجع إحداثي x للأسطورة كنسبة من عرض المخطط. قراءة **float**. |
| **float** [get_Y](./get_y/)() override | يرجع إحداثي y للأسطورة كنسبة من ارتفاع المخطط. قراءة **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق ما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن بالمرجعية كائن القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Height](./set_height/)(**float**) override | يضبط ارتفاع الأسطورة كنسبة من ارتفاع المخطط. كتابة **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | يحدد ما إذا كان يُسمح لعناصر المخطط الأخرى بتغطية الأسطورة. كتابة **bool**. |
| void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) override | يحدد موضع الأسطورة على المخطط. القيم غير NaN للخصائص X و Y و Width و Heigt تتجاوز تأثير هذه الخاصية. كتابة [LegendPositionType](../legendpositiontype/). |
| void [set_Width](./set_width/)(**float**) override | يضبط عرض الأسطورة كنسبة من عرض المخطط. كتابة **float**. |
| void [set_X](./set_x/)(**float**) override | يضبط إحداثي x للأسطورة كنسبة من عرض المخطط. كتابة **float**. |
| void [set_Y](./set_y/)(**float**) override | يضبط إحداثي y للأسطورة كنسبة من ارتفاع المخطط. كتابة **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | يضبط الوسيط القالب رقم n كمؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضاً

* فئة [DomObject](../../aspose.slides/domobject/)
* فئة [ILegend](../ilegend/)
* نطاق الاسم [Aspose::Slides::Charts](../)
* مكتبة [Aspose.Slides](../../)