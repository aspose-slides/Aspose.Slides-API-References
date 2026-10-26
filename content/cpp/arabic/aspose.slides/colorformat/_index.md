---
title: ColorFormat
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يمثل لونًا يُستخدم في عرض تقديمي.
type: docs
weight: 339
url: /ar/aspose.slides/colorformat/
---
## ColorFormat فئة


يمثل اللون المستخدم في عرض تقديمي.

```cpp
class ColorFormat : public Aspose::Slides::PVIObject,
                    public Aspose::Slides::IColorFormat
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\>) override | نسخ تنسيق اللون من \"color\". |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يفحص المساواة مع الكائن المحدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام مفاهيم C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 ينص على أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 ينص على أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| **uint8_t** [get_B](./get_b/)() override | يرجع المكوّن الأزرق للون. يتم تجاهل جميع تحويلات اللون. اقرأ **uint8_t**. |
| [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() override | يرجع اللون الناتج (مع تطبيق جميع تحويلات اللون). يعين ألوان RGB ويزيل جميع تحويلات اللون. اقرأ [System::Drawing::Color](../../system.drawing/color/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) override | يرجع عملية تحويل اللون المطبقة على اللون في الفهرس المحدد. قراءة/كتابة [Aspose::Slides::IColorOperation](../icoloroperation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() override | يرجع مجموعة تحويلات اللون المطبقة على لون. قراءة فقط [IColorOperationCollection](../icoloroperationcollection/). |
| [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() override | يرجع طريقة تعريف اللون. اقرأ [Slides::ColorType](../colortype/). |
| **float** [get_FloatB](./get_floatb/)() override | يرجع المكوّن الأزرق للون. يتم تجاهل جميع تحويلات اللون. اقرأ **float**. |
| **float** [get_FloatG](./get_floatg/)() override | يرجع المكوّن الأخضر للون. يتم تجاهل جميع تحويلات اللون. اقرأ **float**. |
| **float** [get_FloatR](./get_floatr/)() override | يرجع المكوّن الأحمر للون. يتم تجاهل جميع تحويلات اللون. اقرأ **float**. |
| **uint8_t** [get_G](./get_g/)() override | يرجع المكوّن الأخضر للون. يتم تجاهل جميع تحويلات اللون. |
| **float** [get_Hue](./get_hue/)() override | يرجع مكوّن الدرجة للون في تمثيل HSL. يتم تجاهل جميع تحويلات اللون. اقرأ **float**. |
| **float** [get_Luminance](./get_luminance/)() override | يرجع مكوّن الإضاءة للون في تمثيل HSL. يتم تجاهل جميع تحويلات اللون. اقرأ **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | يرجع كائن Parent_Immediate. قراءة فقط [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | يرجع الأب [IPresentationComponent](../ipresentationcomponent/). قراءة فقط [IPresentationComponent](../ipresentationcomponent/). |
| [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() override | يرجع مجموعة الألوان المسبقة. اقرأ [Slides::PresetColor](../presetcolor/). |
| **uint8_t** [get_R](./get_r/)() override | يرجع المكوّن الأحمر للون. يتم تجاهل جميع تحويلات اللون. اقرأ **uint8_t**. |
| **float** [get_Saturation](./get_saturation/)() override | يرجع مكوّن التشبع للون في تمثيل HSL. يتم تجاهل جميع تحويلات اللون. اقرأ **float**. |
| [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() override | يرجع اللون المحدد بواسطة مخطط لون. اقرأ [Slides::SchemeColor](../schemecolor/). |
| [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() override | يرجع اللون المحدد بواسطة جدول ألوان النظام. اقرأ [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عدّاد المرجع المرتبط بالكائن. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | يرجع شفرة التجزئة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مقابل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ أي شيء فعليًا، فقط يهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| void [set_B](./set_b/)(**uint8_t**) override | يضبط المكوّن الأزرق للون. يتم تجاهل جميع تحويلات اللون. اكتب **uint8_t**. |
| void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) override | يرجع اللون الناتج (مع تطبيق جميع تحويلات اللون). يضع ألوان RGB ويزيل جميع تحويلات اللون. اكتب [System::Drawing::Color](../../system.drawing/color/). |
| void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) override | يضبط عملية تحويل اللون المطبقة على اللون في الفهرس المحدد. قراءة/كتابة [Aspose::Slides::IColorOperation](../icoloroperation/) |
| void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) override | يضبط طريقة تعريف اللون. اكتب [Slides::ColorType](../colortype/). |
| void [set_FloatB](./set_floatb/)(**float**) override | يضبط المكوّن الأزرق للون. يتم تجاهل جميع تحويلات اللون. اكتب **float**. |
| void [set_FloatG](./set_floatg/)(**float**) override | يضبط المكوّن الأخضر للون. يتم تجاهل جميع تحويلات اللون. اكتب **float**. |
| void [set_FloatR](./set_floatr/)(**float**) override | يضبط المكوّن الأحمر للون. يتم تجاهل جميع تحويلات اللون. اكتب **float**. |
| void [set_G](./set_g/)(**uint8_t**) override | يضبط المكوّن الأخضر للون. يتم تجاهل جميع تحويلات اللون. |
| void [set_Hue](./set_hue/)(**float**) override | يضبط مكوّن الدرجة للون في تمثيل HSL. يتم تجاهل جميع تحويلات اللون. اكتب **float**. |
| void [set_Luminance](./set_luminance/)(**float**) override | يضبط مكوّن الإضاءة للون في تمثيل HSL. يتم تجاهل جميع تحويلات اللون. اكتب **float**. |
| void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) override | يضبط مجموعة الألوان المسبقة. اكتب [Slides::PresetColor](../presetcolor/). |
| void [set_R](./set_r/)(**uint8_t**) override | يضبط المكوّن الأحمر للون. يتم تجاهل جميع تحويلات اللون. اكتب **uint8_t**. |
| void [set_Saturation](./set_saturation/)(**float**) override | يضبط مكوّن التشبع للون في تمثيل HSL. يتم تجاهل جميع تحويلات اللون. اكتب **float**. |
| void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) override | يضبط اللون المحدد بواسطة مخطط لون. اكتب [Slides::SchemeColor](../schemecolor/). |
| void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) override | يضبط اللون المحدد بواسطة جدول ألوان النظام. اكتب [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيطة النمطية رقم n إلى مؤشر ضعيف (بدلاً من مشترك). يتيح تبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم مؤشرات ذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عدّاد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم مؤشرات ذكية أو ThisProtector. |
| [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) override | يرجع [System::String](../../system/string/) الذي يمثل تنسيق اللون الحالي. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مقابل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم مؤشرات ذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدّاد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم مؤشرات ذكية أو ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضا

* فئة [PVIObject](../pviobject/)
* فئة [IColorFormat](../icolorformat/)
* مساحة الأسماء [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)