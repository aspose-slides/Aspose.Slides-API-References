---
title: IChartParagraphFormat
second_title: مرجع API Aspose.Slides للغة C++
description: يمثل خصائص تنسيق الفقرات لمخطط.
type: docs
weight: 781
url: /ar/aspose.slides.charts/ichartparagraphformat/
---
## IChartParagraphFormat فئة


يمثل خصائص تنسيق الفقرات لمخطط.

```cpp
class IChartParagraphFormat : public virtual System::Object
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يُشير إلى أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يُشير إلى أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لغايات داخلية فقط. |
| virtual [TextAlignment](../../aspose.slides/textalignment/) [get_Alignment](./get_alignment/)() | يعيد محاذاة النص في الفقرة. اقرأ [TextAlignment](../../aspose.slides/textalignment/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | يعيد حجم التبويب الافتراضي. اقرأ **float**. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | يحدد ما إذا كان كسر السطر شرق آسيوي يُستخدم في الفقرة. اقرأ [NullableBool](../../aspose.slides/nullablebool/). |
| virtual [Aspose::Slides::FontAlignment](../../aspose.slides/fontalignment/) [get_FontAlignment](./get_fontalignment/)() | يعيد محاذاة الخط في الفقرة. اقرأ [Slides::FontAlignment](../../aspose.slides/fontalignment/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | يحدد ما إذا كان الترقيم المعلق يُستخدم في الفقرة. اقرأ [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_Indent](./get_indent/)() | يعيد إزاحة السطر الأول/الإزاحة المتدلية للفقرة. يمكن تعريف الإزاحة المتدلية بقيم سالبة. اقرأ **float**. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | يحدد ما إذا كان كسر السطر اللاتيني يُستخدم في الفقرة. اقرأ [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | يعيد الهامش الأيسر في الفقرة. اقرأ **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | يعيد الهامش الأيمن في الفقرة. اقرأ **float**. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_RightToLeft](./get_righttoleft/)() | يحدد ما إذا كان الكتابة من اليمين إلى اليسار يُستخدم في الفقرة. اقرأ [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | يعيد مقدار المسافة بعد السطر الأخير في الفقرة. اقرأ **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | يعيد مقدار المسافة قبل السطر الأول في الفقرة. اقرأ **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | يعيد مقدار المسافة بين الأسطر الأساسية في الفقرة. اقرأ **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../../aspose.slides/itab/)\> [get_Tab](./get_tab/)(**int32_t**) | يعيد التبويب لفقرة عند الفهرس المحدد. قراءة فقط [Aspose::Slides::ITab](../../aspose.slides/itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../../aspose.slides/itabcollection/)\> [get_Tabs](./get_tabs/)() | يعيد تبويبات الفقرة. قراءة فقط [ITabCollection](../../aspose.slides/itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مُشابه لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق ما إذا كان الكائن يمثل نسخة من النوع الوصف بواسطة targetType. مماثل لمُعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مُشابه لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يتهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يتهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يتهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن بالمرجع كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../../aspose.slides/textalignment/)) | يضبط محاذاة النص في الفقرة. كتابة [TextAlignment](../../aspose.slides/textalignment/). |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | يضبط حجم التبويب الافتراضي. كتابة **float**. |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../../aspose.slides/nullablebool/)) | يحدد ما إذا كان كسر السطر شرق آسيوي يُستخدم في الفقرة. كتابة [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../../aspose.slides/fontalignment/)) | يضبط محاذاة الخط في الفقرة. كتابة [Slides::FontAlignment](../../aspose.slides/fontalignment/). |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../../aspose.slides/nullablebool/)) | يحدد ما إذا كان الترقيم المعلق يُستخدم في الفقرة. كتابة [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_Indent](./set_indent/)(**float**) | يضبط إزاحة السطر الأول/الإزاحة المتدلية للفقرة. يمكن تعريف الإزاحة المتدلية بقيم سالبة. كتابة **float**. |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../../aspose.slides/nullablebool/)) | يحدد ما إذا كان كسر السطر اللاتيني يُستخدم في الفقرة. كتابة [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | يضبط الهامش الأيسر في الفقرة. كتابة **float**. |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | يضبط الهامش الأيمن في الفقرة. كتابة **float**. |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../../aspose.slides/nullablebool/)) | يحدد ما إذا كان الكتابة من اليمين إلى اليسار يُستخدم في الفقرة. كتابة [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | يضبط مقدار المسافة بعد السطر الأخير في الفقرة. كتابة **float**. |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | يضبط مقدار المسافة قبل السطر الأول في الفقرة. كتابة **float**. |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | يضبط مقدار المسافة بين الأسطر الأساسية في الفقرة. كتابة **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي الـ n't بمؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مُشابه لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |
## راجع أيضًا

* فئة [Object](../../system/object/)
* مساحة الاسم [Aspose::Slides::Charts](../)
* مكتبة [Aspose.Slides](../../)