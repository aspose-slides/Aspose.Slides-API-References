---
title: NormalViewProperties
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل خصائص العرض العادي. يتكون العرض العادي من ثلاث مناطق محتوى: الشريحة نفسها، ومنطقة محتوى جانبية، ومنطقة محتوى سفلية."
type: docs
weight: 4525
url: /ar/aspose.slides/normalviewproperties/
---
## NormalViewProperties فئة

يمثل خصائص العرض العادي. يتكون العرض العادي من ثلاث مناطق محتوى: الشريحة نفسها، ومنطقة محتوى جانبية، ومنطقة محتوى سفلية.

```cpp
class NormalViewProperties : public Aspose::Slides::INormalViewProperties
```

## طرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقوم بمحاكاة مقارنة أعداد نقطية عائمة بأسلوب C# حيث يُعتبر NaNان متساويين رغم أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقوم بمحاكاة مقارنة أعداد نقطية عائمة بأسلوب C# حيث يُعتبر NaNان متساويين رغم أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للغرض الداخلي فقط. |
| [SplitterBarStateType](../splitterbarstatetype/) [get_HorizontalBarState](./get_horizontalbarstate/)() override | حدد الحالة التي يجب عرض شريط الفاصل الأفقي فيها. شريط الفاصل الأفقي يفصل الشريحة عن منطقة المحتوى أسفل الشريحة. |
| **bool** [get_PreferSingleView](./get_prefersingleview/)() override | يحدد ما إذا كان المستخدم يفضل رؤية منطقة محتوى واحدة بواجهة نافذة كاملة بدلاً من العرض العادي القياسي الذي يحتوي على ثلاث مناطق محتوى. إذا تم تمكين ذلك، قد يختار التطبيق عرض إحدى مناطق المحتوى في النافذة بالكامل. قراءة **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredLeft](./get_restoredleft/)() override | حدد حجم منطقة المحتوى الجانبية في العرض العادي عندما تكون المنطقة بحجم مستعاد متغير (ليس مصغرًا ولا موسعًا). قراءة فقط [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredTop](./get_restoredtop/)() override | حدد حجم منطقة الشريحة العلوية في العرض العادي عندما تكون المنطقة بحجم مستعاد متغير (ليس مصغرًا ولا موسعًا). قراءة فقط [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| **bool** [get_ShowOutlineIcons](./get_showoutlineicons/)() override | يحدد ما إذا كان التطبيق يجب أن يعرض أيقونات عند عرض محتوى المخطط في أي من مناطق المحتوى في وضع العرض العادي. قراءة **bool**. |
| **bool** [get_SnapVerticalSplitter](./get_snapverticalsplitter/)() override | يحدد ما إذا كان الفاصل الرأسي يجب أن ينتقل إلى حالة مصغرة عندما تكون المنطقة الجانبية صغيرة بما يكفي. قراءة **bool**. |
| [SplitterBarStateType](../splitterbarstatetype/) [get_VerticalBarState](./get_verticalbarstate/)() override | حدد الحالة التي يجب عرض شريط الفاصل الرأسي فيها. شريط الفاصل الرأسي يفصل الشريحة عن المنطقة الجانبية. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجعي المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نسخة مماثلة لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نسخة مماثلة لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الوصف بواسطة targetType. نسخة مماثلة لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ عملية توقيع lock() بلغة C#. استدع مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نسخة مماثلة لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقوم بخفض عداد المرجع المشترك بالقيمة المحددة. |
| void [set_HorizontalBarState](./set_horizontalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) override | حدد الحالة التي يجب عرض شريط الفاصل الأفقي فيها. شريط الفاصل الأفقي يفصل الشريحة عن منطقة المحتوى أسفل الشريحة. |
| void [set_PreferSingleView](./set_prefersingleview/)(**bool**) override | يحدد ما إذا كان المستخدم يفضل رؤية منطقة محتوى واحدة بواجهة نافذة كاملة بدلاً من العرض العادي القياسي الذي يحتوي على ثلاث مناطق محتوى. إذا تم تمكين ذلك، قد يختار التطبيق عرض إحدى مناطق المحتوى في النافذة بالكامل. كتابة **bool**. |
| void [set_ShowOutlineIcons](./set_showoutlineicons/)(**bool**) override | يحدد ما إذا كان التطبيق يجب أن يعرض أيقونات عند عرض محتوى المخطط في أي من مناطق المحتوى في وضع العرض العادي. كتابة **bool**. |
| void [set_SnapVerticalSplitter](./set_snapverticalsplitter/)(**bool**) override | يحدد ما إذا كان الفاصل الرأسي يجب أن ينتقل إلى حالة مصغرة عندما تكون المنطقة الجانبية صغيرة بما يكفي. كتابة **bool**. |
| void [set_VerticalBarState](./set_verticalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) override | حدد الحالة التي يجب عرض شريط الفاصل الرأسي فيها. شريط الفاصل الرأسي يفصل الشريحة عن المنطقة الجانبية. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلًا من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقوم بخفض وإرجاع عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلًا من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نسخة مماثلة لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل lock() في C#. استدع مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلًا من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقوم بخفض عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلًا من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |
## ملاحظات

المثال التالي يوضح كيفية تكوين خصائص [ViewProperties::get_NormalViewProperties](../viewproperties/get_normalviewproperties/) لملف PowerPoint [Presentation](../presentation/). 
```cpp
// إنشاء كائن عرض تقديمي يمثل ملف عرض تقديمي
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto normalViewProperties = pres->get_ViewProperties()->get_NormalViewProperties();

normalViewProperties->set_HorizontalBarState(SplitterBarStateType::Restored);
normalViewProperties->set_VerticalBarState(SplitterBarStateType::Maximized);
normalViewProperties->get_RestoredTop()->set_AutoAdjust(true);
normalViewProperties->get_RestoredTop()->set_DimensionSize(80.0f);
normalViewProperties->set_ShowOutlineIcons(true);
pres->Save(u"presentation_normal_view_state.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* فئة [INormalViewProperties](../inormalviewproperties/)
* نطاق [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)