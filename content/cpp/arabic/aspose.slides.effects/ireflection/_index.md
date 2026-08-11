---
title: IReflection
second_title: مرجع API Aspose.Slides لـ C++
description: يمثل تأثير الانعكاس.
type: docs
weight: 937
url: /ar/aspose.slides.effects/ireflection/
---
## IReflection فئة

يمثل تأثير الانعكاس.

```cpp
class IReflection : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                    public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IReflectionEffectiveData>>
```

## الدوال

| طريقة | وصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNان اثنان متساويين على الرغم من أنه وفقًا لـ IEC 60559:1989 لا يُساوي NaN أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNان اثنان متساويين على الرغم من أنه وفقًا لـ IEC 60559:1989 لا يُساوي NaN أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) نصف القطر. قراءة **double**. |
| virtual **float** [get_Direction](./get_direction/)() | اتجاه الانعكاس. قراءة **float**. |
| virtual **double** [get_Distance](./get_distance/)() | مسافة الانعكاس. قراءة **double**. |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | يحدد موضع النهاية (على طول منحدر تدريج ألفا) لقيمة ألفا النهاية (النسب المئوية). قراءة **float**. |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | شفافية الانعكاس النهائية. (النسب المئوية). قراءة **float**. |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | يحدد اتجاه إزاحة الانعكاس. (زاوية). قراءة **float**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | محاذاة المستطيل. قراءة [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | يحدد ما إذا كان يجب أن يدور الانعكاس مع الشكل إذا تم تدوير الشكل. قراءة **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | يحدد عامل التحجيم الأفقي، التحجيم السالب يسبب انعكاسًا. (النسب المئوية) قراءة **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | يحدد عامل التحجيم الرأسي، التحجيم السالب يسبب انعكاسًا. (النسب المئوية) قراءة **double**. |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | يحدد زاوية الانحراف الأفقي. قراءة **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | يحدد زاوية الانحراف الرأسي. قراءة **double**. |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | يحدد موضع البداية (على طول منحدر تدريج ألفا) لقيمة ألفا البداية (النسب المئوية). قراءة **float**. |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | شفافية الانعكاس الابتدائية. (النسب المئوية). قراءة **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبطة بالكائن. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | يحصل على البيانات الفعالة مع تطبيق الوراثة. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير مشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) نصف القطر. كتابة **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | اتجاه الانعكاس. كتابة **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | مسافة الانعكاس. كتابة **double**. |
| virtual void [set_EndPosAlpha](./set_endposalpha/)(**float**) | يحدد موضع النهاية (على طول منحدر تدريج ألفا) لقيمة ألفا النهاية (النسب المئوية). كتابة **float**. |
| virtual void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) | شفافية الانعكاس النهائية. (النسب المئوية). كتابة **float**. |
| virtual void [set_FadeDirection](./set_fadedirection/)(**float**) | يحدد اتجاه إزاحة الانعكاس. (زاوية). كتابة **float**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | محاذاة المستطيل. كتابة [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | يحدد ما إذا كان يجب أن يدور الانعكاس مع الشكل إذا تم تدوير الشكل. كتابة **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | يحدد عامل التحجيم الأفقي، التحجيم السالب يسبب انعكاسًا. (النسب المئوية) كتابة **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | يحدد عامل التحجيم الرأسي، التحجيم السالب يسبب انعكاسًا. (النسب المئوية) كتابة **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | يحدد زاوية الانحراف الأفقي. كتابة **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | يحدد زاوية الانحراف الرأسي. كتابة **double**. |
| virtual void [set_StartPosAlpha](./set_startposalpha/)(**float**) | يحدد موضع البداية (على طول منحدر تدريج ألفا) لقيمة ألفا البداية (النسب المئوية). كتابة **float**. |
| virtual void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) | شفافية الانعكاس الابتدائية. (النسب المئوية). كتابة **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط معامل القالب رقم n على مؤشر ضعيف (بدلاً من مشترك). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا يجب استدعاؤه مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يُحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [IImageTransformOperation](../iimagetransformoperation/)
* فئة [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* مساحة الاسم [Aspose::Slides::Effects](../)
* مكتبة [Aspose.Slides](../../)