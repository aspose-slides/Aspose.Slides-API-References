---
title: ParagraphFormat
second_title: مرجع API الخاص بـ Aspose.Slides للـ C++
description: تحتوي هذه الفئة على خصائص تنسيق الفقرة. على عكس IParagraphFormatEffectiveData، جميع خصائص هذه الفئة قابلة للكتابة.
type: docs
weight: 4668
url: /ar/aspose.slides/paragraphformat/
---
## فئة ParagraphFormat

تحتوي هذه الفئة على خصائص تنسيق الفقرة. على عكس [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)، جميع خصائص هذه الفئة قابلة للكتابة.

```cpp
class ParagraphFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IParagraphFormat,
                        public Aspose::Slides::Charts::IChartParagraphFormat
```

## الأساليب

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يقارن مع الكائن المحدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقطة عائمة بنمط C# حيث يُعتبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقطة عائمة بنمط C# حيث يُعتبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() override | يعيد محاذاة النص في الفقرة دون وراثة. اقرأ [TextAlignment](../textalignment/). |
| **float** [get_DefaultTabSize](./get_defaulttabsize/)() override | يعيد حجم التبويب الافتراضي دون وراثة. اقرأ **float**. |
| [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() override | يحدد ما إذا كان فاصل السطر شرق آسيوي يُستخدم في الفقرة. لا يتم تطبيق وراثة. اقرأ [NullableBool](../nullablebool/). |
| [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() override | يعيد محاذاة الخط في الفقرة دون وراثة. اقرأ [Slides::FontAlignment](../fontalignment/). |
| [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() override | يحدد ما إذا كانت علامات الترقيم المتدلية تُستخدم في الفقرة. لا يتم تطبيق وراثة. اقرأ [NullableBool](../nullablebool/). |
| **float** [get_Indent](./get_indent/)() override | يعيد إزاحة السطر الأول/الإزاحة المتدلية للفقرة دون وراثة. يمكن تعريف الإزاحة المتدلية بقيم سلبية. اقرأ **float**. |
| [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() override | يحدد ما إذا كان فاصل السطر اللاتيني يُستخدم في الفقرة. لا يتم تطبيق وراثة. اقرأ [NullableBool](../nullablebool/). |
| **float** [get_MarginLeft](./get_marginleft/)() override | يعيد الهامش الأيسر في الفقرة دون وراثة. اقرأ **float**. |
| **float** [get_MarginRight](./get_marginright/)() override | يعيد الهامش الأيمن في الفقرة دون وراثة. اقرأ **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | يعيد كائن Parent_Immediate. قراءة فقط [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | يعيد الأب [IPresentationComponent](../ipresentationcomponent/). قراءة فقط [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() override | يحدد ما إذا كان الكتابة من اليمين إلى اليسار تُستخدم في الفقرة. لا يتم تطبيق وراثة. اقرأ [NullableBool](../nullablebool/). |
| **float** [get_SpaceAfter](./get_spaceafter/)() override | يعيد مقدار المسافة بعد السطر الأخير في الفقرة دون وراثة. القيمة الموجبة تحدد النسبة المئوية لحجم الخط التي يجب أن تكون عليها المسافة البيضاء. القيمة السالبة تحدد حجم المسافة البيضاء بالنقطة. اقرأ **float**. |
| **float** [get_SpaceBefore](./get_spacebefore/)() override | يعيد مقدار المسافة قبل السطر الأول في الفقرة دون وراثة. القيمة الموجبة تحدد النسبة المئوية لحجم الخط التي يجب أن تكون عليها المسافة البيضاء. القيمة السالبة تحدد حجم المسافة البيضاء بالنقطة. اقرأ **float**. |
| **float** [get_SpaceWithin](./get_spacewithin/)() override | يعيد مقدار المسافة بين الأسطر الأساسية في الفقرة. القيمة الموجبة تعني نسبة مئوية، السالبة تعني حجم بالنقاط. لا يتم تطبيق وراثة. اقرأ **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) override | يعيد التبويب للفقرة عند الفهرس المحدد. لا يتم تطبيق وراثة. قراءة فقط [Aspose::Slides::ITab](../itab/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() override | يعيد تبويبات الفقرة. لا يتم تطبيق وراثة. قراءة فقط [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() override | يحصل على بيانات تنسيق الفقرة الفعّالة مع تطبيق الوراثة. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | يعيد رمز التجزئة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. مماثل لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل بيان C# lock(). استدع مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يتهيئ كل هياكل البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يتهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| [ParagraphFormat](./paragraphformat/)() | يتهيئ نسخة جديدة من فئة [ParagraphFormat](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع قيم بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) override | يضبط محاذاة النص في الفقرة دون وراثة. اكتب [TextAlignment](../textalignment/). |
| void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) override | يضبط حجم التبويب الافتراضي دون وراثة. اكتب **float**. |
| void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) override | يحدد ما إذا كان فاصل السطر شرق آسيوي يُستخدم في الفقرة. لا يتم تطبيق وراثة. اكتب [NullableBool](../nullablebool/). |
| void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) override | يضبط محاذاة الخط في الفقرة دون وراثة. اكتب [Slides::FontAlignment](../fontalignment/). |
| void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) override | يحدد ما إذا كانت علامات الترقيم المتدلية تُستخدم في الفقرة. لا يتم تطبيق وراثة. اكتب [NullableBool](../nullablebool/). |
| void [set_Indent](./set_indent/)(**float**) override | يضبط إزاحة السطر الأول/الإزاحة المتدلية للفقرة دون وراثة. يمكن تعريف الإزاحة المتدلية بقيم سلبية. اكتب **float**. |
| void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) override | يحدد ما إذا كان فاصل السطر اللاتيني يُستخدم في الفقرة. لا يتم تطبيق وراثة. اكتب [NullableBool](../nullablebool/). |
| void [set_MarginLeft](./set_marginleft/)(**float**) override | يضبط الهامش الأيسر في الفقرة دون وراثة. اكتب **float**. |
| void [set_MarginRight](./set_marginright/)(**float**) override | يضبط الهامش الأيمن في الفقرة دون وراثة. اكتب **float**. |
| void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) override | يحدد ما إذا كان الكتابة من اليمين إلى اليسار تُستخدم في الفقرة. لا يتم تطبيق وراثة. اكتب [NullableBool](../nullablebool/). |
| void [set_SpaceAfter](./set_spaceafter/)(**float**) override | يضبط مقدار المسافة بعد السطر الأخير في الفقرة دون وراثة. القيمة الموجبة تحدد النسبة المئوية لحجم الخط التي يجب أن تكون عليها المسافة البيضاء. القيمة السالبة تحدد حجم المسافة البيضاء بالنقطة. اكتب **float**. |
| void [set_SpaceBefore](./set_spacebefore/)(**float**) override | يضبط مقدار المسافة قبل السطر الأول في الفقرة دون وراثة. القيمة الموجبة تحدد النسبة المئوية لحجم الخط التي يجب أن تكون عليها المسافة البيضاء. القيمة السالبة تحدد حجم المسافة البيضاء بالنقطة. اكتب **float**. |
| void [set_SpaceWithin](./set_spacewithin/)(**float**) override | يضبط مقدار المسافة بين الأسطر الأساسية في الفقرة. القيمة الموجبة تعني نسبة مئوية، السالبة تعني حجم بالنقاط. لا يتم تطبيق وراثة. اكتب **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل بيان C# lock(). استدع مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر كل هياكل البيانات الداخلية. |

## ملاحظات

تُستخدم هذه الفئة لإرجاع وتعديل خصائص تنسيق الفقرة المحددة للفقرة المعينة. هذا يعني أنه لا يتم تطبيق الوراثة عند الحصول على القيم، وبالتالي في معظم الحالات ستحصل على قيم تعني "غير معرف".

للحصول على قيم معلمات التنسيق الفعّالة بما في ذلك الموروثة، تحتاج إلى استخدام الطريقة [ParagraphFormat::GetEffective](./geteffective/) التي تُعيد مثالًا من نوع [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/).

## راجع أيضًا

* الفئة [PVIObject](../pviobject/)
* الفئة [IParagraphFormat](../iparagraphformat/)
* الفئة [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat/)
* مساحة الاسم [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)