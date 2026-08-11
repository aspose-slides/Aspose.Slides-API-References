---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides لـ C++ مرجع API
description: كائن غير قابل للتغيير يحتوي على خصائص تنسيق الفقرة الفعّالة.
type: docs
weight: 3160
url: /ar/aspose.slides/iparagraphformateffectivedata/
---
## IParagraphFormatEffectiveData فئة

كائن غير قابل للتغيير يحتوي على خصائص تنسيق الفقرة الفعّالة.

```cpp
class IParagraphFormatEffectiveData : public virtual System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | محاكاة مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان متساويين على الرغم من أن IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | محاكاة مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان متساويين على الرغم من أن IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للأغراض الداخلية فقط. |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | يرجع محاذاة النص في الفقرة. للقراءة فقط [TextAlignment](../textalignment/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [get_Bullet](./get_bullet/)() | يرجع تنسيق نقطة تعداد للفقرة. للقراءة فقط [IBulletFormatEffectiveData](../ibulletformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | يرجع تنسيق الجزء الافتراضي للفقرة. للقراءة فقط [IPortionFormatEffectiveData](../iportionformateffectivedata/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | يرجع حجم الفواصل الافتراضي. للقراءة فقط **float**. |
| virtual **int16_t** [get_Depth](./get_depth/)() | يرجع عمق الفقرة. للقراءة فقط **int16_t**. |
| virtual **bool** [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | يحدد ما إذا كان يتم استخدام فاصل الأسطر شرق آسيا في الفقرة. للقراءة فقط **bool**. |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | يرجع محاذاة الخط في الفقرة. للقراءة فقط [Slides::FontAlignment](../fontalignment/). |
| virtual **bool** [get_HangingPunctuation](./get_hangingpunctuation/)() | يحدد ما إذا كان يتم استخدام علامات الترقيم المتدلية في الفقرة. للقراءة فقط **bool**. |
| virtual **float** [get_Indent](./get_indent/)() | يرجع إزاحة السطر الأول/الإزاحة المتدلية للفقرة. يمكن تعريف الإزاحة المتدلية بقيم سالبة. للقراءة فقط **float**. |
| virtual **bool** [get_LatinLineBreak](./get_latinlinebreak/)() | يحدد ما إذا كان يتم استخدام فاصل الأسطر اللاتينية في الفقرة. للقراءة فقط **bool**. |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | يرجع الهامش الأيسر في الفقرة. للقراءة فقط **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | يرجع الهامش الأيمن في الفقرة. للقراءة فقط **float**. |
| virtual **bool** [get_RightToLeft](./get_righttoleft/)() | يحدد ما إذا كان يتم استخدام الكتابة من اليمين إلى اليسار في الفقرة. للقراءة فقط **bool**. |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | يرجع مقدار المسافة بعد السطر الأخير في الفقرة. للقراءة فقط **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | يرجع مقدار المسافة قبل السطر الأول في الفقرة. للقراءة فقط **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | يرجع مقدار المسافة بين الأسطر الأساسية في الفقرة. للقراءة فقط **float**. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITabEffectiveData](../itabeffectivedata/)\>\> [get_Tabs](./get_tabs/)() | يرجع الفواصل للفقرة. للقراءة فقط [ITabEffectiveData](../itabeffectivedata/)[]. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل مثالًا للنوع الموضح بواسطة targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | تنفيذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح نسخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | يُنشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخة. لا ينسخ شيئًا في الواقع، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا في الواقع، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجعية مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | تنفيذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | تنفيذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## ملاحظات

يُستخدم هذا الواجهة مع واجهة [IParagraphFormat](../iparagraphformat/) لإرجاع قيم التنسيق الفعّالة مع تطبيق الوراثة.

## انظر أيضًا

* الفئة [Object](../../system/object/)
* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)