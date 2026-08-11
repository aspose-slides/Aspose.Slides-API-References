---
title: FilterEffect
second_title: Aspose.Slides لمرجع API للغة C++
description: يمثل تأثير الفلتر للسلوك.
type: docs
weight: 131
url: /ar/aspose.slides.animation/filtereffect/
---
## فئة FilterEffect

يمثل تأثير الفلتر للسلوك.

```cpp
class FilterEffect : public Aspose::Slides::Animation::Behavior,
                     public Aspose::Slides::Animation::IFilterEffect
```

## الأساليب

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | محاكاة مقارنة نقطية عائمة على نمط C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | محاكاة مقارنة نقطية عائمة على نمط C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
|  [FilterEffect](./filtereffect/)() | منشئ افتراضي. |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../behavior/get_accumulate/)() override | يمثل ما إذا كانت سلوكيات الرسوم المتحركة مُجمّعة. قراءة [NullableBool](../../aspose.slides/nullablebool/). |
| [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../behavior/get_additive/)() override | يمثل ما إذا تم دمج سلوك الرسوم المتحركة الحالي مع رسوم متحركة أخرى جارية. قراءة [BehaviorAdditiveType](../behavioradditivetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../behavior/get_properties/)() override | يمثل خصائص السلوك. قراءة فقط [IBehaviorPropertyCollection](../ibehaviorpropertycollection/). |
| [FilterEffectRevealType](../filtereffectrevealtype/) [get_Reveal](./get_reveal/)() override | يمثل أن التأثير مع السلوك يجب أن يكشف (داخل/خارج) قراءة [FilterEffectRevealType](../filtereffectrevealtype/). |
| [FilterEffectSubtype](../filtereffectsubtype/) [get_Subtype](./get_subtype/)() override | يمثل النوع الفرعي لتأثير الفلتر. قراءة [FilterEffectSubtype](../filtereffectsubtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../behavior/get_timing/)() override | يمثل خصائص التوقيت لسلوك التأثير. قراءة [ITiming](../itiming/). |
| [FilterEffectType](../filtereffecttype/) [get_Type](./get_type/)() override | يمثل نوع تأثير الفلتر. قراءة [FilterEffectType](../filtereffecttype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عدّاد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلاً للنوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | تنفيذ قفل جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| void [set_Accumulate](../behavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) override | يمثل ما إذا كانت سلوكيات الرسوم المتحركة مُجمّعة. كتابة [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_Additive](../behavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) override | يمثل ما إذا تم دمج سلوك الرسوم المتحركة الحالي مع رسوم متحركة أخرى جارية. كتابة [BehaviorAdditiveType](../behavioradditivetype/). |
| void [set_Reveal](./set_reveal/)([FilterEffectRevealType](../filtereffectrevealtype/)) override | يمثل أن التأثير مع السلوك يجب أن يكشف (داخل/خارج) كتابة [FilterEffectRevealType](../filtereffectrevealtype/). |
| void [set_Subtype](./set_subtype/)([FilterEffectSubtype](../filtereffectsubtype/)) override | يمثل النوع الفرعي لتأثير الفلتر. كتابة [FilterEffectSubtype](../filtereffectsubtype/). |
| void [set_Timing](../behavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | يمثل خصائص التوقيت لسلوك التأثير. كتابة [ITiming](../itiming/). |
| void [set_Type](./set_type/)([FilterEffectType](../filtereffecttype/)) override | يمثل نوع تأثير الفلتر. كتابة [FilterEffectType](../filtereffecttype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كـ weak pointer (بدلاً من shared). يتيح تبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعدّاد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عدّاد المرجع المشترك ويعيده. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | تنفيذ إلغاء قفل جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [Behavior](../behavior/)
* فئة [IFilterEffect](../ifiltereffect/)
* مساحة الاسم [Aspose::Slides::Animation](../)
* مكتبة [Aspose.Slides](../../)