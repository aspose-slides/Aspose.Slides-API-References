---
title: Hyperlink
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل ارتباطًا تشعبيًا.
type: docs
weight: 1236
url: /ar/aspose.slides/hyperlink/
---
## فئة Hyperlink

يمثل ارتباطًا تشعبيًا.

```cpp
class Hyperlink : public Aspose::Slides::PVIObject,
                  public Aspose::Slides::IHyperlink
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يحدد ما إذا كانت المثيلات [Hyperlink](./) الاثنين متساوية. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة على نمط C# حيث يتم اعتبار NaNين متساويين رغم أنه وفقًا لـ IEC 60559:1989 لا يعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة على نمط C# حيث يتم اعتبار NaNين متساويين رغم أنه وفقًا لـ IEC 60559:1989 لا يعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [HyperlinkActionType](../hyperlinkactiontype/) [get_ActionType](./get_actiontype/)() override | يعيد نوع إجراء [Hyperlink](./). قراءة فقط [HyperlinkActionType](../hyperlinkactiontype/). |
| [HyperlinkColorSource](../hyperlinkcolorsource/) [get_ColorSource](./get_colorsource/)() override | يمثل مصدر لون الارتباط التشعبي - إما الأنماط أو تنسيق الجزء. قراءة [HyperlinkColorSource](../hyperlinkcolorsource/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_EndShow](./get_endshow/)() | يعيد ارتباطًا تشعبيًا ينهي العرض. قراءة فقط [Hyperlink](./). |
| [System::String](../../system/string/) [get_ExternalUrl](./get_externalurl/)() override | يحدد عنوان URL الخارجي. قراءة فقط [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ExternalUrlOriginal](./get_externalurloriginal/)() override | يمثل ارتباطًا تشعبيًا يتم تعيينه لهذا الجزء دون النظر إلى المحتوى الفعلي للجزء. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_FirstSlide](./get_firstslide/)() | يعيد ارتباطًا تشعبيًا إلى الشريحة الأولى من العرض التقديمي. قراءة فقط [Hyperlink](./). |
| **bool** [get_HighlightClick](./get_highlightclick/)() override | يحدد ما إذا كان يجب تمييز الارتباط التشعبي عند النقر. قراءة **bool**. |
| **bool** [get_History](./get_history/)() override | يحدد ما إذا ينبغي إضافة هدف الارتباط التشعبي الأصلي إلى قائمة الارتباطات المشاهدة عند استدعائه. قراءة **bool**. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastSlide](./get_lastslide/)() | يعيد ارتباطًا تشعبيًا إلى الشريحة الأخيرة من العرض التقديمي. قراءة فقط [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastVievedSlide](./get_lastvievedslide/)() | يعيد ارتباطًا تشعبيًا إلى الشريحة الأخيرة التي تم عرضها. قراءة فقط [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_Media](./get_media/)() | يعيد ارتباطًا تشعبيًا خاصًا \"play mediafile\". يستخدم في [AudioFrame](../audioframe/) و [VideoFrame](../videoframe/). قراءة فقط [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NextSlide](./get_nextslide/)() | يعيد ارتباطًا تشعبيًا إلى الشريحة التالية. قراءة فقط [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NoAction](./get_noaction/)() | يعيد ارتباطًا تشعبيًا خاصًا \"do nothing\". قراءة فقط [Hyperlink](./). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | يعيد الأصل [IPresentationComponent](../ipresentationcomponent/). قراءة فقط [IPresentationComponent](../ipresentationcomponent/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_PreviousSlide](./get_previousslide/)() | يعيد ارتباطًا تشعبيًا إلى الشريحة السابقة. قراءة فقط [Hyperlink](./). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() override | يمثل الصوت المشغل للارتباط التشعبي. قراءة [IAudio](../iaudio/). |
| **bool** [get_StopSoundOnClick](./get_stopsoundonclick/)() override | يحدد ما إذا يجب إيقاف الصوت عند النقر على الارتباط التشعبي. قراءة **bool**. |
| [System::String](../../system/string/) [get_TargetFrame](./get_targetframe/)() override | يعيد الإطار داخل مجموعة إطارات HTML الأصلية لهدف الارتباط التشعبي الأصلي عندما يكون موجودًا. قراءة/كتابة [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() override | إذا كان [Hyperlink](./) يستهدف شريحة محددة، يرجع هذه الشريحة. قراءة فقط [ISlide](../islide/). |
| [System::String](../../system/string/) [get_Tooltip](./get_tooltip/)() override | يعيد السلسلة التي قد تظهر في واجهة المستخدم كمرتبطة بالارتباط التشعبي الأصلي. قراءة [System::String](../../system/string/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | يعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مشابه لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
|  [Hyperlink](./hyperlink/)([System::String](../../system/string/)) | ينشئ نسخة من ارتباط تشعبي. |
|  [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) | ينشئ نسخة من ارتباط تشعبي يُشير إلى شريحة محددة. ملاحظة: يجب ربط الارتباط التشعبي المنشأ ببعض الكائنات من نفس العرض التقديمي، وإلا سيُحفظ الرابط كـ NoAction. |
|  [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\>, [System::String](../../system/string/), [System::String](../../system/string/), **bool**, **bool**, **bool**) | ينشئ نسخة من ارتباط تشعبي باستخدام ارتباط آخر كمصدر، مع تجاوز الخصائص الثانوية. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. مشابه لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعلاً، فقط يهيئ كائنًا جديدًا ويسمح بنسخ البُنى الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعلاً، فقط يهيئ كائنًا جديدًا ويسمح بنسخ البُنى الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_ColorSource](./set_colorsource/)([HyperlinkColorSource](../hyperlinkcolorsource/)) override | يمثل مصدر لون الارتباط التشعبي - إما الأنماط أو تنسيق الجزء. كتابة [HyperlinkColorSource](../hyperlinkcolorsource/). |
| void [set_HighlightClick](./set_highlightclick/)(**bool**) override | يحدد ما إذا يجب تمييز الارتباط التشعبي عند النقر. كتابة **bool**. |
| void [set_History](./set_history/)(**bool**) override | يحدد ما إذا ينبغي إضافة هدف الارتباط التشعبي الأصلي إلى قائمة الارتباطات المشاهدة عند استدعائه. كتابة **bool**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | يمثل الصوت المشغل للارتباط التشعبي. كتابة [IAudio](../iaudio/). |
| void [set_StopSoundOnClick](./set_stopsoundonclick/)(**bool**) override | يحدد ما إذا يجب إيقاف الصوت عند النقر على الارتباط التشعبي. كتابة **bool**. |
| void [set_TargetFrame](./set_targetframe/)([System::String](../../system/string/)) override | يعيد الإطار داخل مجموعة إطارات HTML الأصلية لهدف الارتباط التشعبي الأصلي عندما يكون موجودًا. قراءة/كتابة [System::String](../../system/string/). |
| void [set_Tooltip](./set_tooltip/)([System::String](../../system/string/)) override | يعيد السلسلة التي قد تظهر في واجهة المستخدم كمرتبطة بالارتباط التشعبي الأصلي. كتابة [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب ’n‘ إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتغيير المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* الفئة [PVIObject](../pviobject/)
* الفئة [IHyperlink](../ihyperlink/)
* مساحة الاسم [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)