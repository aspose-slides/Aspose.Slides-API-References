---
title: LineFormat
second_title: مرجع Aspose.Slides للغة C++
description: يمثل تنسيق الخط.
type: docs
weight: 4382
url: /ar/aspose.slides/lineformat/
---
## LineFormat فئة

يمثل تنسيق خط.

```cpp
class LineFormat : public Aspose::Slides::PVIObject,
                   public Aspose::Slides::ILineFormat
```

## الطرق

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override |  |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\>) override | يحدد ما إذا كان مثليا [LineFormat](./) متساويين. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر قيمتي NaN متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر قيمتي NaN متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [LineAlignment](../linealignment/) [get_Alignment](./get_alignment/)() override | يعيد محاذاة الخط. اقرأ [LineAlignment](../linealignment/). |
| [LineArrowheadLength](../linearrowheadlength/) [get_BeginArrowheadLength](./get_beginarrowheadlength/)() override | يعيد طول رأس السهم في بداية الخط. اقرأ [LineArrowheadLength](../linearrowheadlength/). |
| [LineArrowheadStyle](../linearrowheadstyle/) [get_BeginArrowheadStyle](./get_beginarrowheadstyle/)() override | يعيد نمط رأس السهم في بداية الخط. اقرأ [LineArrowheadStyle](../linearrowheadstyle/). |
| [LineArrowheadWidth](../linearrowheadwidth/) [get_BeginArrowheadWidth](./get_beginarrowheadwidth/)() override | يعيد عرض رأس السهم في بداية الخط. اقرأ [LineArrowheadWidth](../linearrowheadwidth/). |
| [LineCapStyle](../linecapstyle/) [get_CapStyle](./get_capstyle/)() override | يعيد نمط غطاء الخط. اقرأ [LineCapStyle](../linecapstyle/). |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CustomDashPattern](./get_customdashpattern/)() override | يعيد نمط النقاط المتقطعة المخصص. اقرأ **float**[]. |
| [LineDashStyle](../linedashstyle/) [get_DashStyle](./get_dashstyle/)() override | يعيد نمط الخط المتقطع. اقرأ [LineDashStyle](../linedashstyle/). |
| [LineArrowheadLength](../linearrowheadlength/) [get_EndArrowheadLength](./get_endarrowheadlength/)() override | يعيد طول رأس السهم في نهاية الخط. اقرأ [LineArrowheadLength](../linearrowheadlength/). |
| [LineArrowheadStyle](../linearrowheadstyle/) [get_EndArrowheadStyle](./get_endarrowheadstyle/)() override | يعيد نمط رأس السهم في نهاية الخط. اقرأ [LineArrowheadStyle](../linearrowheadstyle/). |
| [LineArrowheadWidth](../linearrowheadwidth/) [get_EndArrowheadWidth](./get_endarrowheadwidth/)() override | يعيد عرض رأس السهم في نهاية الخط. اقرأ [LineArrowheadWidth](../linearrowheadwidth/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFillFormat](../ilinefillformat/)\> [get_FillFormat](./get_fillformat/)() override | يعيد تنسيق تعبئة الخط. للقراءة فقط [ILineFillFormat](../ilinefillformat/). |
| **bool** [get_IsFormatNotDefined](./get_isformatnotdefined/)() override | يعيد true إذا لم يتم تعريف تنسيق الخط (كما عند إنشائه، القيمة الافتراضية). **bool** للقراءة فقط. |
| [LineJoinStyle](../linejoinstyle/) [get_JoinStyle](./get_joinstyle/)() override | يعيد نمط وصل الخطوط. اقرأ [LineJoinStyle](../linejoinstyle/). |
| **float** [get_MiterLimit](./get_miterlimit/)() override | يعيد حد القطع للخط. اقرأ **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | يعيد كائن Parent_Immediate. للقراءة فقط [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | يعيد الأب [IPresentationComponent](../ipresentationcomponent/). للقراءة فقط [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISketchFormat](../isketchformat/)\> [get_SketchFormat](./get_sketchformat/)() override | يعيد تنسيق الرسم للخط. للقراءة فقط [ILineFillFormat](../ilinefillformat/). |
| [LineStyle](../linestyle/) [get_Style](./get_style/)() override | يعيد نمط الخط. اقرأ [LineStyle](../linestyle/). |
| **double** [get_Width](./get_width/)() override | يعيد عرض الخط. اقرأ **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد الإشارة المرتبط بالكائن. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [GetEffective](./geteffective/)() override | يحصل على بيانات تنسيق الخط الفعلي مع تطبيق الوراثة. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | يعيد رمز التجزئة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مشابه لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثالا من النوع الموضّح بـ targetType. مشابه لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة lock() في C#. استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع البنى الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعلاً، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعلاً، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالإشارة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلص عداد الإشارة المشترك بالقيمة المحددة. |
| void [set_Alignment](./set_alignment/)([LineAlignment](../linealignment/)) override | يضبط محاذاة الخط. اكتب [LineAlignment](../linealignment/). |
| void [set_BeginArrowheadLength](./set_beginarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) override | يضبط طول رأس السهم في بداية الخط. اكتب [LineArrowheadLength](../linearrowheadlength/). |
| void [set_BeginArrowheadStyle](./set_beginarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) override | يضبط نمط رأس السهم في بداية الخط. اكتب [LineArrowheadStyle](../linearrowheadstyle/). |
| void [set_BeginArrowheadWidth](./set_beginarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) override | يضبط عرض رأس السهم في بداية الخط. اكتب [LineArrowheadWidth](../linearrowheadwidth/). |
| void [set_CapStyle](./set_capstyle/)([LineCapStyle](../linecapstyle/)) override | يضبط نمط غطاء الخط. اكتب [LineCapStyle](../linecapstyle/). |
| void [set_CustomDashPattern](./set_customdashpattern/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | يضبط نمط النقاط المتقطعة المخصص. اكتب **float**[]. |
| void [set_DashStyle](./set_dashstyle/)([LineDashStyle](../linedashstyle/)) override | يضبط نمط الخط المتقطع. اكتب [LineDashStyle](../linedashstyle/). |
| void [set_EndArrowheadLength](./set_endarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) override | يضبط طول رأس السهم في نهاية الخط. اكتب [LineArrowheadLength](../linearrowheadlength/). |
| void [set_EndArrowheadStyle](./set_endarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) override | يضبط نمط رأس السهم في نهاية الخط. اكتب [LineArrowheadStyle](../linearrowheadstyle/). |
| void [set_EndArrowheadWidth](./set_endarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) override | يضبط عرض رأس السهم في نهاية الخط. اكتب [LineArrowheadWidth](../linearrowheadwidth/). |
| void [set_JoinStyle](./set_joinstyle/)([LineJoinStyle](../linejoinstyle/)) override | يضبط نمط وصل الخطوط. اكتب [LineJoinStyle](../linejoinstyle/). |
| void [set_MiterLimit](./set_miterlimit/)(**float**) override | يضبط حد القطع للخط. اكتب **float**. |
| void [set_Style](./set_style/)([LineStyle](../linestyle/)) override | يضبط نمط الخط. اكتب [LineStyle](../linestyle/). |
| void [set_Width](./set_width/)(**double**) override | يضبط عرض الخط. اكتب **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلص عداد الإشارة المشترك ويعيد قيمته. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة lock() في C#. استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزداد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع البنى الداخلية. |
## انظر أيضًا

* الفئة [PVIObject](../pviobject/)
* الفئة [ILineFormat](../ilineformat/)
* المساحة الاسمية [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)