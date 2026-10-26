---
title: IOuterShadow
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل تأثير الظل الخارجي.
type: docs
weight: 885
url: /ar/aspose.slides.effects/ioutershadow/
---
## IOuterShadow فئة

يمثل تأثير الظل الخارجي.

```cpp
class IOuterShadow : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                     public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IOuterShadowEffectiveData>>
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين على الرغم من أنه وفقًا لـ IEC 60559:1989 لا يعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين على الرغم من أنه وفقًا لـ IEC 60559:1989 لا يعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) نصف القطر، بالنقاط. القيمة الافتراضية – 0 pt. قراءة **double**. |
| virtual **float** [get_Direction](./get_direction/)() | اتجاه الظل، بالدرجات. القيمة الافتراضية – 0 ° (من اليسار إلى اليمين). قراءة **float**. |
| virtual **double** [get_Distance](./get_distance/)() | مسافة الظل عن الكائن، بالنقاط. القيمة الافتراضية – 0 pt. قراءة **double**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | محاذاة المستطيل. القيمة الافتراضية – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). قراءة [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | يشير إلى ما إذا كان الظل يدور مع الشكل. القيمة الافتراضية – true. قراءة **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | عامل التحجيم الأفقي، كنسبة مئوية من الحجم الأصلي. يؤدي التحجيم السلبي إلى انعكاس. القيمة الافتراضية – 100 %. قراءة **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | عامل التحجيم العمودي، كنسبة مئوية من الحجم الأصلي. يؤدي التحجيم السلبي إلى انعكاس. القيمة الافتراضية – 100 %. قراءة **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() | لون الظل. القيمة الافتراضية – أسود تلقائي (يعتمد على السمة). قراءة فقط [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | زاوية الانحراف الأفقي، بالدرجات. القيمة الافتراضية – 0 °. قراءة **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | زاوية الانحراف العمودي، بالدرجات. القيمة الافتراضية – 0 °. قراءة **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | يحصل على البيانات الفعّالة مع تطبيق الوراثة. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تماثل معامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | تنفّذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد المراجع المشتركة بالقيمة المحددة. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) نصف القطر، بالنقاط. القيمة الافتراضية – 0 pt. كتابة **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | اتجاه الظل، بالدرجات. القيمة الافتراضية – 0 ° (من اليسار إلى اليمين). كتابة **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | مسافة الظل عن الكائن، بالنقاط. القيمة الافتراضية – 0 pt. كتابة **double**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | محاذاة المستطيل. القيمة الافتراضية – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). كتابة [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | يشير إلى ما إذا كان الظل يدور مع الشكل. القيمة الافتراضية – true. كتابة **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | عامل التحجيم الأفقي، كنسبة مئوية من الحجم الأصلي. يؤدي التحجيم السلبي إلى انعكاس. القيمة الافتراضية – 100 %. كتابة **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | عامل التحجيم العمودي، كنسبة مئوية من الحجم الأصلي. يؤدي التحجيم السلبي إلى انعكاس. القيمة الافتراضية – 100 %. كتابة **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | زاوية الانحراف الأفقي، بالدرجات. القيمة الافتراضية – 0 °. كتابة **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | زاوية الانحراف العمودي، بالدرجات. القيمة الافتراضية – 0 °. كتابة **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط n في القالب إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عدد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | تنفّذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |
## انظر أيضاً

* فئة [IImageTransformOperation](../iimagetransformoperation/)
* فئة [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* مساحة الاسم [Aspose::Slides::Effects](../)
* مكتبة [Aspose.Slides](../../)