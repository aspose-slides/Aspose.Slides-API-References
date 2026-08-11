---
title: IColorChange
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل تأثير تغيير اللون. يتم استبدال كائنات FromColor بكائنات ToColor.
type: docs
weight: 508
url: /ar/aspose.slides.effects/icolorchange/
---
## IColorChange الفئة

Represents a Color Change effect. Instances of FromColor are replaced with instances of ToColor.

```cpp
class IColorChange : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                     public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IColorChangeEffectiveData>>
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سياق C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع مرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة الأعداد العائمة بأسلوب C# حيث تُعتبر NaN مزدوجة متساوية رغم أن وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة الأعداد العائمة بأسلوب C# حيث تُعتبر NaN مزدوجة متساوية رغم أن وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_FromColor](./get_fromcolor/)() | اللون الذي سيستبدل. قراءة فقط [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ToColor](./get_tocolor/)() | اللون الذي سيستبدل. قراءة فقط [IColorFormat](../../aspose.slides/icolorformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عدّاد المرجع المرتبط بالكائن. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | يحصل على البيانات الفعّالة مع تطبيق الوراثة. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يمكّن تجزئة الكائنات المخصّصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. مماثل لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل بيان C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يمكّن استنساخ الأنواع المخصّصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّء جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، بل يهيّء كائنًا جديدًا ويُمكّن من نسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيّء كائنًا جديدًا ويُمكّن من نسخ بناء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن النوع القيمي بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلّل عدّاد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | عيّن الوسيط القالبي النوني مؤشرًا ضعيفًا (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلّص ويعيد عدّاد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يمكّن تحويل الكائنات المخصّصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل بيان C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلّص عدّاد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [IImageTransformOperation](../iimagetransformoperation/)
* الفئة [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* النطاق [Aspose::Slides::Effects](../)
* المكتبة [Aspose.Slides](../../)