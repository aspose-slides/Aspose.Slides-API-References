---
title: PresentationHeaderFooterManager
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: يمثل مديرًا يتحكم في سلوك جميع العناصر النائبة للتذييل، والوقت/التاريخ، وأرقام الصفحات في العرض التقديمي.
type: docs
weight: 4863
url: /ar/aspose.slides/presentationheaderfootermanager/
---
## PresentationHeaderFooterManager فئة


Represents manager which holds behavior of all footer, date-time and page number placeholders of presentation.

```cpp
class PresentationHeaderFooterManager : public Aspose::Slides::BaseHeaderFooterManager,
                                        public Aspose::Slides::IPresentationHeaderFooterManager
```

## الأساليب

| طريقة | وصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يتم اعتبار NaN اثنين متساويين على الرغم من أن IEC 60559:1989 تشير إلى أن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة ذات الدقة المزدوجة بأسلوب C# حيث يتم اعتبار NaN اثنين متساويين على الرغم من أن IEC 60559:1989 تشير إلى أن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. مماثل لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة lock() في C#. استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ إنشاء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل التعيين. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ إنشاء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات عن طريق المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات عن طريق المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [SetAllDateTimesText](./setalldatetimestext/)([System::String](../../system/string/)) override | يعيّن النص إلى جميع عناصر النائب للوقت والتاريخ، بما في ذلك الشرائح الرئيسة، شرائح التخطيط، الشرائح، رئيس الملاحظات، شرائح الملاحظات، والناشر الرئيسي. |
| void [SetAllDateTimesVisibility](./setalldatetimesvisibility/)(**bool**) override | يغيّر إظهار جميع عناصر النائب للوقت والتاريخ، بما في ذلك الشرائح الرئيسة، شرائح التخطيط، الشرائح، رئيس الملاحظات، شرائح الملاحظات، والناشر الرئيسي. |
| void [SetAllFootersText](./setallfooterstext/)([System::String](../../system/string/)) override | يعيّن النص إلى جميع عناصر النائب للتذييل، بما في ذلك الشرائح الرئيسة، شرائح التخطيط، الشرائح، رئيس الملاحظات، شرائح الملاحظات، والناشر الرئيسي. |
| void [SetAllFootersVisibility](./setallfootersvisibility/)(**bool**) override | يغيّر إظهار جميع عناصر النائب للتذييل، بما في ذلك الشرائح الرئيسة، شرائح التخطيط، الشرائح، رئيس الملاحظات، شرائح الملاحظات، والناشر الرئيسي. |
| void [SetAllHeadersText](./setallheaderstext/)([System::String](../../system/string/)) override | يعيّن النص إلى جميع عناصر النائب للترويسة، بما فيcluding رئيس الملاحظات، شرائح الملاحظات والناشر الرئيسي. |
| void [SetAllHeadersVisibility](./setallheadersvisibility/)(**bool**) override | يغيّر إظهار جميع عناصر النائب للترويسة، بما فيcluding رئيس الملاحظات، شرائح الملاحظات والناشر الرئيسي. |
| void [SetAllSlideNumbersVisibility](./setallslidenumbersvisibility/)(**bool**) override | يغيّر إظهار جميع عناصر النائب لأرقام الصفحات، بما فيincluding الشرائح الرئيسة، شرائح التخطيط، الشرائح، رئيس الملاحظات، شرائح الملاحظات والناشر الرئيسي. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n مؤشرًا ضعيفًا (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| void [SetVisibilityOnAllTitleSlides](./setvisibilityonalltitleslides/)(**bool**) override | يغيّر إظهار عناصر النائب للتذييل والوقت/التاريخ وأرقام الصفحات لجميع شرائح العنوان ولشريحة التخطيط الأولى. شرائح العنوان \u2013 شرائح تعتمد على شريحة التخطيط الأولى (بغض النظر عن نوع هذا التخطيط الأول). |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد المرجع المشترك ويعيده. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة lock() في C#. استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزداد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [BaseHeaderFooterManager](../baseheaderfootermanager/)
* الفئة [IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/)
* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)