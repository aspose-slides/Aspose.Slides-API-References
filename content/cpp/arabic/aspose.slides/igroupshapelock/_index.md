---
title: IGroupShapeLock
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد أي العمليات تم تعطيلها على الكائن GroupShape الأصل.
type: docs
weight: 2497
url: /ar/aspose.slides/igroupshapelock/
---
## IGroupShapeLock فئة

يحدد أي العمليات تم تعطيلها على الأصل [GroupShape](../groupshape/).

```cpp
class IGroupShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## الطرق

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوك C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يُقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يُقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين رغم أن وفقًا للمعيار IEC 60559:1989 فإن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين رغم أن وفقًا للمعيار IEC 60559:1989 فإن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للأغراض الداخلية فقط. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | يحدد ما إذا كان يجب على الشكل الحفاظ على نسبة الأبعاد عند تغيير الحجم. قراءة **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | يحدد ما إذا كان إضافة هذا الشكل إلى مجموعة ممنوعًا. قراءة **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | يرجع true إذا كانت جميع علامات القفل معطلة. **bool** للقراءة فقط. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | يحدد ما إذا كان تحريك هذا الشكل ممنوعًا. قراءة **bool**. |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | يحدد ما إذا كان تغيير زاوية دوران هذا الشكل ممنوعًا. قراءة **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | يحدد ما إذا كان اختيار هذا الشكل ممنوعًا. قراءة **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | يحدد ما إذا كان تغيير حجم هذا الشكل ممنوحًا. قراءة **bool**. |
| virtual **bool** [get_UngroupingLocked](./get_ungroupinglocked/)() | يحدد ما إذا كان تقسيم شكل المجموعة هذا ممنوعًا. قراءة **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مكافئ لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مكافئ لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بواسطة targetType. مكافئ لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل تعبير C# lock(). يُستدعى مباشرة أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مكافئ لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | يُنشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مقابل nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | يحدد ما إذا كان الشكل يجب أن يحافظ على نسبة الأبعاد عند تغيير الحجم. كتابة **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | يحدد ما إذا كان إضافة هذا الشكل إلى مجموعة ممنوعًا. كتابة **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | يحدد ما إذا كان تحريك هذا الشكل ممنوعًا. كتابة **bool**. |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | يحدد ما إذا كان تغيير زاوية دوران هذا الشكل ممنوحًا. كتابة **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | يحدد ما إذا كان اختيار هذا الشكل ممنوحًا. كتابة **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | يحدد ما إذا كان تغيير حجم هذا الشكل ممنوحًا. كتابة **bool**. |
| virtual void [set_UngroupingLocked](./set_ungroupinglocked/)(**bool**) | يحدد ما إذا كان تقسيم شكل المجموعة هذا ممنوحًا. كتابة **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضعية ضعيفة. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مكافئ لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل تعبير C# lock(). يُستدعى مباشرة أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [IBaseShapeLock](../ibaseshapelock/)
* نطاق [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)