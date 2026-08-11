---
title: ColorEffect
second_title: مرجع API Aspose.Slides لـ C++
description: يمثل تأثير لون لسلوك الرسوم المتحركة.
type: docs
weight: 79
url: /ar/aspose.slides.animation/coloreffect/
---
## فئة ColorEffect

يمثل تأثير لون لسلوك الرسوم المتحركة.

```cpp
class ColorEffect : public Aspose::Slides::Animation::Behavior,
                    public Aspose::Slides::Animation::IColorEffect
```

## الأساليب

| طريقة | وصف |
| --- | --- |
|  [ColorEffect](./coloreffect/)() | ينشئ نسخة جديدة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوكيات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNين متساويين بالرغم من أن معيار IEC 60559:1989 يشير إلى أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNين متساويين بالرغم من أن معيار IEC 60559:1989 يشير إلى أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../behavior/get_accumulate/)() override | يمثل ما إذا كانت سلوكيات الرسوم المتحركة متراكمة. اقرأ [NullableBool](../../aspose.slides/nullablebool/). |
| [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../behavior/get_additive/)() override | يمثل ما إذا كان سلوك الرسوم المتحركة الحالي مدمجًا مع رسوم متحركة أخرى قيد التشغيل. اقرأ [BehaviorAdditiveType](../behavioradditivetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOffset](../icoloroffset/)\> [get_By](./get_by/)() override | يوصف قيمة الإزاحة النسبية لتأثير اللون. اقرأ [IColorOffset](../icoloroffset/). |
| [Aspose::Slides::Animation::ColorSpace](../colorspace/) [get_ColorSpace](./get_colorspace/)() override | يمثل مساحة اللون للسلوك. اقرأ [Animation::ColorSpace](../colorspace/). |
| [ColorDirection](../colordirection/) [get_Direction](./get_direction/)() override | يحدد الاتجاه الذي يُدور فيه الصبغ حول عجلة اللون. اقرأ [ColorDirection](../colordirection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_From](./get_from/)() override | يُستخدم هذا القيمة لتحديد اللون الابتدائي للسلوك. اقرأ [IColorFormat](../../aspose.slides/icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../behavior/get_properties/)() override | يمثل خصائص السلوك. قراءة فقط [IBehaviorPropertyCollection](../ibehaviorpropertycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../behavior/get_timing/)() override | يمثل خصائص التوقيت لسلوك التأثير. اقرأ [ITiming](../itiming/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_To](./get_to/)() override | يوصف اللون الناتج لتغيير لون الرسوم المتحركة. اقرأ [IColorFormat](../../aspose.slides/icolorformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نسخة مماثلة لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نسخة مماثلة لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نسخة مماثلة لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نسخة مماثلة لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، فقط يهيء كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيء كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Accumulate](../behavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) override | يمثل ما إذا كانت سلوكيات الرسوم المتحركة متراكمة. اكتب [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_Additive](../behavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) override | يمثل ما إذا كان سلوك الرسوم المتحركة الحالي مدمجًا مع رسوم متحركة أخرى قيد التشغيل. اكتب [BehaviorAdditiveType](../behavioradditivetype/). |
| void [set_By](./set_by/)([System::SharedPtr](../../system/sharedptr/)\<[IColorOffset](../icoloroffset/)\>) override | يوصف قيمة الإزاحة النسبية لتأثير اللون. اكتب [IColorOffset](../icoloroffset/). |
| void [set_ColorSpace](./set_colorspace/)([Aspose::Slides::Animation::ColorSpace](../colorspace/)) override | يمثل مساحة اللون للسلوك. اكتب [Animation::ColorSpace](../colorspace/). |
| void [set_Direction](./set_direction/)([ColorDirection](../colordirection/)) override | يحدد الاتجاه الذي يُدور فيه الصبغ حول عجلة اللون. اكتب [ColorDirection](../colordirection/). |
| void [set_From](./set_from/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\>) override | يُستخدم هذا القيمة لتحديد اللون الابتدائي للسلوك. اكتب [IColorFormat](../../aspose.slides/icolorformat/). |
| void [set_Timing](../behavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | يمثل خصائص التوقيت لسلوك التأثير. اكتب [ITiming](../itiming/). |
| void [set_To](./set_to/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\>) override | يوصف اللون الناتج لتغيير لون الرسوم المتحركة. اكتب [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط وسيط القالب رقم n كإشارة ضعيفة (بدلاً من المشتركة). يتيح تحويل الإشارات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نسخة مماثلة لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## أنظر أيضًا

* فئة [Behavior](../behavior/)
* فئة [IColorEffect](../icoloreffect/)
* نطاق [Aspose::Slides::Animation](../)
* مكتبة [Aspose.Slides](../../)