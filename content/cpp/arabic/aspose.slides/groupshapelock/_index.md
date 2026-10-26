---
title: GroupShapeLock
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد العمليات التي تم تعطيلها على العنصر الأصل GroupShape.
type: docs
weight: 1210
url: /ar/aspose.slides/groupshapelock/
---
## الفئة GroupShapeLock

يحدد أي العمليات تم تعطيلها على العنصر الأصل [GroupShape](../groupshape/).

```cpp
class GroupShapeLock : public Aspose::Slides::BaseShapeLock,
                       public Aspose::Slides::IGroupShapeLock
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعامل قيمتي NaN على أنهما متساويتان على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعامل قيمتي NaN على أنهما متساويتان على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | يحدد ما إذا كان الشكل يجب أن يحافظ على نسبة الأبعاد عند إعادة التحجيم. قراءة **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | يحدد ما إذا كان إضافة هذا الشكل إلى مجموعة محظورة. قراءة **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | إرجاع true إذا تم تعطيل جميع أعلام القفل. **bool** للقراءة فقط. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | يحدد ما إذا كان تحريك هذا الشكل محظورًا. قراءة **bool**. |
| **bool** [get_RotationLocked](./get_rotationlocked/)() override | يحدد ما إذا كان تغيير زاوية الدوران لهذا الشكل محظورًا. قراءة **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | يحدد ما إذا كان اختيار هذا الشكل محظورًا. قراءة **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | يحدد ما إذا كان تغيير حجم هذا الشكل محظورًا. قراءة **bool**. |
| **bool** [get_UngroupingLocked](./get_ungroupinglocked/)() override | يحدد ما إذا كان تقسيم هذا الشكل المجمع محظورًا. قراءة **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد الإشارة المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير دالة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير دالة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | المُنشئ النسخي. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | يحدد ما إذا كان الشكل يجب أن يحافظ على نسبة الأبعاد عند إعادة التحجيم. كتابة **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | يحدد ما إذا كان إضافة هذا الشكل إلى مجموعة محظورة. كتابة **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | يحدد ما إذا كان تحريك هذا الشكل محظورًا. كتابة **bool**. |
| void [set_RotationLocked](./set_rotationlocked/)(**bool**) override | يحدد ما إذا كان تغيير زاوية الدوران لهذا الشكل محظورًا. كتابة **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | يحدد ما إذا كان اختيار هذا الشكل محظورًا. كتابة **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | يحدد ما إذا كان تغيير حجم هذا الشكل محظورًا. كتابة **bool**. |
| void [set_UngroupingLocked](./set_ungroupinglocked/)(**bool**) override | يحدد ما إذا كان تقسيم هذا الشكل المجمع محظورًا. كتابة **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كإشارة ضعيفة (بدلاً من المشتركة). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير دالة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الصنف [BaseShapeLock](../baseshapelock/)
* الصنف [IGroupShapeLock](../igroupshapelock/)
* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)