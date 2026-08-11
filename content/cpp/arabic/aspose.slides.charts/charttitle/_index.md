---
title: ChartTitle
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل خصائص عنوان المخطط.
type: docs
weight: 326
url: /ar/aspose.slides.charts/charttitle/
---
## فئة ChartTitle

يمثل خصائص عنوان المخطط.

```cpp
class ChartTitle : public Aspose::Slides::Charts::IChartTitle,
                   public Aspose::Slides::IDOMObject
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | قم بتهيئة TextFrameForOverriding بالنص في المعامل \"text\". إذا كان TextFrameForOverriding مُهيأً بالفعل فسيتم فقط تغيير نصه. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يتم اعتبار NaNين متساويين رغم أنه وفقًا لـ IEC 60559:1989 فإن NaN ليس متساويًا مع أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يتم اعتبار NaNين متساويين رغم أنه وفقًا لـ IEC 60559:1989 فإن NaN ليس متساويًا مع أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **float** [get_ActualHeight](./get_actualheight/)() override | يحدد الارتفاع الفعلي لعنصر المخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولاً للحصول على القيم الفعلية. قراءة **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | يحدد العرض الفعلي لعنصر المخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولاً للحصول على القيم الفعلية. قراءة **float**. |
| **float** [get_ActualX](./get_actualx/)() override | يحدد الموقع الفعلي على المحور x (اليسار) لعنصر المخطط بالنسبة للزاوية اليسرى العليا للمخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولاً للحصول على القيم الفعلية. قراءة **float**. |
| **float** [get_ActualY](./get_actualy/)() override | يحدد أعلى عنصر المخطط بالنسبة للزاوية اليسرى العليا للمخطط. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) أولاً للحصول على القيم الفعلية. قراءة **float**. |
| **float** [get_Bottom](./get_bottom/)() override | القاع. قراءة فقط **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | يعيد المخطط الأب. قراءة فقط [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | يعيد أنماط التعبئة، الخط، والتأثير لعنوان. قراءة فقط [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | يعيد ارتفاع العنوان كنسبة من ارتفاع المخطط. قراءة **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | يحدد ما إذا كان يُسمح لعناصر المخطط الأخرى بالتراكب مع العنوان. قراءة **bool**. |
| **float** [get_Right](./get_right/)() override | يمين. قراءة فقط **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | يعيد تنسيق النص. قراءة فقط [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | يمكنه احتواء نص غني بالتنسيق. إذا لم تكن هذه الخاصية فارغة (null) فإن قيمة النص المنسق ستُعيد كتابة النص المُنشأ تلقائيًا. النص المُنشأ تلقائيًا هو خاصية ضمنية لعلامة البيانات، علامة وحدة العرض للمحور القيمي، عنوان المحور، عنوان المخطط، تسمية خط الاتجاه. يتم تنسيق النص المُنشأ تلقائيًا باستخدام الخاصية [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). قراءة فقط [ITextFrame](../../aspose.slides/itextframe/). |
| **float** [get_Width](./get_width/)() override | يعيد عرض العنوان كنسبة من عرض المخطط. قراءة **float**. |
| **float** [get_X](./get_x/)() override | يعيد إحداثي x للعنوان كنسبة من عرض المخطط. قراءة **float**. |
| **float** [get_Y](./get_y/)() override | يعيد إحداثي y للعنوان كنسبة من ارتفاع المخطط. قراءة **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل تعبير C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح نسخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيء كائنًا جديدًا ويمكّن من إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيء كائنًا جديدًا ويمكّن من إنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجعية مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Height](./set_height/)(**float**) override | يضبط ارتفاع العنوان كنسبة من ارتفاع المخطط. كتابة **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | يحدد ما إذا كان يُسمح لعناصر المخطط الأخرى بالتراكب مع العنوان. كتابة **bool**. |
| void [set_Width](./set_width/)(**float**) override | يضبط عرض العنوان كنسبة من عرض المخطط. كتابة **float**. |
| void [set_X](./set_x/)(**float**) override | يضبط إحداثي x للعنوان كنسبة من عرض المخطط. كتابة **float**. |
| void [set_Y](./set_y/)(**float**) override | يضبط إحداثي y للعنوان كنسبة من ارتفاع المخطط. كتابة **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضع الوسيط القالب رقم n كإشارة ضعيفة (بدلاً من المشتركة). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل تعبير C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يقوم بتدمير الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [IChartTitle](../icharttitle/)
* فئة [IDOMObject](../../aspose.slides/idomobject/)
* مساحة أسماء [Aspose::Slides::Charts](../)
* مكتبة [Aspose.Slides](../../)