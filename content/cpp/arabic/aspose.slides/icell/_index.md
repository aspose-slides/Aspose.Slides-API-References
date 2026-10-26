---
title: ICell
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل خلية في جدول.
type: docs
weight: 1639
url: /ar/aspose.slides/icell/
---
## ICell فئة

يمثل خلية في جدول.

```cpp
class ICell : public Aspose::Slides::ISlideComponent
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سيمنتيكيات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع مرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 ينص على أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 ينص على أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual **bool** [get_AnchorCenter](./get_anchorcenter/)() | يحدد ما إذا كان مربع النص مركّزًا داخل خلية أم لا. قراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() | يعيد كائن [CellFormat](../cellformat/) الذي يحتوي على خصائص التنسيق لهذه الخلية. قراءة فقط [ICellFormat](../icellformat/). |
| virtual **int32_t** [get_ColSpan](./get_colspan/)() | يعيد عدد أعمدة الشبكة في شبكة الجدول الأصلية التي ستمتد عبرها الخلية الحالية. تسمح هذه الخاصية للخلية بأن تظهر كأنها مدمجة، حيث تمتد عبر الحدود العمودية لخلايا أخرى في الجدول. قراءة فقط **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() | يحصل على العمود الأول للخلية. قراءة فقط [IColumn](../icolumn/). |
| virtual **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() | يعيد فهرس العمود الأول الذي تغطيه الخلية. قراءة فقط **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() | يحصل على الصف الأول للخلية. قراءة فقط [IRow](../irow/). |
| virtual **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() | يعيد فهرس الصف الأول الذي تغطيه الخلية. قراءة فقط **int32_t**. |
| virtual **double** [get_Height](./get_height/)() | يعيد ارتفاع الخلية. قراءة فقط **double**. |
| virtual **bool** [get_IsMergedCell](./get_ismergedcell/)() | يعيد true إذا كانت الخلية مدمجة مع أي خلية معدّلة، وإلا false. قراءة فقط **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | يعيد الهامش السفلي في [TextFrame](../textframe/). قراءة **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | يعيد الهامش الأيسر في [TextFrame](../textframe/). قراءة **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | يعيد الهامش الأيمن في [TextFrame](../textframe/). قراءة **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | يعيد الهامش العلوي في [TextFrame](../textframe/). قراءة **double**. |
| virtual **double** [get_MinimalHeight](./get_minimalheight/)() | يعيد الحد الأدنى لارتفاع الخلية. هذا هو مجموع الارتفاعات الدنيا لجميع الصفوف المغطاة بالخلية. قراءة فقط **double**. |
| virtual **double** [get_OffsetX](./get_offsetx/)() | يعيد المسافة من الجانب الأيسر للجدول إلى الجانب الأيسر للخلية. قراءة فقط **double**. |
| virtual **double** [get_OffsetY](./get_offsety/)() | يعيد المسافة من الجانب العلوي للجدول إلى الجانب العلوي للخلية. قراءة فقط **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | يعيد العرض التقديمي. قراءة فقط [IPresentation](../ipresentation/). |
| virtual **int32_t** [get_RowSpan](./get_rowspan/)() | يعيد عدد الصفوف التي تمتد عبرها الخلية المدمجة. يُستخدم ذلك مع سمة vMerge في خلايا أخرى لتحديد خلية البدء للدمج الأفقي. قراءة فقط **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | يعيد الشريحة الأساسية. قراءة فقط [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() | يعيد كائن [Table](../table/) الأب لخلية. قراءة فقط [ITable](../itable/). |
| virtual [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() | يعيد نوع مرساة النص. قراءة [Slides::TextAnchorType](../textanchortype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | يعيد إطار النص للخلية. قراءة فقط [ITextFrame](../itextframe/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | يعيد نوع النص العمودي. قراءة [Slides::TextVerticalType](../textverticaltype/). |
| virtual **double** [get_Width](./get_width/)() | يعيد عرض الخلية. قراءة فقط **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثلاً للنوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصّصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن نوع القيمة بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_AnchorCenter](./set_anchorcenter/)(**bool**) | يحدد ما إذا كان مربع النص مركّزًا داخل خلية أم لا. كتابة **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | يضبط الهامش السفلي في [TextFrame](../textframe/). كتابة **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | يضبط الهامش الأيسر في [TextFrame](../textframe/). كتابة **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | يضبط الهامش الأيمن في [TextFrame](../textframe/). كتابة **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | يضبط الهامش العلوي في [TextFrame](../textframe/). كتابة **double**. |
| virtual void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) | يضبط نوع مرساة النص. كتابة [Slides::TextAnchorType](../textanchortype/). |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | يضبط نوع النص العمودي. كتابة [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual void [SplitByColSpan](./splitbycolspan/)(**int32_t**) | يقسم الخلية إلى خليتين حسب فهرس العمود. |
| virtual void [SplitByHeight](./splitbyheight/)(**double**) | يقسم الخلية حسب الارتفاع. |
| virtual void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) | يقسم الخلية إلى خليتين حسب فهرس الصف. |
| virtual void [SplitByWidth](./splitbywidth/)(**double**) | يقسم الخلية حسب العرض. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [ISlideComponent](../islidecomponent/)
* فضاء الاسم [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)