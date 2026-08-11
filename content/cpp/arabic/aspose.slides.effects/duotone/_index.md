---
title: Duotone
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل تأثير Duotone. لكل بكسل، يجمع بين Color1 وColor2 من خلال استيفاء خطي لتحديد اللون الجديد لذلك البكسل.
type: docs
weight: 157
url: /ar/aspose.slides.effects/duotone/
---
## فئة Duotone

يمثّل تأثير [Duotone](./). لكل بكسل، يجمع بين Color1 وColor2 من خلال استيفاء خطي لتحديد اللون الجديد لهذا البكسل.

```cpp
class Duotone : public Aspose::Slides::Effects::ImageTransformOperation,
                public Aspose::Slides::Effects::IDuotone,
                public Aspose::Slides::Effects::IVisualEffect
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يحدد ما إذا كان [Duotone](./) المحدد يساوي [Duotone](./) الحالي. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقاط العائمة بأسلوب C# حيث يُ considered NaNانان متساويين رغم أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقاط العائمة بأسلوب C# حيث يُ considered NaNانان متساويين رغم أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_Color1](./get_color1/)() override | يعيد تنسيق اللون المستهدف للبكسلات الداكنة. للقراءة فقط [IColorFormat](../../aspose.slides/icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_Color2](./get_color2/)() override | يعيد تنسيق اللون المستهدف للبكسلات الفاتحة. للقراءة فقط [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | يعيد كائن Parent_Immediate. للقراءة فقط [IDOMObject](../../aspose.slides/idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | يعيد [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) الأصل. للقراءة فقط [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يُحصل على بنية عداد المرجع المرتبطة بالكائن. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDuotoneEffectiveData](../iduotoneeffectivedata/)\> [GetEffective](./geteffective/)() override | يُحصل على بيانات التأثير [Duotone](./) الفعّالة مع تطبيق الوراثة. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | تعمل كدالة تجزئة لنوع معين. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يُحصل على النوع الفعلي للكائن. مشابه لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل مثيلاً للنوع الموضّح بواسطة targetType. مشابه لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يمكّن من استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن المرجع لكائن نوع قيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يُحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. يجب عدم استدعائه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويُعيد عدّاد المرجع المشترك. يجب عدم استدعائه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه لطريقة C# [Object.ToString()](../../system/object/tostring/). يمكّن من تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. يجب عدم استدعائه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدّاد المرجع الضعيف. يجب عدم استدعائه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [ImageTransformOperation](../imagetransformoperation/)
* فئة [IDuotone](../iduotone/)
* فئة [IVisualEffect](../ivisualeffect/)
* نطاق [Aspose::Slides::Effects](../)
* مكتبة [Aspose.Slides](../../)