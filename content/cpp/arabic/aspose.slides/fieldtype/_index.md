---
title: FieldType
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يمثل نوعًا من الحقل. تحدد هذه القيمة النص الذي سيتم تعيينه إلى جزء الحقل عند تحديثه.
type: docs
weight: 872
url: /ar/aspose.slides/fieldtype/
---
## FieldType فئة

Represents a type of field. This value determines which text will be set to the field portion when it will be updated.

```cpp
class FieldType : public Aspose::Slides::IFieldType
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يتحقق مما إذا كان هذا الحقل يساوي آخر. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقطية عائمة بنمط C# حيث يتم اعتبار NaNين متساوين بالرغم من أن IEC 60559:1989 يحدد أن NaN ليس مساوٍ لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقطية عائمة بنمط C# حيث يتم اعتبار NaNين متساوين بالرغم من أن IEC 60559:1989 يحدد أن NaN ليس مساوٍ لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
|  [FieldType](./fieldtype/)([System::String](../../system/string/)) | يهيئ نسخة جديدة من فئة [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime](./get_datetime/)() | التاريخ والوقت الحالي بالصيغة الافتراضية لتطبيق العرض. للقراءة فقط [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime1](./get_datetime1/)() | التاريخ والوقت الحالي بصيغة محددة أولاً (MM/DD/YYYY للإنجليزية). للقراءة فقط [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime10](./get_datetime10/)() | التاريخ والوقت الحالي بصيغة محددة ثانياً (hh:mm للإنجليزية). للقراءة فقط [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime11](./get_datetime11/)() | التاريخ والوقت الحالي بصيغة محددة ثالثاً (hh:mm:ss للإنجليزية). للقراءة فقط [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime12](./get_datetime12/)() | التاريخ والوقت الحالي بصيغة محددة رابعاً (hh:mm AM/PM للإنجليزية). للقراءة فقط [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime13](./get_datetime13/)() | التاريخ والوقت الحالي بصيغة محددة خامساً (hh:mm:ss AM/PM للإنجليزية). للقراءة فقط [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime2](./get_datetime2/)() | التاريخ والوقت الحالي بصيغة محددة سادساً (Day, Month DD, YYYY للإنجليزية). للقراءة فقط [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime3](./get_datetime3/)() | التاريخ والوقت الحالي بصيغة محددة سابعاً (DD Month YYYY للإنجليزية). للقراءة فقط [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime4](./get_datetime4/)() | التاريخ والوقت الحالي بصيغة محددة ثامناً (Month DD, YYYY للإنجليزية). للقراءة فقط [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime5](./get_datetime5/)() | التاريخ والوقت الحالي بصيغة محددة تاسعاً (DD-Mon-YY للإنجليزية). للقراءة فقط [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime6](./get_datetime6/)() | التاريخ والوقت الحالي بصيغة محددة عاشراً (Month YY للإنجليزية). للقراءة فقط [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime7](./get_datetime7/)() | التاريخ والوقت الحالي بصيغة محددة حادي عشر (Mon-YY للإنجليزية). للقراءة فقط [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime8](./get_datetime8/)() | التاريخ والوقت الحالي بصيغة محددة ثانٍ عشر (MM/DD/YYYY hh:mm AM/PM للإنجليزية). للقراءة فقط [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime9](./get_datetime9/)() | التاريخ والوقت الحالي بصيغة محددة ثالث عشر (MM/DD/YYYY hh:mm:ss AM/PM للإنجليزية). للقراءة فقط [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_Footer](./get_footer/)() | تذييل [Slide](../slide/). للقراءة فقط [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_Header](./get_header/)() | رأس [Slide](../slide/). للقراءة فقط [FieldType](./). |
| [System::String](../../system/string/) [get_InternalString](./get_internalstring/)() override | ترجع الاسم الداخلي لهذا الكائن [FieldType](./). قراءة [System::String](../../system/string/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_SlideNumber](./get_slidenumber/)() | رقم الشريحة الحالية. للقراءة فقط [FieldType](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | ترجع قيمة الهاش لهذا الكائن. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير مشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل بيان C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يمكّن استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بنسخ الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بنسخ الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_InternalString](./set_internalstring/)([System::String](../../system/string/)) override | ترجع الاسم الداخلي لهذا الكائن [FieldType](./). كتابة [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط معامل القالب رقم n إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد المرجع المشترك ويعيد قيمته. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يمكّن تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل بيان C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [IFieldType](../ifieldtype/)
* مساحة الاسم [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)