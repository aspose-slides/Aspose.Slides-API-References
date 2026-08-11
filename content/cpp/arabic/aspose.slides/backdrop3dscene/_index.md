--- 
title: Backdrop3DScene
second_title: Aspose.Slides للـ C++ مرجع واجهة برمجة التطبيقات
description: يعرف سطحاً تُطبق فيه التأثيرات، مثل التوهج والظل، بالنسبة إلى الشكل الذي تُطبق عليه.
type: docs
weight: 92
url: /ar/aspose.slides/backdrop3dscene/
---
## Backdrop3DScene الفئة

يعرف سطراً تُطبق فيه المؤثرات، مثل التوهج والظل، بالنسبة إلى الشكل الذي تُطبّق عليها.

```cpp
class Backdrop3DScene : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IBackdrop3DScene
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يقارن مع الكائن المحدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقطية عائمة بأسلوب C# حيث يُعتَبَر NaNين متساويين رغم أن IEC 60559:1989 يوضح أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقطية عائمة بأسلوب C# حيث يُعتَبَر NaNين متساويين رغم أن IEC 60559:1989 يوضح أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_AnchorPoint](./get_anchorpoint/)() override | يرجع نقطة في الفضاء ثلاثي الأبعاد. هذه النقطة هي النقطة في الفضاء التي تثبت سطـح الخلفية. تمثَّل النقطة ثلاثية الأبعاد بمصفوفة من 3 قيم float التي تحدد إحداثيات X و Y و Z. قراءة **float**[]. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_NormalVector](./get_normalvector/)() override | يرجع متجهًا طبيعيًا. لتكون أكثر دقة، تُعرِّف هذه الخاصية متجهًا عموديًا على سطح سطـح الخلفية. يُمثَّل المتجه بمصفوفة من 3 قيم float التي تحدد إحداثيات X و Y و Z. قراءة **float**[]. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | يرجع كائن Parent_Immediate. قراءة فقط [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | يرجع الأصل [IPresentationComponent](../ipresentationcomponent/). قراءة فقط [IPresentationComponent](../ipresentationcomponent/). |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_UpVector](./get_upvector/)() override | يرجع متجهًا يمثل الاتجاه الأعلى. لتكون أكثر دقة، تُعرِّف هذه الخاصية متجهًا يمثل الاتجاه الأعلى بالنسبة إلى سطح سطـح الخلفية. يُمثَّل المتجه بمصفوفة من 3 قيم float التي تحدد إحداثيات X و Y و Z. قراءة **float**[]. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد الإشارة المرتبط بالكائن. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | يرجع رمز التجزئة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير مشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يُنفّذ عملية القفل في تعبير C# lock(). استدعِه مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشتركة بالقيمة المحددة. |
| void [set_AnchorPoint](./set_anchorpoint/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | يعين نقطة في الفضاء ثلاثي الأبعاد. هذه النقطة هي النقطة في الفضاء التي تثبت سطـح الخلفية. تمثَّل النقطة ثلاثية الأبعاد بمصفوفة من 3 قيم float التي تحدد إحداثيات X و Y و Z. كتابة **float**[]. |
| void [set_NormalVector](./set_normalvector/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | يعين متجهًا طبيعيًا. لتكون أكثر دقة، تُعرِّف هذه الخاصية متجهًا عموديًا على سطح سطـح الخلفية. يُمثَّل المتجه بمصفوفة من 3 قيم float التي تحدد إحداثيات X و Y و Z. كتابة **float**[]. |
| void [set_UpVector](./set_upvector/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | يعين متجهًا يمثل الاتجاه الأعلى. لتكون أكثر دقة، تُعرِّف هذه الخاصية متجهًا يمثل الاتجاه الأعلى بالنسبة إلى سطح سطـح الخلفية. يُمثَّل المتجه بمصفوفة من 3 قيم float التي تحدد إحداثيات X و Y و Z. كتابة **float**[]. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتغيير المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرةً؛ بدلًا من ذلك استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد الإشارة المشتركة ويعيده. لا ينبغي استدعاؤه مباشرةً؛ بدلًا من ذلك استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يُنفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يُنفّذ إلغاء قفل تعبير C# lock(). استدعِه مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرةً؛ بدلًا من ذلك استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرةً؛ بدلًا من ذلك استخدم المؤشرات الذكية أو ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |
## انظر أيضًا

* الفئة [PVIObject](../pviobject/)
* الفئة [IBackdrop3DScene](../ibackdrop3dscene/)
* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)