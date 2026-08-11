---
title: ILineFormat
second_title: Aspose.Slides لمرجع API للغة C++
description: يمثل تنسيق الخط.
type: docs
weight: 2757
url: /ar/aspose.slides/ilineformat/
---
## فئة ILineFormat

يمثل تنسيق الخط.

```cpp
class ILineFormat : public Aspose::Slides::ILineParamSource
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](./)\>) | يحدد ما إذا كانت مثيلات [LineFormat](../lineformat/) الاثنين متساوية. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يُحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين رغم أن IEC 60559:1989 تنص على أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يُحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين رغم أن IEC 60559:1989 تنص على أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [LineAlignment](../linealignment/) [get_Alignment](./get_alignment/)() | يرجع محاذاة الخط. اقرأ [LineAlignment](../linealignment/). |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_BeginArrowheadLength](./get_beginarrowheadlength/)() | يرجع طول رأس السهم في بداية الخط. اقرأ [LineArrowheadLength](../linearrowheadlength/). |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_BeginArrowheadStyle](./get_beginarrowheadstyle/)() | يرجع نمط رأس السهم في بداية الخط. اقرأ [LineArrowheadStyle](../linearrowheadstyle/). |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_BeginArrowheadWidth](./get_beginarrowheadwidth/)() | يرجع عرض رأس السهم في بداية الخط. اقرأ [LineArrowheadWidth](../linearrowheadwidth/). |
| virtual [LineCapStyle](../linecapstyle/) [get_CapStyle](./get_capstyle/)() | يرجع نمط غطاء الخط. اقرأ [LineCapStyle](../linecapstyle/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CustomDashPattern](./get_customdashpattern/)() | يرجع نمط الشرط المتقطع المخصص. اقرأ **float**[]. |
| virtual [LineDashStyle](../linedashstyle/) [get_DashStyle](./get_dashstyle/)() | يرجع نمط الشرط المتقطع للخط. اقرأ [LineDashStyle](../linedashstyle/). |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_EndArrowheadLength](./get_endarrowheadlength/)() | يرجع طول رأس السهم في نهاية الخط. اقرأ [LineArrowheadLength](../linearrowheadlength/). |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_EndArrowheadStyle](./get_endarrowheadstyle/)() | يرجع نمط رأس السهم في نهاية الخط. اقرأ [LineArrowheadStyle](../linearrowheadstyle/). |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_EndArrowheadWidth](./get_endarrowheadwidth/)() | يرجع عرض رأس السهم في نهاية الخط. اقرأ [LineArrowheadWidth](../linearrowheadwidth/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFillFormat](../ilinefillformat/)\> [get_FillFormat](./get_fillformat/)() | يرجع تنسيق تعبئة الخط. للقراءة فقط [ILineFillFormat](../ilinefillformat/). |
| virtual **bool** [get_IsFormatNotDefined](./get_isformatnotdefined/)() | يرجع true إذا لم يُعرّف تنسيق الخط (كما تم إنشاؤه حديثًا، الافتراضي). للقراءة فقط **bool**. |
| virtual [LineJoinStyle](../linejoinstyle/) [get_JoinStyle](./get_joinstyle/)() | يرجع نمط وصل الخطوط. اقرأ [LineJoinStyle](../linejoinstyle/). |
| virtual **float** [get_MiterLimit](./get_miterlimit/)() | يرجع حد القطع للخط. اقرأ **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISketchFormat](../isketchformat/)\> [get_SketchFormat](./get_sketchformat/)() | يرجع تنسيق الرسم التخطيطي للخط. للقراءة فقط [ISketchFormat](../isketchformat/). |
| virtual [LineStyle](../linestyle/) [get_Style](./get_style/)() | يرجع نمط الخط. اقرأ [LineStyle](../linestyle/). |
| virtual **double** [get_Width](./get_width/)() | يرجع عرض الخط. اقرأ **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبطة بالكائن. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [GetEffective](./geteffective/)() | يحصل على بيانات تنسيق الخط الفعّالة مع تطبيق الوراثة. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ عملية القفل في تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا حقًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا حقًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_Alignment](./set_alignment/)([LineAlignment](../linealignment/)) | يضبط محاذاة الخط. اكتب [LineAlignment](../linealignment/). |
| virtual void [set_BeginArrowheadLength](./set_beginarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) | يضبط طول رأس السهم في بداية الخط. اكتب [LineArrowheadLength](../linearrowheadlength/). |
| virtual void [set_BeginArrowheadStyle](./set_beginarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) | يضبط نمط رأس السهم في بداية الخط. اكتب [LineArrowheadStyle](../linearrowheadstyle/). |
| virtual void [set_BeginArrowheadWidth](./set_beginarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) | يضبط عرض رأس السهم في بداية الخط. اكتب [LineArrowheadWidth](../linearrowheadwidth/). |
| virtual void [set_CapStyle](./set_capstyle/)([LineCapStyle](../linecapstyle/)) | يضبط نمط غطاء الخط. اكتب [LineCapStyle](../linecapstyle/). |
| virtual void [set_CustomDashPattern](./set_customdashpattern/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) | يضبط نمط الشرط المتقطع المخصص. اكتب **float**[]. |
| virtual void [set_DashStyle](./set_dashstyle/)([LineDashStyle](../linedashstyle/)) | يضبط نمط الشرط المتقطع للخط. اكتب [LineDashStyle](../linedashstyle/). |
| virtual void [set_EndArrowheadLength](./set_endarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) | يضبط طول رأس السهم في نهاية الخط. اكتب [LineArrowheadLength](../linearrowheadlength/). |
| virtual void [set_EndArrowheadStyle](./set_endarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) | يضبط نمط رأس السهم في نهاية الخط. اكتب [LineArrowheadStyle](../linearrowheadstyle/). |
| virtual void [set_EndArrowheadWidth](./set_endarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) | يضبط عرض رأس السهم في نهاية الخط. اكتب [LineArrowheadWidth](../linearrowheadwidth/). |
| virtual void [set_JoinStyle](./set_joinstyle/)([LineJoinStyle](../linejoinstyle/)) | يضبط نمط وصل الخطوط. اكتب [LineJoinStyle](../linejoinstyle/). |
| virtual void [set_MiterLimit](./set_miterlimit/)(**float**) | يضبط حد القطع للخط. اكتب **float**. |
| virtual void [set_Style](./set_style/)([LineStyle](../linestyle/)) | يضبط نمط الخط. اكتب [LineStyle](../linestyle/). |
| virtual void [set_Width](./set_width/)(**double**) | يضبط عرض الخط. اكتب **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط المتغيّر القالبي الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد المرجع المشترك ويعيده. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ عملية فك القفل في تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [ILineParamSource](../ilineparamsource/)
* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)