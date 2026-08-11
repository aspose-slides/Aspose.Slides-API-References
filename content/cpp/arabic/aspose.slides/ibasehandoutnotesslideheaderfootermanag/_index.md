---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: مرجع API الخاص بـ Aspose.Slides للـ C++
description: يمثل المُدير الذي يتحكم في سلوك العناصر النائبة، بما في ذلك عنصر نائب العنوان لجميع أنواع شرائح الملاحظات والنشرات.
type: docs
weight: 1431
url: /ar/aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
## IBaseHandoutNotesSlideHeaderFooterManag فئة


يمثِّل المُدير الذي يتحكم في سلوك العناصر النائبة، بما في ذلك عنصر نائب العنوان لجميع أنواع شرائح الملاحظات والنشرات.

```cpp
class IBaseHandoutNotesSlideHeaderFooterManag : public virtual Aspose::Slides::IBaseSlideHeaderFooterManager
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبر NaNانان متساويين رغم أنه وفق IEC 60559:1989 لا يساوي NaN أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبر NaNانان متساويين رغم أنه وفق IEC 60559:1989 لا يساوي NaN أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual **bool** [get_IsDateTimeVisible](../ibaseslideheaderfootermanager/get_isdatetimevisible/)() | يحصل على القيمة التي تشير إلى وجود عنصر نائب للوقت والتاريخ. قراءة**bool**. |
| virtual **bool** [get_IsFooterVisible](../ibaseslideheaderfootermanager/get_isfootervisible/)() | يحصل على القيمة التي تشير إلى وجود عنصر نائب للتذييل. قراءة **bool**. |
| virtual **bool** [get_IsHeaderVisible](./get_isheadervisible/)() | يحصل على القيمة التي تشير إلى وجود عنصر نائب للعنوان. قراءة **bool**. |
| virtual **bool** [get_IsSlideNumberVisible](../ibaseslideheaderfootermanager/get_isslidenumbervisible/)() | يحصل على القيمة التي تشير إلى وجود عنصر نائب لرقم الصفحة. قراءة**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetDateTimeText](../ibaseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) | يضبط النص لعنصر نائب للوقت والتاريخ في الشريحة. |
| virtual void [SetDateTimeVisibility](../ibaseslideheaderfootermanager/setdatetimevisibility/)(**bool**) | يغيّر وضوح عنصر نائب الوقت والتاريخ في الشريحة. |
| virtual void [SetFooterText](../ibaseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) | يضبط النص لعنصر نائب التذييل في الشريحة. |
| virtual void [SetFooterVisibility](../ibaseslideheaderfootermanager/setfootervisibility/)(**bool**) | يغيّر وضوح عنصر نائب التذييل في الشريحة. |
| virtual void [SetHeaderText](./setheadertext/)([System::String](../../system/string/)) | يضبط النص لعنصر نائب العنوان في الشريحة. |
| virtual void [SetHeaderVisibility](./setheadervisibility/)(**bool**) | يغيّر وضوح عنصر نائب العنوان في الشريحة. |
| virtual void [SetSlideNumberVisibility](../ibaseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) | يغيّر وضوح عنصر نائب رقم الصفحة في الشريحة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي رقم n على مؤشر ضعيف (بدلاً من مشترك). يسمح بالتبديل بين المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## ملاحظات

اسم الواجهة الأصلي "IBaseHandoutNotesSlideHeaderFooterManager" تم اختصاره إلى "IBaseHandoutNotesSlideHeaderFooterManag" لتوافق COM (يجب ألا يتجاوز طول اسم النوع 39).

## انظر أيضاً

* الفئة [IBaseSlideHeaderFooterManager](../ibaseslideheaderfootermanager/)
* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)