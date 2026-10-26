---
title: IColorFormat
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل لونًا يُستخدم في العرض التقديمي.
type: docs
weight: 1691
url: /ar/aspose.slides/icolorformat/
---
## IColorFormat فئة

يمثل لونًا يُستخدم في العرض التقديمي.

```cpp
class IColorFormat : public Aspose::Slides::IFillParamSource
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](./)\>) | نسخ تنسيق اللون من \"color\". |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوكيات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتَبر NaNانين متساويين رغم أن IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتَبر NaNانين متساويين رغم أن IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual **uint8_t** [get_B](./get_b/)() | يُعيد مكوّن اللون الأزرق. تُهمل جميع تحويلات اللون. اقرأ **uint8_t**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() | يُعيد اللون الناتج (مع تطبيق جميع تحويلات اللون). يضبط ألوان RGB ويزيل جميع تحويلات اللون. اقرأ [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) | يُعيد عملية تحويل اللون المطبقة على اللون في الفهرس المحدد. قراءة/كتابة [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() | يُعيد مجموعة تحويلات اللون المطبقة على لون. قراءة فقط [IColorOperationCollection](../icoloroperationcollection/). |
| virtual [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() | يُعيد طريقة تعريف اللون. قراءة [Slides::ColorType](../colortype/). |
| virtual **float** [get_FloatB](./get_floatb/)() | يُعيد مكوّن اللون الأزرق. تُهمل جميع تحويلات اللون. اقرأ **float**. |
| virtual **float** [get_FloatG](./get_floatg/)() | يُعيد مكوّن اللون الأخضر. تُهمل جميع تحويلات اللون. اقرأ **float**. |
| virtual **float** [get_FloatR](./get_floatr/)() | يُعيد مكوّن اللون الأحمر. تُهمل جميع تحويلات اللون. اقرأ **float**. |
| virtual **uint8_t** [get_G](./get_g/)() | يُعيد مكوّن اللون الأخضر. تُهمل جميع تحويلات اللون. اقرأ **uint8_t**. |
| virtual **float** [get_Hue](./get_hue/)() | يُعيد مكوّن الصبغة للون في تمثيل HSL. تُهمل جميع تحويلات اللون. اقرأ **float**. |
| virtual **float** [get_Luminance](./get_luminance/)() | يُعيد مكوّن الإضاءة للون في تمثيل HSL. تُهمل جميع تحويلات اللون. اقرأ **float**. |
| virtual [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() | يُعيد إعداد اللون المسبق. اقرأ [Slides::PresetColor](../presetcolor/). |
| virtual **uint8_t** [get_R](./get_r/)() | يُعيد مكوّن اللون الأحمر. تُهمل جميع تحويلات اللون. اقرأ **uint8_t**. |
| virtual **float** [get_Saturation](./get_saturation/)() | يُعيد مكوّن التشبع للون في تمثيل HSL. تُهمل جميع تحويلات اللون. اقرأ **float**. |
| virtual [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() | يُعيد اللون المحدد بواسطة مخطط ألوان. اقرأ [Slides::SchemeColor](../schemecolor/). |
| virtual [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() | يُعيد اللون المحدد بواسطة جدول ألوان النظام. اقرأ [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مشابه لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مشابه لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. مشابه لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يطبق تعليمة C# lock() لتأمين. استدعِ مباشرة أو استخدم كائن المراقبة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_B](./set_b/)(**uint8_t**) | يضبط مكوّن اللون الأزرق. تُهمل جميع تحويلات اللون. كتابة **uint8_t**. |
| virtual void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) | يُعيد اللون الناتج (مع تطبيق جميع تحويلات اللون). يضبط ألوان RGB ويزيل جميع تحويلات اللون. كتابة [System::Drawing::Color](../../system.drawing/color/). |
| virtual void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) | يضبط عملية تحويل اللون المطبقة على اللون في الفهرس المحدد. قراءة/كتابة [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) | يضبط طريقة تعريف اللون. كتابة [Slides::ColorType](../colortype/). |
| virtual void [set_FloatB](./set_floatb/)(**float**) | يضبط مكوّن اللون الأزرق. تُهمل جميع تحويلات اللون. كتابة **float**. |
| virtual void [set_FloatG](./set_floatg/)(**float**) | يضبط مكوّن اللون الأخضر. تُهمل جميع تحويلات اللون. كتابة **float**. |
| virtual void [set_FloatR](./set_floatr/)(**float**) | يضبط مكوّن اللون الأحمر. تُهمل جميع تحويلات اللون. كتابة **float**. |
| virtual void [set_G](./set_g/)(**uint8_t**) | يضبط مكوّن اللون الأخضر. تُهمل جميع تحويلات اللون. كتابة **uint8_t**. |
| virtual void [set_Hue](./set_hue/)(**float**) | يضبط مكوّن الصبغة للون في تمثيل HSL. تُهمل جميع تحويلات اللون. كتابة **float**. |
| virtual void [set_Luminance](./set_luminance/)(**float**) | يضبط مكوّن الإضاءة للون في تمثيل HSL. تُهمل جميع تحويلات اللون. كتابة **float**. |
| virtual void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) | يضبط إعداد اللون المسبق. كتابة [Slides::PresetColor](../presetcolor/). |
| virtual void [set_R](./set_r/)(**uint8_t**) | يضبط مكوّن اللون الأحمر. تُهمل جميع تحويلات اللون. كتابة **uint8_t**. |
| virtual void [set_Saturation](./set_saturation/)(**float**) | يضبط مكوّن التشبع للون في تمثيل HSL. تُهمل جميع تحويلات اللون. كتابة **float**. |
| virtual void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) | يضبط اللون المحدد بواسطة مخطط ألوان. كتابة [Slides::SchemeColor](../schemecolor/). |
| virtual void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) | يضبط اللون المحدد بواسطة جدول ألوان النظام. كتابة [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزداد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) | يُعيد [System::String](../../system/string/) الذي يمثل تنسيق اللون الحالي. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة نصية. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق تعليمة C# lock() لإلغاء القفل. استدعِ مباشرة أو استخدم كائن المراقبة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* Class [IFillParamSource](../ifillparamsource/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)