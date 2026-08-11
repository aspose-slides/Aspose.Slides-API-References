---
title: IConnectorLock
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد العمليات التي تم تعطيلها على العنصر الأصل Connector.
type: docs
weight: 1860
url: /ar/aspose.slides/iconnectorlock/
---
## الفئة IConnectorLock

يحدد العمليات التي تم تعطيلها على العنصر الأصل [Connector](../connector/).

```cpp
class IConnectorLock : public virtual Aspose::Slides::IBaseShapeLock
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة (double) بأسلوب C# حيث يُعتَبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | يحدد ما إذا كان تغيير قيم الضبط محظورًا. قراءة **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | يحدد ما إذا كان تغيير رؤوس الأسهم محظورًا. قراءة **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | يحدد ما إذا كان يجب على الشكل الحفاظ على نسبة العرض إلى الارتفاع عند تغيير الحجم. قراءة **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | يحدد ما إذا كان تغيير الشكل الخارجي لهذا الشكل مباشرة محظورًا. قراءة **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | يحدد ما إذا كان إضافة هذا الشكل إلى مجموعة محظورًا. قراءة **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | يرجع true إذا كانت جميع أعلام القفل معطلة. **bool** للقراءة فقط. |
| virtual **bool** [get_PositionMove](./get_positionmove/)() | يحدد ما إذا كان نقل هذا الشكل محظورًا. قراءة **bool**. |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | يحدد ما إذا كان تغيير زاوية الدوران لهذا الشكل محظورًا. قراءة **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | يحدد ما إذا كان اختيار هذا الشكل محظورًا. قراءة **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | يحدد ما إذا كان تغيير نوع الشكل محظورًا. قراءة **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | يحدد ما إذا كان تغيير حجم هذا الشكل محظورًا. قراءة **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد الإشارة المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلًا للنوع الموضح بواسطة targetType. مماثل لمشغِل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل تعليمة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشتركة بالقيمة المحددة. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | يحدد ما إذا كان تغيير قيم الضبط محظورًا. كتابة **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | يحدد ما إذا كان تغيير رؤوس الأسهم محظورًا. كتابة **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | يحدد ما إذا كان يجب على الشكل الحفاظ على نسبة العرض إلى الارتفاع عند تغيير الحجم. كتابة **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | يحدد ما إذا كان تغيير الشكل الخارجي لهذا الشكل مباشرة محظورًا. كتابة **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | يحدد ما إذا كان إضافة هذا الشكل إلى مجموعة محظورًا. كتابة **bool**. |
| virtual void [set_PositionMove](./set_positionmove/)(**bool**) | يحدد ما إذا كان نقل هذا الشكل محظورًا. كتابة **bool**. |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | يحدد ما إذا كان تغيير زاوية الدوران لهذا الشكل محظورًا. كتابة **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | يحدد ما إذا كان اختيار هذا الشكل محظورًا. كتابة **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | يحدد ما إذا كان تغيير نوع الشكل محظورًا. كتابة **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | يحدد ما إذا كان تغيير حجم هذا الشكل محظورًا. كتابة **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n إلى مؤشر ضعيف (بدلاً من مشترك). يتيح تبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص عداد الإشارة المشتركة ويعيده. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل تعليمة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [IBaseShapeLock](../ibaseshapelock/)
* مساحة الاسم [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)