---
title: Reflection
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: يمثل تأثير انعكاس.
type: docs
weight: 1067
url: /ar/aspose.slides.effects/reflection/
---
## فئة Reflection

يمثل تأثير [Reflection](./).

```cpp
class Reflection : public Aspose::Slides::Effects::IReflection,
                   public Aspose::Slides::Effects::IVisualEffect,
                   public Aspose::Slides::IPVIObject
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يحدد ما إذا كان [Reflection](./) المحدد يساوي [Reflection](./) الحالي. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي على نمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث تُعتبر NaNين متساويتين على الرغم من أن IEC 60559:1989 تقول إن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث تُعتبر NaNين متساويتين على الرغم من أن IEC 60559:1989 تقول إن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) نصف القطر. قراءة **double**. |
| **float** [get_Direction](./get_direction/)() override | اتجاه الانعكاس. قراءة **float**. |
| **double** [get_Distance](./get_distance/)() override | مسافة الانعكاس. قراءة **double**. |
| **float** [get_EndPosAlpha](./get_endposalpha/)() override | يحدد الموضع النهائي (على امتداد منحدر تدرج ألفا) لقيمة ألفا النهائية (النسب المئوية). قراءة **float**. |
| **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() override | العتمة النهائية للانعكاس. (النسب المئوية). قراءة **float**. |
| **float** [get_FadeDirection](./get_fadedirection/)() override | يحدد اتجاه الإزاحة للانعكاس. (زاوية). قراءة **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | يرجع العنصر الأب [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) للقراءة فقط. |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | محاذاة المستطيل. قراءة [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | يحدد ما إذا كان يجب أن يدور الانعكاس مع الشكل إذا تم تدوير الشكل. قراءة **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | يحدد معامل التدرج الأفقي، حيث يسبب التدرج السلبي انعكاسًا. (النسب المئوية) قراءة **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | يحدد معامل التدرج العمودي، حيث يسبب التدرج السلبي انعكاسًا. (النسب المئوية) قراءة **double**. |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | يحدد زاوية الانحراف الأفقي. قراءة **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | يحدد زاوية الانحراف العمودي. قراءة **double**. |
| **float** [get_StartPosAlpha](./get_startposalpha/)() override | يحدد الموضع الابتدائي (على امتداد منحدر تدرج ألفا) لقيمة ألفا الابتدائية (النسب المئوية). قراءة **float**. |
| **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() override | العتمة الابتدائية للانعكاس. (النسب المئوية). قراءة **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | الإصدار. **uint32_t** للقراءة فقط. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| [System::SharedPtr](../../system/sharedptr/)\<[IReflectionEffectiveData](../ireflectioneffectivedata/)\> [GetEffective](./geteffective/)() override | يحصل على بيانات تأثير [Reflection](./) الفعّالة مع تطبيق الوراثة. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | يعمل كدالة تجزئة لنوع معين. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يمكّن استنساخ الأنواع المخصّصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، فقط يهيّء كائنًا جديدًا ويمكّن بناء نسخ الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | معامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيّء كائنًا جديدًا ويمكّن بناء نسخ الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائنًا من نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) نصف القطر. كتابة **double**. |
| void [set_Direction](./set_direction/)(**float**) override | اتجاه الانعكاس. كتابة **float**. |
| void [set_Distance](./set_distance/)(**double**) override | مسافة الانعكاس. كتابة **double**. |
| void [set_EndPosAlpha](./set_endposalpha/)(**float**) override | يحدد الموضع النهائي (على امتداد منحدر تدرج ألفا) لقيمة ألفا النهائية (النسب المئوية). كتابة **float**. |
| void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) override | العتمة النهائية للانعكاس. (النسب المئوية). كتابة **float**. |
| void [set_FadeDirection](./set_fadedirection/)(**float**) override | يحدد اتجاه إزاحة الانعكاس. (زاوية). كتابة **float**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | محاذاة المستطيل. كتابة [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | يحدد ما إذا كان يجب أن يدور الانعكاس مع الشكل إذا تم تدوير الشكل. كتابة **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | يحدد معامل التدرج الأفقي، حيث يسبب التدرج السلبي انعكاسًا. (النسب المئوية) كتابة **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | يحدد معامل التدرج العمودي، حيث يسبب التدرج السلبي انعكاسًا. (النسب المئوية) كتابة **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | يحدد زاوية الانحراف الأفقي. كتابة **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | يحدد زاوية الانحراف العمودي. كتابة **double**. |
| void [set_StartPosAlpha](./set_startposalpha/)(**float**) override | يحدد الموضع الابتدائي (على امتداد منحدر تدرج ألفا) لقيمة ألفا الابتدائية (النسب المئوية). كتابة **float**. |
| void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) override | العتمة الابتدائية للانعكاس. (النسب المئوية). كتابة **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي nth إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عدّاد المرجع المشترك ويعيده. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يمكّن تحويل الكائنات المخصّصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ فك قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* الفئة [IReflection](../ireflection/)
* الفئة [IVisualEffect](../ivisualeffect/)
* الفئة [IPVIObject](../../aspose.slides/ipviobject/)
* مساحة الاسم [Aspose::Slides::Effects](../)
* المكتبة [Aspose.Slides](../../)