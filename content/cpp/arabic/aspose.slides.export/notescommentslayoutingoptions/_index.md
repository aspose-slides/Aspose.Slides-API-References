---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides لـ C++ مرجع API
description: يوفر خيارات تتحكم في مظهر تخطيط الملاحظات والتعليقات في المستند المُصدَّر.
type: docs
weight: 560
url: /ar/aspose.slides.export/notescommentslayoutingoptions/
---
## NotesCommentsLayoutingOptions الفئة

يوفر خيارات تتحكم في مظهر تخطيط الملاحظات والتعليقات في المستند المُصدَّر.

```cpp
class NotesCommentsLayoutingOptions : public Aspose::Slides::Export::ISlidesLayoutOptions
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوك C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُ considered NaNانان متساويين بالرغم من أن وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُ considered NaNانان متساويين بالرغم من أن وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::Drawing::Color](../../system.drawing/color/) [get_CommentsAreaColor](./get_commentsareacolor/)() | يعيد لون منطقة التعليقات (يطبق فقط إذا تم عرض التعليقات على اليمين). |
| **int32_t** [get_CommentsAreaWidth](./get_commentsareawidth/)() | يعيد عرض مساحة إخراج التعليق بالبكسل (يطبق فقط إذا تم عرض التعليقات على اليمين). |
| [CommentsPositions](../commentspositions/) [get_CommentsPosition](./get_commentsposition/)() | يعيد موضع التعليقات على الصفحة. |
| [NotesPositions](../notespositions/) [get_NotesPosition](./get_notesposition/)() | يعيد موضع الملاحظات على الصفحة. |
| **bool** [get_ShowCommentsByNoAuthor](./get_showcommentsbynoauthor/)() | يعيد رؤية التعليقات التي لا تحتوي على مؤلف. إذا كان true فسيتم عرض التعليقات. (يطبق فقط إذا تم عرض التعليقات). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يعيد هيكل عداد المرجعية المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يعيد النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. تناظر عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [NotesCommentsLayoutingOptions](./notescommentslayoutingoptions/)() | المنشئ الافتراضي. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجعية المشتركة بالقيمة المحددة. |
| void [set_CommentsAreaColor](./set_commentsareacolor/)([System::Drawing::Color](../../system.drawing/color/)) | يضبط لون منطقة التعليقات (يطبق فقط إذا تم عرض التعليقات على اليمين). |
| void [set_CommentsAreaWidth](./set_commentsareawidth/)(**int32_t**) | يضبط عرض مساحة إخراج التعليق بالبكسل (يطبق فقط إذا تم عرض التعليقات على اليمين). |
| void [set_CommentsPosition](./set_commentsposition/)([CommentsPositions](../commentspositions/)) | يضبط موضع التعليقات على الصفحة. |
| void [set_NotesPosition](./set_notesposition/)([NotesPositions](../notespositions/)) | يضبط موضع الملاحظات على الصفحة. |
| void [set_ShowCommentsByNoAuthor](./set_showcommentsbynoauthor/)(**bool**) | يضبط رؤية التعليقات التي لا تحتوي على مؤلف. إذا كان true فسيتم عرض التعليقات. (يطبق فقط إذا تم عرض التعليقات). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n't إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتبديل المؤشرات داخل الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يعيد القيمة الحالية لعداد المرجعية المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجعية المشتركة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عدّاد المرجعية المشتركة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ تركيبة C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجعية الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد المرجعية الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |
## انظر أيضًا

* الفئة [ISlidesLayoutOptions](../islideslayoutoptions/)
* مساحة الاسم [Aspose::Slides::Export](../)
* المكتبة [Aspose.Slides](../../)