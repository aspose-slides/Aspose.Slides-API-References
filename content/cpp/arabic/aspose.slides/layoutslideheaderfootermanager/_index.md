---
title: LayoutSlideHeaderFooterManager
second_title: مرجع API Aspose.Slides للغة C++
description: يمثل مديرًا يحتفظ بسلوك تذييل شريحة التخطيط، وعناصر النائب للتاريخ-الوقت، ورقم الصفحة وجميع العناصر النائبة الفرعية. تعني العناصر النائبة الفرعية أن العناصر النائبة موجودة على الشرائح التابعة. الشرائح التابعة تستخدم وتعتمد على شريحة التخطيط.
type: docs
weight: 4317
url: /ar/aspose.slides/layoutslideheaderfootermanager/
---
## LayoutSlideHeaderFooterManager فئة

يمثّل مديرًا يحتفظ بسلوك تذييل شريحة التخطيط، عناصر نائبة التاريخ-الوقت، رقم الصفحة والعناصر النائبة التابعة. العناصر النائبة التابعة تعني أنّ العناصر النائبة موجودة على الشرائح التابعة. الشرائح التابعة تستخدم وتعتمد على شريحة التخطيط.

```cpp
class LayoutSlideHeaderFooterManager : public Aspose::Slides::BaseSlideHeaderFooterManager,
                                       public Aspose::Slides::ILayoutSlideHeaderFooterManager
```

## الأساليب

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سيمانتيك C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | تحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر قيمة NaN مزدوجة متساوية على الرغم من أنه وفقًا للمعيار IEC 60559:1989 لا تعتبر NaN مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | تحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر قيمة NaN مزدوجة متساوية على الرغم من أنه وفقًا للمعيار IEC 60559:1989 لا تعتبر NaN مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | يحصل على قيمة تشير إلى وجود عنصر نائبي تاريخ-وقت. Read**bool**. |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | يحصل على قيمة تشير إلى وجود عنصر نائبي تذييل. Read **bool**. |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | يحصل على قيمة تشير إلى وجود عنصر نائبي رقم الصفحة. Read**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يُنفّذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء، فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء، فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) override | يعيّن النص إلى عنصر نائبي تاريخ-وقت لشريحة التخطيط وجميع عناصر النائبة للوقت الخاصة بالأطفال. تعني عناصر النائبة للأطفال أنها موجودة على الشرائح التابعة. الشرائح التابعة تستخدم وتعتمد على شريحة التخطيط. |
| void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) override | يغيّر رؤية عنصر نائبي تاريخ-وقت لشريحة التخطيط وجميع عناصر النائبة للوقت الخاصة بالأطفال. تعني عناصر النائبة للأطفال أنها موجودة على الشرائح التابعة. الشرائح التابعة تستخدم وتعتمد على شريحة التخطيط. |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | يعيّن النص إلى عنصر نائبي تاريخ-وقت للشرائح. |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | يغيّر رؤية عنصر نائبي تاريخ-وقت للشرائح. |
| void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) override | يعيّن النص إلى عنصر نائبي تذييل شريحة التخطيط وجميع عناصر النائبة للتذييل الخاصة بالأطفال. تعني عناصر النائبة للأطفال أنها موجودة على الشرائح التابعة. الشرائح التابعة تستخدم وتعتمد على شريحة التخطيط. |
| void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) override | يغيّر رؤية عنصر نائبي تذييل شريحة التخطيط وجميع عناصر النائبة للتذييل الخاصة بالأطفال. تعني عناصر النائبة للأطفال أنها موجودة على الشرائح التابعة. الشرائح التابعة تستخدم وتعتمد على شريحة رئيسية. |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | يعيّن النص إلى عنصر نائبي تذييل للشرائح. |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | يغيّر رؤية عنصر نائبي تذييل للشرائح. |
| void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) override | يغيّر رؤية عنصر نائبي رقم الصفحة لشريحة التخطيط وجميع عناصر النائبة لأرقام الصفحات الخاصة بالأطفال. تعني عناصر النائبة للأطفال أنها موجودة على الشرائح التابعة. الشرائح التابعة تستخدم وتعتمد على شريحة التخطيط. |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | يغيّر رؤية عنصر نائبي رقم الصفحة للشرائح. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط وسيط القالب الـ n إلى مؤشر ضعيف (بدلاً من المشترك). يتيح تحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحّرّ جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [BaseSlideHeaderFooterManager](../baseslideheaderfootermanager/)
* فئة [ILayoutSlideHeaderFooterManager](../ilayoutslideheaderfootermanager/)
* مساحة الاسم [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)