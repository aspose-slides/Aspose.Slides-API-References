---
title: ILayoutPlaceholderManager
second_title: مرجع API ل Aspose.Slides للغة C++
description: يمثل مديرًا يسمح لك بإضافة نائبات إلى شريحة التخطيط.
type: docs
weight: 2627
url: /ar/aspose.slides/ilayoutplaceholdermanager/
---
## ILayoutPlaceholderManager فئة

يمثِّل المدير الذي يسمح لك بإضافة نائبات إلى شريحة التخطيط.

```cpp
class ILayoutPlaceholderManager : public virtual System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddChartPlaceholder](./addchartplaceholder/)(**float**, **float**, **float**, **float**) | يضيف شكلاً نائبا جديدًا إلى شريحة التخطيط لحمل مخطط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddContentPlaceholder](./addcontentplaceholder/)(**float**, **float**, **float**, **float**) | يضيف شكلاً نائبا جديدًا إلى شريحة التخطيط لحمل محتوى، مثل صورة أو جدول أو وسائط أو نص. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddMediaPlaceholder](./addmediaplaceholder/)(**float**, **float**, **float**, **float**) | يضيف شكلاً نائبا جديدًا إلى شريحة التخطيط لحمل كائن وسائط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddOnlineImagePlaceholder](./addonlineimageplaceholder/)(**float**, **float**, **float**, **float**) | يضيف شكلاً نائبا جديدًا إلى شريحة التخطيط لحمل صورة عبر الإنترنت. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddPicturePlaceholder](./addpictureplaceholder/)(**float**, **float**, **float**, **float**) | يضيف شكلاً نائبا جديدًا إلى شريحة التخطيط لحمل صورة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddSmartArtPlaceholder](./addsmartartplaceholder/)(**float**, **float**, **float**, **float**) | يضيف شكلاً نائبا جديدًا إلى شريحة التخطيط لحمل مخطط [SmartArt](../../aspose.slides.smartart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddTablePlaceholder](./addtableplaceholder/)(**float**, **float**, **float**, **float**) | يضيف شكلاً نائبا جديدًا إلى شريحة التخطيط لحمل جدول. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddTextPlaceholder](./addtextplaceholder/)(**float**, **float**, **float**, **float**) | يضيف شكلاً نائبا جديدًا إلى شريحة التخطيط لحمل محتوى نصي. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddVerticalContentPlaceholder](./addverticalcontentplaceholder/)(**float**, **float**, **float**, **float**) | يضيف شكلاً نائبا جديدًا إلى شريحة التخطيط لحمل محتوى، مثل صورة أو جدول أو وسائط أو نص، باتجاه عمودي. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddVerticalTextPlaceholder](./addverticaltextplaceholder/)(**float**, **float**, **float**, **float**) | يضيف شكلاً نائبا جديدًا إلى شريحة التخطيط لحمل محتوى نصي باتجاه عمودي. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانانين متساويين رغم أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانانين متساويين رغم أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلاً للنوع الموصوف بواسطة targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يطبق قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل إسناد. لا ينسخ شيئًا فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن المرجع لكائن من النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضع الوسيط القالبي الـ n كمرجع ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق إلغاء قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## أنظر أيضًا

* الفئة [Object](../../system/object/)
* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)