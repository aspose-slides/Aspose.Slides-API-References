---
title: AutoShapeLock
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد أي العمليات معطلة على العنصر الأصل AutoshapeEx.
type: docs
weight: 79
url: /ar/aspose.slides/autoshapelock/
---
## AutoShapeLock فئة

يحدد أي العمليات معطلة على العنصر الأصل AutoshapeEx.

```cpp
class AutoShapeLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IAutoShapeLock
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقطية عائمة بأسلوب C# حيث يُعتبر NaNانان متساويين رغم أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقطية عائمة بأسلوب C# حيث يُعتبر NaNانان متساويين رغم أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لاستخدام الداخلي فقط. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | يحدد ما إذا كان تعديل قيم الضبط ممنوعًا. قراءة **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | يحدد ما إذا كان تعديل رؤوس السهام ممنوعًا. قراءة **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | يحدد ما إذا كان يجب على الشكل حفظ نسبة الأبعاد عند تغيير الحجم. قراءة **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | يحدد ما إذا كان تعديل مباشر لمحيط هذا الشكل ممنوعًا. قراءة **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | يحدد ما إذا كان إضافة هذا الشكل إلى مجموعة ممنوعًا. قراءة **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | يرجع true إذا كانت جميع أعلام القفل معطلة. قراءة فقط **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | يحدد ما إذا كان تحريك هذا الشكل ممنوعًا. قراءة **bool**. |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | يحدد ما إذا كان تعديل زاوية الدوران لهذا الشكل ممنوعًا. قراءة **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | يحدد ما إذا كان اختيار هذا الشكل ممنوعًا. قراءة **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | يحدد ما إذا كان تعديل نوع الشكل ممنوعًا. قراءة **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | يحدد ما إذا كان تغيير حجم هذا الشكل ممنوعًا. قراءة **bool**. |
| **bool** [get_TextLocked](./get_textlocked/)() override | يحدد ما إذا كان تحرير النص ممنوعًا. قراءة **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير معامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل إسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد المراجع المشتركة بالقيمة المحددة. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | يحدد ما إذا كان تعديل قيم الضبط ممنوعًا. كتابة **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | يحدد ما إذا كان تعديل رؤوس السهام ممنوعًا. كتابة **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | يحدد ما إذا كان يجب على الشكل حفظ نسبة الأبعاد عند تغيير الحجم. كتابة **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | يحدد ما إذا كان تعديل مباشر لمحيط هذا الشكل ممنوعًا. كتابة **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | يحدد ما إذا كان إضافة هذا الشكل إلى مجموعة ممنوعًا. كتابة **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | يحدد ما إذا كان تحريك هذا الشكل ممنوعًا. كتابة **bool**. |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | يحدد ما إذا كان تعديل زاوية الدوران لهذا الشكل ممنوعًا. كتابة **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | يحدد ما إذا كان اختيار هذا الشكل ممنوعًا. كتابة **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | يحدد ما إذا كان تعديل نوع الشكل ممنوعًا. كتابة **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | يحدد ما إذا كان تغيير حجم هذا الشكل ممنوعًا. كتابة **bool**. |
| void [set_TextLocked](./set_textlocked/)(**bool**) override | يحدد ما إذا كان تحرير النص ممنوعًا. كتابة **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل تعبير C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمّر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* الفئة [BaseShapeLock](../baseshapelock/)
* الفئة [IAutoShapeLock](../iautoshapelock/)
* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)