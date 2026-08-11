---
title: FlyThroughTransition
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تأثير انتقال شريحة Fly-through.
type: docs
weight: 40
url: /ar/aspose.slides.slideshow/flythroughtransition/
---
## FlyThroughTransition الفئة

Fly-through slide transition effect.

```cpp
class FlyThroughTransition : public Aspose::Slides::SlideShow::TransitionValueBase,
                             public Aspose::Slides::SlideShow::IFlyThroughTransition
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| **bool** [Equals](../transitionvaluebase/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يحدد ما إذا كانت مثيلات [TransitionValueBase](../transitionvaluebase/) الاثنين متساوية. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوك C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقلّد مقارنة النقطة العائمة بنمط C# حيث تُ considered NaN واحدة مساوية للأخرى بالرغم من أنه وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقلّد مقارنة النقطة العائمة بنمط C# حيث تُ considered NaN واحدة مساوية للأخرى بالرغم من أنه وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [TransitionInOutDirectionType](../transitioninoutdirectiontype/) [get_Direction](./get_direction/)() override | اتجاه الانتقال. اقرأ [TransitionInOutDirectionType](../transitioninoutdirectiontype/). |
| **bool** [get_HasBounce](./get_hasbounce/)() override | يحدد أن حركة شرائح العرض أثناء الانتقال تشمل ارتدادًا. اقرأ **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عدّاد المرجع المتصلة بالكائن. |
| **int32_t** [GetHashCode](../transitionvaluebase/gethashcode/)() const override | يعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ الكائن. يهيّء جميع هياكل البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، بل يهيّء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | مشغل الإسناد. لا ينسخ أي شيء فعلًا، بل يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| void [set_Direction](./set_direction/)([TransitionInOutDirectionType](../transitioninoutdirectiontype/)) override | اتجاه الانتقال. اكتب [TransitionInOutDirectionType](../transitioninoutdirectiontype/). |
| void [set_HasBounce](./set_hasbounce/)(**bool**) override | يحدد أن حركة شرائح العرض أثناء الانتقال تشمل ارتدادًا. اكتب **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي رقم n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عدّاد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* الفئة [TransitionValueBase](../transitionvaluebase/)
* الفئة [IFlyThroughTransition](../iflythroughtransition/)
* النطاق [Aspose::Slides::SlideShow](../)
* المكتبة [Aspose.Slides](../../)