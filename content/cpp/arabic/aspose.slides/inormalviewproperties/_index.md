---
title: INormalViewProperties
second_title: Aspose.Slides لـ C++ مرجع API
description: "يمثل خصائص العرض العادي. يتكون العرض العادي من ثلاث مناطق محتوى: الشريحة نفسها، منطقة محتوى جانبية، ومنطقة محتوى سفلية."
type: docs
weight: 2978
url: /ar/aspose.slides/inormalviewproperties/
---
## فئة INormalViewProperties

يمثل خصائص العرض العادي. يتكون العرض العادي من ثلاث مناطق محتوى: الشريحة نفسها، منطقة محتوى جانبية، ومنطقة محتوى سفلية.

```cpp
class INormalViewProperties : public virtual System::Object
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة من نوع double بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| virtual [SplitterBarStateType](../splitterbarstatetype/) [get_HorizontalBarState](./get_horizontalbarstate/)() | يحدد الحالة التي يجب أن يُعرض فيها شريط الفاصل الأفقي. شريط الفاصل الأفقي يفصل الشريحة عن منطقة المحتوى أسفل الشريحة. |
| virtual **bool** [get_PreferSingleView](./get_prefersingleview/)() | يحدد ما إذا كان المستخدم يفضّل رؤية منطقة محتوى واحدة بملء النافذة بدلاً من العرض العادي القياسي الذي يحتوي على ثلاث مناطق محتوى. إذا تم تمكينه، قد يختار التطبيق عرض إحدى مناطق المحتوى في كامل النافذة. قراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredLeft](./get_restoredleft/)() | هذا العنصر يحدد حجم منطقة المحتوى الجانبية في العرض العادي، عندما تكون المنطقة ذات حجم مستعاد متغيّر (ليس مصغرة ولا مكبرة). قراءة فقط [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredTop](./get_restoredtop/)() | هذا العنصر يحدد حجم منطقة الشريحة العليا في العرض العادي، عندما تكون المنطقة ذات حجم مستعاد متغيّر (ليس مصغرة ولا مكبرة). قراءة فقط [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| virtual **bool** [get_ShowOutlineIcons](./get_showoutlineicons/)() | يحدد ما إذا كان التطبيق يجب أن يعرض أيقونات عند عرض محتوى المخطط في أي من مناطق المحتوى في وضع العرض العادي. قراءة **bool**. |
| virtual **bool** [get_SnapVerticalSplitter](./get_snapverticalsplitter/)() | يحدد ما إذا كان الفاصل العمودي يجب أن يلتقط إلى حالة مصغرة عندما تكون المنطقة الجانبية صغيرة بشكل كافٍ. قراءة **bool**. |
| virtual [SplitterBarStateType](../splitterbarstatetype/) [get_VerticalBarState](./get_verticalbarstate/)() | يحدد الحالة التي يجب أن يُعرض فيها شريط الفاصل العمودي. شريط الفاصل العمودي يفصل الشريحة عن منطقة المحتوى الجانبية. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مقابل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مقارن لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلاً للنوع الموصوف بـ targetType. مقارن لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل جملة C# lock(). يُستدعى مباشرة أو يستخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مقابل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_HorizontalBarState](./set_horizontalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) | يحدد الحالة التي يجب أن يُعرض فيها شريط الفاصل الأفقي. شريط الفاصل الأفقي يفصل الشريحة عن منطقة المحتوى أسفل الشريحة. |
| virtual void [set_PreferSingleView](./set_prefersingleview/)(**bool**) | يحدد ما إذا كان المستخدم يفضّل رؤية منطقة محتوى واحدة بملء النافذة بدلاً من العرض العادي القياسي الذي يحتوي على ثلاث مناطق محتوى. إذا تم تمكينه، قد يختار التطبيق عرض إحدى مناطق المحتوى في كامل النافذة. كتابة **bool**. |
| virtual void [set_ShowOutlineIcons](./set_showoutlineicons/)(**bool**) | يحدد ما إذا كان التطبيق يجب أن يعرض أيقونات عند عرض محتوى المخطط في أي من مناطق المحتوى في وضع العرض العادي. كتابة **bool**. |
| virtual void [set_SnapVerticalSplitter](./set_snapverticalsplitter/)(**bool**) | يحدد ما إذا كان الفاصل العمودي يجب أن يلتقط إلى حالة مصغرة عندما تكون المنطقة الجانبية صغيرة بشكل كافٍ. كتابة **bool**. |
| virtual void [set_VerticalBarState](./set_verticalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) | يحدد الحالة التي يجب أن يُعرض فيها شريط الفاصل العمودي. شريط الفاصل العمودي يفصل الشريحة عن منطقة المحتوى الجانبية. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط وسيط القالب رقم n ليكون مؤشرًا ضعيفًا (بدلاً من المشترك). يتيح تحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مقابل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ فك قفل جملة C# lock(). يُستدعى مباشرة أو يستخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## أنظر أيضًا

* فئة [Object](../../system/object/)
* مساحة الاسم [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)