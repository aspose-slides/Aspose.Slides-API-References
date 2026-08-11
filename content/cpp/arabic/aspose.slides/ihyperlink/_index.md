---
title: IHyperlink
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل ارتباطًا تشعبيًا.
type: docs
weight: 2523
url: /ar/aspose.slides/ihyperlink/
---
## IHyperlink فئة


يمثل ارتباطًا تشعبيًا.

```cpp
class IHyperlink : public virtual System::Object
```

## Methods

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | تحاكي مقارنة النقطة العائمة بنمط C# حيث تُ considered NaN مزدوجة متساوية على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | تحاكي مقارنة النقطة العائمة بنمط C# حيث تُ considered NaN مزدوجة متساوية على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [HyperlinkActionType](../hyperlinkactiontype/) [get_ActionType](./get_actiontype/)() | يعيد نوع فعل HyperLinkEx. للقراءة فقط [HyperlinkActionType](../hyperlinkactiontype/). |
| virtual [HyperlinkColorSource](../hyperlinkcolorsource/) [get_ColorSource](./get_colorsource/)() | يمثل مصدر لون الارتباط التشعبي - إما الأنماط أو تنسيق الجزء. قراءة [HyperlinkColorSource](../hyperlinkcolorsource/). |
| virtual [System::String](../../system/string/) [get_ExternalUrl](./get_externalurl/)() | يحدد عنوان URL الخارجي إذا أصبحت هذه الخاصية غير فارغة ثم تصبح الخاصية TargetSlide فارغة. للقراءة فقط [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ExternalUrlOriginal](./get_externalurloriginal/)() | يمثل ارتباطًا تشعبيًا يتم تعيينه لهذا الجزء دون اعتبار لمحتوى الجزء الفعلي. |
| virtual **bool** [get_HighlightClick](./get_highlightclick/)() | يحدد ما إذا كان يجب تمييز الارتباط التشعبي عند النقر. قراءة **bool**. |
| virtual **bool** [get_History](./get_history/)() | يحدد ما إذا كان هدف الارتباط التشعبي الأصلي سيُضاف إلى قائمة الارتباطات المشاهدة عند تنفيذه. قراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() | يمثل صوت تشغيل الارتباط التشعبي. قراءة [IAudio](../iaudio/). |
| virtual **bool** [get_StopSoundOnClick](./get_stopsoundonclick/)() | يحدد ما إذا كان يجب إيقاف الصوت عند النقر على الارتباط التشعبي. قراءة **bool**. |
| virtual [System::String](../../system/string/) [get_TargetFrame](./get_targetframe/)() | يعيد الإطار داخل مجموعة إطارات HTML الأب للهدف الخاص بالارتباط التشعبي الأصلي عندما يكون موجودًا. قراءة [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() | إذا كان HyperlinkEx يستهدف شريحة محددة، يُعيد هذه الشريحة. إذا أصبحت الخاصية غير فارغة فإن الخاصية ExternalUrl تصبح فارغة. للقراءة فقط [ISlide](../islide/). |
| virtual [System::String](../../system/string/) [get_Tooltip](./get_tooltip/)() | يعيد السلسلة التي قد تُظهر في واجهة المستخدم كملحق للارتباط التشعبي الأصلي. قراءة [System::String](../../system/string/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | يُنشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا حقًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا حقًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_ColorSource](./set_colorsource/)([HyperlinkColorSource](../hyperlinkcolorsource/)) | يمثل مصدر لون الارتباط التشعبي - إما الأنماط أو تنسيق الجزء. كتابة [HyperlinkColorSource](../hyperlinkcolorsource/). |
| virtual void [set_HighlightClick](./set_highlightclick/)(**bool**) | يحدد ما إذا كان يجب تمييز الارتباط التشعبي عند النقر. كتابة **bool**. |
| virtual void [set_History](./set_history/)(**bool**) | يحدد ما إذا كان هدف الارتباط التشعبي الأصلي سيُضاف إلى قائمة الارتباطات المشاهدة عند تنفيذه. كتابة **bool**. |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | يمثل صوت تشغيل الارتباط التشعبي. كتابة [IAudio](../iaudio/). |
| virtual void [set_StopSoundOnClick](./set_stopsoundonclick/)(**bool**) | يحدد ما إذا كان يجب إيقاف الصوت عند النقر على الارتباط التشعبي. كتابة **bool**. |
| virtual void [set_TargetFrame](./set_targetframe/)([System::String](../../system/string/)) | يعيد الإطار داخل مجموعة إطارات HTML الأب للهدف الخاص بالارتباط التشعبي الأصلي عندما يكون موجودًا. كتابة [System::String](../../system/string/). |
| virtual void [set_Tooltip](./set_tooltip/)([System::String](../../system/string/)) | يعيد السلسلة التي قد تُظهر في واجهة المستخدم كملحق للارتباط التشعبي الأصلي. كتابة [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ضبط الوسيط القالب رقم n كمؤشر ضعيف (بدلاً من المشترك). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بدلًا من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بدلًا من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بدلًا من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بدلًا من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [Object](../../system/object/)
* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)