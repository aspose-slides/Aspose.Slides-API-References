---
title: IPictureFrameLock
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد أي العمليات معطلة على الـ PictureFrameEx الأب.
type: docs
weight: 3264
url: /ar/aspose.slides/ipictureframelock/
---
## IPictureFrameLock فئة


يحدد أي العمليات معطلة على الـ PictureFrameEx الأب.

```cpp
class IPictureFrameLock : public virtual Aspose::Slides::IBaseShapeLock
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر قيمتا NaN متساويتين رغم أنه وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر قيمتا NaN متساويتين رغم أنه وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | يحدد ما إذا كان تعديل قيم الضبط ممنوعًا. قراءة **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | يحدد ما إذا كان تعديل رؤوس الأسهم ممنوعًا. قراءة **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | يحدد ما إذا كان على الشكل الحفاظ على نسبة الأبعاد عند تغيير الحجم. قراءة **bool**. |
| virtual **bool** [get_CropLocked](./get_croplocked/)() | يحدد ما إذا كان قص الصورة ممنوعًا. قراءة **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | يحدد ما إذا كان تعديل مباشر لمحيط هذا الشكل ممنوعًا. قراءة **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | يحدد ما إذا كان إضافة هذا الشكل إلى مجموعة ممنوعًا. قراءة **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | إرجاع true إذا تم تعطيل جميع أعلام القفل. **bool** للقراءة فقط. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | يحدد ما إذا كان تحريك هذا الشكل ممنوعًا. قراءة **bool**. |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | يحدد ما إذا كان تعديل زاوية الدوران لهذا الشكل ممنوعًا. قراءة **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | يحدد ما إذا كان اختيار هذا الشكل ممنوعًا. قراءة **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | يحدد ما إذا كان تعديل نوع الشكل ممنوعًا. قراءة **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | يحدد ما إذا كان تغيير حجم هذا الشكل ممنوعًا. قراءة **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | إنشاء كائن. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعلاً، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعلاً، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | يحدد ما إذا كان تعديل قيم الضبط ممنوعًا. كتابة **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | يحدد ما إذا كان تعديل رؤوس الأسهم ممنوعًا. كتابة **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | يحدد ما إذا كان على الشكل الحفاظ على نسبة الأبعاد عند تغيير الحجم. كتابة **bool**. |
| virtual void [set_CropLocked](./set_croplocked/)(**bool**) | يحدد ما إذا كان قص الصورة ممنوعًا. كتابة **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | يحدد ما إذا كان تعديل مباشر لمحيط هذا الشكل ممنوعًا. كتابة **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | يحدد ما إذا كان إضافة هذا الشكل إلى مجموعة ممنوعًا. كتابة **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | يحدد ما إذا كان تحريك هذا الشكل ممنوعًا. كتابة **bool**. |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | يحدد ما إذا كان تعديل زاوية الدوران لهذا الشكل ممنوعًا. كتابة **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | يحدد ما إذا كان اختيار هذا الشكل ممنوعًا. كتابة **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | يحدد ما إذا كان تعديل نوع الشكل ممنوعًا. كتابة **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | يحدد ما إذا كان تغيير حجم هذا الشكل ممنوعًا. كتابة **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | تعيين الوسيط القالبي الـ n't إلى مؤشر ضعيف (بدلاً من مشترك). يتيح تبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [IBaseShapeLock](../ibaseshapelock/)
* مساحة الاسم [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)