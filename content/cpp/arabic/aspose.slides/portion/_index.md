---
title: Portion
second_title: Aspose.Slides لمرجع واجهة برمجة التطبيقات C++
description: يمثل جزءًا من النص داخل فقرة نصية.
type: docs
weight: 4772
url: /ar/aspose.slides/portion/
---
## فئة Portion

Represents a portion of text inside a text paragraph.

```cpp
class Portion : public Aspose::Slides::IPortion,
                public Aspose::Slides::IDOMObject
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| void [AddField](./addfield/)([System::SharedPtr](../../system/sharedptr/)\<[IFieldType](../ifieldtype/)\>) override | يحول هذه القطعة إلى حقل يتم تحديثه تلقائيًا. |
| void [AddField](./addfield/)([System::String](../../system/string/)) override | يحول هذه القطعة إلى حقل يتم تحديثه تلقائيًا. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | تحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن IEC 60559:1989 تقول إن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | تحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن IEC 60559:1989 تقول إن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للأغراض الداخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IField](../ifield/)\> [get_Field](./get_field/)() override | يرجع حقلًا لهذه القطعة. للقراءة فقط [IField](../ifield/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_PortionFormat](./get_portionformat/)() override | يرجع كائن تنسيق يحتوي على خصائص التنسيق المحددة صراحةً للقطعة النصية دون وراثة. للقراءة فقط [IPortionFormat](../iportionformat/). |
| [System::String](../../system/string/) [get_Text](./get_text/)() override | يحصل على النص العادي لقطعة. قراءة [System::String](../../system/string/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [GetCoordinates](./getcoordinates/)() override | يحصل على إحداثيات بداية القطعة. إحداثي X للنقطة يمثل بداية القطعة من الحرف الأول بما في ذلك الهامش الجانبي الأيسر. إحداثي Y يشمل الهامش العلوي. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetRect](./getrect/)() override | يحصل على إحداثيات المستطيل الذي يحد القطعة. المستطيل يشمل جميع خطوط النص في القطعة، بما في ذلك الفارغة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثلاً للنوع الموصوف بـ targetType. تناظر عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل العبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخة من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخة من الفئات الفرعية. |
|  [Portion](./portion/)() | يًهيئ نسخة جديدة من الفئة [Portion](./). |
|  [Portion](./portion/)([System::String](../../system/string/)) | يًهيئ نسخة جديدة من الفئة [Portion](./). |
|  [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Portion](./)\>) | يًهيئ نسخة جديدة من الفئة [Portion](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [RemoveField](./removefield/)() override | يحول هذه القطعة الحقلية إلى القطعة البسيطة. |
| void [set_Text](./set_text/)([System::String](../../system/string/)) override | يضبط النص العادي للقطعة. كتابة [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط المتغيّر القالبي n كإشارة ضعيفة (بدلاً من المشتركة). يتيح تحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استعمل المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل العبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [IPortion](../iportion/)
* فئة [IDOMObject](../idomobject/)
* مساحة الاسم [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)