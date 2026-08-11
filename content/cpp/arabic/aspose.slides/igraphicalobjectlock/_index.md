---
title: IGraphicalObjectLock
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحدد أي العمليات تم تعطيلها على العنصر الأب GraphicalObjectEx.
type: docs
weight: 2471
url: /ar/aspose.slides/igraphicalobjectlock/
---
## IGraphicalObjectLock فئة


يحدد أي العمليات تم تعطيلها على العنصر الأب GraphicalObjectEx.

```cpp
class IGraphicalObjectLock : public virtual Aspose::Slides::IBaseShapeLock
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتَبَر NaN اثنان متساويتين على الرغم من أن IEC 60559:1989 تُعرّف أن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتَبَر NaN اثنان متساويتين على الرغم من أن IEC 60559:1989 تُعرّف أن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للأغراض الداخلية فقط. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | يحدد ما إذا كان يجب على الشكل الحفاظ على نسبة العرض إلى الارتفاع عند تغيير الحجم. قراءة **bool**. |
| virtual **bool** [get_DrilldownLocked](./get_drilldownlocked/)() | يحدد ما إذا كان اختيار الأشكال الفرعية لهذا الكائن ممنوعًا. قراءة **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | يحدد ما إذا كان إضافة هذا الشكل إلى مجموعة ممنوعًا. قراءة **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | إرجاع true إذا تم تعطيل جميع علامات القفل. قراءة فقط **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | يحدد ما إذا كان تحريك هذا الشكل ممنوعًا. قراءة **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | يحدد ما إذا كان اختيار هذا الشكل ممنوعًا. قراءة **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | يحدد ما إذا كان تغيير حجم هذا الشكل ممنوعًا. قراءة **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عدّاد المرجعات المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل مثالًا للنوع الموصوف بـ targetType. تناظر عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقوم بتقليل عدّاد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | يحدد ما إذا كان يجب على الشكل الحفاظ على نسبة العرض إلى الارتفاع عند تغيير الحجم. كتابة **bool**. |
| virtual void [set_DrilldownLocked](./set_drilldownlocked/)(**bool**) | يحدد ما إذا كان اختيار الأشكال الفرعية لهذا الكائن ممنوعًا. كتابة **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | يحدد ما إذا كان إضافة هذا الشكل إلى مجموعة ممنوعًا. كتابة **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | يحدد ما إذا كان تحريك هذا الشكل ممنوعًا. كتابة **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | يحدد ما إذا كان اختيار هذا الشكل ممنوعًا. كتابة **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | يحدد ما إذا كان تغيير حجم هذا الشكل ممنوعًا. كتابة **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | تعيين الوسيط القالب رقم n كإشارة ضعيفة (بدلاً من مشاركة). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عدّاد المرجع المشترك ويعيده. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [IBaseShapeLock](../ibaseshapelock/)
* مساحة الأسماء [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)