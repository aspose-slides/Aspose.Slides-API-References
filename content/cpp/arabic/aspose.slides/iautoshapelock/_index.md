---
title: IAutoShapeLock
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحدد أي العمليات تم تعطيلها على الكائن AutoshapeEx الأب.
type: docs
weight: 1379
url: /ar/aspose.slides/iautoshapelock/
---
## IAutoShapeLock فئة

يحدّد أي العمليات مُعطَّلة على كائن AutoshapeEx الأب.

```cpp
class IAutoShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانين متساويين رغم أنه وفقًا لـ IEC 60559:1989 لا يُعد NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانين متساويين رغم أنه وفقًا لـ IEC 60559:1989 لا يُعد NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | يحدِّد ما إذا كان تغيير قيم الضبط محظورًا. يقرأ **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | يحدِّد ما إذا كان تغيير رؤوس السهام محظورًا. يقرأ **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | يحدِّد ما إذا كان يجب على الشكل الحفاظ على نسبة العرض إلى الارتفاع عند إعادة الحجم. يقرأ **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | يحدِّد ما إذا كان تغيير الحدود المباشر لهذا الشكل محظورًا. يقرأ **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | يحدِّد ما إذا كان إضافة هذا الشكل إلى مجموعة محظورًا. يقرأ **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | يرجع true إذا تم تعطيل جميع أعلام القفل. **bool** للقراءة فقط. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | يحدِّد ما إذا كان نقل هذا الشكل محظورًا. يقرأ **bool**. |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | يحدِّد ما إذا كان تغيير زاوية الدوران لهذا الشكل محظورًا. يقرأ **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | يحدِّد ما إذا كان اختيار هذا الشكل محظورًا. يقرأ **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | يحدِّد ما إذا كان تغيير نوع الشكل محظورًا. يقرأ **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | يحدِّد ما إذا كان تغيير حجم هذا الشكل محظورًا. يقرأ **bool**. |
| virtual **bool** [get_TextLocked](./get_textlocked/)() | يحدِّد ما إذا كان تعديل النص محظورًا. يقرأ **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد الإشارة المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يُتيح تجزئة الكائنات المخصَّصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | تنفّذ قفل تعبير C# lock(). استدعٍ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يُتيح استنساخ الأنواع المخصَّصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعلًا، بل يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعلًا، بل يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن بالمرجع كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يُقلِّل عداد الإشارة المشتركة بالقيمة المحددة. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | يحدِّد ما إذا كان تغيير قيم الضبط محظورًا. يكتب **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | يحدِّد ما إذا كان تغيير رؤوس السهام محظورًا. يكتب **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | يحدِّد ما إذا كان يجب على الشكل الحفاظ على نسبة العرض إلى الارتفاع عند إعادة الحجم. يكتب **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | يحدِّد ما إذا كان تغيير الحدود المباشر لهذا الشكل محظورًا. يكتب **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | يحدِّد ما إذا كان إضافة هذا الشكل إلى مجموعة محظورًا. يكتب **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | يحدِّد ما إذا كان نقل هذا الشكل محظورًا. يكتب **bool**. |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | يحدِّد ما إذا كان تغيير زاوية الدوران لهذا الشكل محظورًا. يكتب **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | يحدِّد ما إذا كان اختيار هذا الشكل محظورًا. يكتب **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | يحدِّد ما إذا كان تغيير نوع الشكل محظورًا. يكتب **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | يحدِّد ما إذا كان تغيير حجم هذا الشكل محظورًا. يكتب **bool**. |
| virtual void [set_TextLocked](./set_textlocked/)(**bool**) | يحدِّد ما إذا كان تعديل النص محظورًا. يكتب **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلًا من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلًا من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يُتيح تحويل الكائنات المخصَّصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يُطبق بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | تنفّذ إلغاء قفل تعبير C# lock(). استدعٍ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [IBaseShapeLock](../ibaseshapelock/)
* مساحة الاسم [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)