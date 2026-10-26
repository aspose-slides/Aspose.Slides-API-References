---
title: OuterShadow
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل تأثير الظل الخارجي.
type: docs
weight: 1041
url: /ar/aspose.slides.effects/outershadow/
---
## OuterShadow الصنف


يمثل تأثير الظل الخارجي.

```cpp
class OuterShadow : public Aspose::Slides::Effects::IOuterShadow,
                    public Aspose::Slides::Effects::IVisualEffect,
                    public Aspose::Slides::IPVIObject
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يحدد ما إذا كان [OuterShadow](./) المحدد مساويًا للـ [OuterShadow](./) الحالي. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي على طراز C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقوم بمحاكاة مقارنة الأعداد العائمة على طراز C# حيث تُعامل قيمتي NaN على أنهما متساويتان بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقوم بمحاكاة مقارنة الأعداد العائمة على طراز C# حيث تُعامل قيمتي NaN على أنهما متساويتان بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) نصف القطر، بوحدات النقاط. القيمة الافتراضية – 0 نقطة. قراءة **double**. |
| **float** [get_Direction](./get_direction/)() override | اتجاه الظل، بالدرجات. القيمة الافتراضية – 0° (من اليسار إلى اليمين). قراءة **float**. |
| **double** [get_Distance](./get_distance/)() override | مسافة الظل من الكائن، بوحدات النقاط. القيمة الافتراضية – 0 نقطة. قراءة **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | يعيد العنصر الأعلى [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). للقراءة فقط [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | محاذاة المستطيل. القيمة الافتراضية – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). قراءة [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | يشير إلى ما إذا كان الظل يدور مع الشكل. القيمة الافتراضية – true. قراءة **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | عامل التحجيم الأفقي، كنسبة مئوية من الحجم الأصلي. التحجيم السالب يسبب انعكاسًا. القيمة الافتراضية – 100٪. قراءة **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | عامل التحجيم العمودي، كنسبة مئوية من الحجم الأصلي. التحجيم السالب يسبب انعكاسًا. القيمة الافتراضية – 100٪. قراءة **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() override | لون الظل. القيمة الافتراضية – أسود تلقائي (يعتمد على السمة). للقراءة فقط [IColorFormat](../../aspose.slides/icolorformat/). |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | زاوية الانحراف الأفقي، بالدرجات. القيمة الافتراضية – 0°. قراءة **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | زاوية الانحراف العمودي، بالدرجات. القيمة الافتراضية – 0°. قراءة **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | الإصدار. للقراءة فقط **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يسترجع بنية بيانات عدّاد المرجع المرتبط بالكائن. |
| [System::SharedPtr](../../system/sharedptr/)\<[IOuterShadowEffectiveData](../ioutershadoweffectivedata/)\> [GetEffective](./geteffective/)() override | يسترجع بيانات تأثير الظل الخارجي الفعلي مع تطبيق الوراثة. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | يعمل كدالة تجزئة لنوع معين. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يسترجع النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يطبق قفل عبارة C# lock(). يستدعى مباشرة أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) نصف القطر، بوحدات النقاط. القيمة الافتراضية – 0 نقطة. كتابة **double**. |
| void [set_Direction](./set_direction/)(**float**) override | اتجاه الظل، بالدرجات. القيمة الافتراضية – 0° (من اليسار إلى اليمين). كتابة **float**. |
| void [set_Distance](./set_distance/)(**double**) override | مسافة الظل من الكائن، بوحدات النقاط. القيمة الافتراضية – 0 نقطة. كتابة **double**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | محاذاة المستطيل. القيمة الافتراضية – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). كتابة [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | يشير إلى ما إذا كان الظل يدور مع الشكل. القيمة الافتراضية – true. كتابة **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | عامل التحجيم الأفقي، كنسبة مئوية من الحجم الأصلي. التحجيم السالب يسبب انعكاسًا. القيمة الافتراضية – 100٪. كتابة **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | عامل التحجيم العمودي، كنسبة مئوية من الحجم الأصلي. التحجيم السالب يسبب انعكاسًا. القيمة الافتراضية – 100٪. كتابة **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | زاوية الانحراف الأفقي، بالدرجات. القيمة الافتراضية – 0°. كتابة **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | زاوية الانحراف العمودي، بالدرجات. القيمة الافتراضية – 0°. كتابة **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط وسيط القالب رقم n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يسترجع القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص عدّاد المرجع المشترك ويعيده. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). يستدعى مباشرة أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* الصنف [IOuterShadow](../ioutershadow/)
* الصنف [IVisualEffect](../ivisualeffect/)
* الصنف [IPVIObject](../../aspose.slides/ipviobject/)
* النطاق [Aspose::Slides::Effects](../)
* المكتبة [Aspose.Slides](../../)