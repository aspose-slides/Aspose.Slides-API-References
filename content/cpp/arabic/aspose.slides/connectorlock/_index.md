---
title: ConnectorLock
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحدد العمليات التي تم تعطيلها على الموصل الأب
type: docs
weight: 495
url: /ar/aspose.slides/connectorlock/
---
## فئة ConnectorLock

يحدد العمليات التي تم تعطيلها على الكائن الأب [Connector](../connector/).

```cpp
class ConnectorLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IConnectorLock
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNّان متساويتين رغم أن IEC 60559:1989 تنص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNّان متساويتين رغم أن IEC 60559:1989 تنص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للأغراض الداخلية فقط. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | يحدد ما إذا كان تعديل قيم الضبط محظورًا. قراءة **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | يحدد ما إذا كان تعديل رؤوس السهام محظورًا. قراءة **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | يحدد ما إذا كان يجب على الشكل الحفاظ على نسبة الأبعاد أثناء تغيير الحجم. قراءة **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | يحدد ما إذا كان تعديل مباشر لمحيط هذا الشكل محظورًا. قراءة **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | يحدد ما إذا كان إضافة هذا الشكل إلى مجموعة محظورة. قراءة **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | يعيد true إذا كانت جميع علامات القفل معطلة. **bool** للقراءة فقط. |
| **bool** [get_PositionMove](./get_positionmove/)() override | يحدد ما إذا كان تحريك هذا الشكل محظورًا. قراءة **bool**. |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | يحدد ما إذا كان تعديل زاوية الدوران لهذا الشكل محظورًا. قراءة **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | يحدد ما إذا كان اختيار هذا الشكل محظورًا. قراءة **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | يحدد ما إذا كان تعديل نوع الشكل محظورًا. قراءة **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | يحدد ما إذا كان تعديل حجم هذا الشكل محظورًا. قراءة **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يجلب بنية بيانات عداد الإشارة المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يجلب النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، يهيئ كائنًا جديدًا فقط ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، يهيئ كائنًا جديدًا فقط ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشترك بالقيمة المحددة. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | يحدد ما إذا كان تعديل قيم الضبط محظورًا. كتابة **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | يحدد ما إذا كان تعديل رؤوس السهام محظورًا. كتابة **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | يحدد ما إذا كان يجب على الشكل الحفاظ على نسبة الأبعاد أثناء تغيير الحجم. كتابة **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | يحدد ما إذا كان تعديل مباشر لمحيط هذا الشكل محظورًا. كتابة **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | يحدد ما إذا كان إضافة هذا الشكل إلى مجموعة محظورة. كتابة **bool**. |
| void [set_PositionMove](./set_positionmove/)(**bool**) override | يحدد ما إذا كان تحريك هذا الشكل محظورًا. كتابة **bool**. |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | يحدد ما إذا كان تعديل زاوية الدوران لهذا الشكل محظورًا. كتابة **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | يحدد ما إذا كان اختيار هذا الشكل محظورًا. كتابة **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | يحدد ما إذا كان تعديل نوع الشكل محظورًا. كتابة **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | يحدد ما إذا كان تعديل حجم هذا الشكل محظورًا. كتابة **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كإشارة ضعيفة (بدلاً من المشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يجلب القيمة الحالية لعداد الإشارة المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد الإشارة المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ تركيبة C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* الفئة [BaseShapeLock](../baseshapelock/)
* الفئة [IConnectorLock](../iconnectorlock/)
* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)