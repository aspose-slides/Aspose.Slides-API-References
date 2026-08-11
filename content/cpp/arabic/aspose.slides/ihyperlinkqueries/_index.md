---
title: IHyperlinkQueries
second_title: مرجع API Aspose.Slides للغة C++
description: توفير وصول سهل إلى الارتباطات التشعبية المتضمنة.
type: docs
weight: 2562
url: /ar/aspose.slides/ihyperlinkqueries/
---
## IHyperlinkQueries فئة

Provide easy access to contained hyperlinks.

```cpp
class IHyperlinkQueries : public virtual System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع المرجعية بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يتم اعتبار NaN اثنين متساويين على الرغم من أن معيار IEC 60559:1989 يقول إن NaN غير متساوٍ مع أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يتم اعتبار NaN اثنين متساويين على الرغم من أن معيار IEC 60559:1989 يقول إن NaN غير متساوٍ مع أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IList](../../system.collections.generic/ilist/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkContainer](../ihyperlinkcontainer/)\>\>\> [GetAnyHyperlinks](./getanyhyperlinks/)() | احصل على جميع الكائنات الفرعية [IHyperlinkContainer](../ihyperlinkcontainer/) التي تحتوي على HyperlinkMouseOver غير فارغ. باستخدام كائن [IHyperlinkContainer](../ihyperlinkcontainer/) المعطى يمكنك إدارة الارتباط التشعبي الخاص به (قراءة، تحديث أو إزالة). راجع الواجهة [IHyperlinkContainer](../ihyperlinkcontainer/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل للطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IList](../../system.collections.generic/ilist/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkContainer](../ihyperlinkcontainer/)\>\>\> [GetHyperlinkClicks](./gethyperlinkclicks/)() | احصل على جميع الكائنات الفرعية [IHyperlinkContainer](../ihyperlinkcontainer/) التي تحتوي على HyperlinkClick غير فارغ. باستخدام كائن [IHyperlinkContainer](../ihyperlinkcontainer/) المعطى يمكنك إدارة الارتباط التشعبي الخاص به (قراءة، تحديث أو إزالة). راجع الواجهة [IHyperlinkContainer](../ihyperlinkcontainer/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IList](../../system.collections.generic/ilist/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkContainer](../ihyperlinkcontainer/)\>\>\> [GetHyperlinkMouseOvers](./gethyperlinkmouseovers/)() | احصل على جميع الكائنات الفرعية [IHyperlinkContainer](../ihyperlinkcontainer/) التي تحتوي على HyperlinkMouseOver غير فارغ. باستخدام كائن [IHyperlinkContainer](../ihyperlinkcontainer/) المعطى يمكنك إدارة الارتباط التشعبي الخاص به (قراءة، تحديث أو إزالة). راجع الواجهة [IHyperlinkContainer](../ihyperlinkcontainer/). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يُنفّذ قفل جملة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل للطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء، في الواقع، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء، في الواقع، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| virtual void [RemoveAllHyperlinks](./removeallhyperlinks/)() | يزيل جميع ارتباطات HyperlinkClick و HyperlinkMouseOver المحتواة (في جميع الكائنات الفرعية [IHyperlinkContainer](../ihyperlinkcontainer/)). |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n't إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل للطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يُنفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يُنفّذ فك قفل جملة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## أنظر أيضًا

* فئة [Object](../../system/object/)
* مساحة الأسماء [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)