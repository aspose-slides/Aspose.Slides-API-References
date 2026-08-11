---
title: Cell
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل خلية في جدول.
type: docs
weight: 300
url: /ar/aspose.slides/cell/
---
## فئة Cell


يمثل خلية في جدول.

```cpp
class Cell : public Aspose::Slides::IDOMObject,
             public Aspose::Slides::ICell
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع المرجع بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع القيمة بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقلد مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقلد مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **bool** [get_AnchorCenter](./get_anchorcenter/)() override | يحدد ما إذا كان مربع النص متمركزًا داخل خلية أم لا. اقرأ **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() override | يعيد الكائن [CellFormat](../cellformat/) الذي يحتوي على خصائص التنسيق لهذه الخلية. للقراءة فقط [ICellFormat](../icellformat/). |
| **int32_t** [get_ColSpan](./get_colspan/)() override | يعيد عدد أعمدة الشبكة في جدول الوالد التي يجب أن تغطيها الخلية الحالية. تسمح هذه الخاصية للخلية بأن تبدو مدمجة، حيث تمتد عبر حدود عمودية لخلايا أخرى في الجدول. للقراءة فقط **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() override | يُحصل على العمود الأول للخلية. للقراءة فقط [IColumn](../icolumn/). |
| **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() override | يعيد فهرس العمود الأول الذي تغطيه الخلية. للقراءة فقط **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() override | يُحصل على الصف الأول للخلية. للقراءة فقط [IRow](../irow/). |
| **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() override | يعيد فهرس الصف الأول الذي تغطيه الخلية. للقراءة فقط **int32_t**. |
| **double** [get_Height](./get_height/)() override | يعيد ارتفاع الخلية. للقراءة فقط **double**. |
| **bool** [get_IsMergedCell](./get_ismergedcell/)() override | يعيد true إذا كانت الخلية مدمجة مع أي خلية معدلة، وإلا false. للقراءة فقط **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | يعيد الهامش السفلي في [TextFrame](../textframe/). اقرأ **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | يعيد الهامش الأيسر في [TextFrame](../textframe/). اقرأ **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | يعيد الهامش الأيمن في [TextFrame](../textframe/). اقرأ **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | يعيد الهامش العلوي في [TextFrame](../textframe/). اقرأ **double**. |
| **double** [get_MinimalHeight](./get_minimalheight/)() override | يعيد الحد الأدنى لارتفاع الخلية. هذا مجموع الارتفاعات الدنيا لجميع الصفوف التي تغطيها الخلية. للقراءة فقط **double**. |
| **double** [get_OffsetX](./get_offsetx/)() override | يعيد المسافة من الجانب الأيسر للجدول إلى الجانب الأيسر للخلية. للقراءة فقط **double**. |
| **double** [get_OffsetY](./get_offsety/)() override | يعيد المسافة من الجانب العلوي للجدول إلى الجانب العلوي للخلية. للقراءة فقط **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | يعيد العرض التقديمي الأب للخلية. للقراءة فقط [IPresentation](../ipresentation/). |
| **int32_t** [get_RowSpan](./get_rowspan/)() override | يعيد عدد الصفوف التي تمتد عبرها الخلية المدمجة. يُستخدم هذا مع خاصية vMerge على خلايا أخرى لتحديد خلية البدء للدمج الأفقي. للقراءة فقط **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | يعيد الشريحة الأب للخلية. للقراءة فقط [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() override | يعيد الكائن [Table](../table/) الأب للخلية. للقراءة فقط [ITable](../itable/). |
| [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() override | يعيد نوع نقطة تثبيت النص. اقرأ [Slides::TextAnchorType](../textanchortype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | يعيد إطار النص للخلية. للقراءة فقط [ITextFrame](../itextframe/). |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | يعيد نوع النص العمودي. اقرأ [Slides::TextVerticalType](../textverticaltype/). |
| **double** [get_Width](./get_width/)() override | يعيد عرض الخلية. للقراءة فقط **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير عامل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_AnchorCenter](./set_anchorcenter/)(**bool**) override | يحدد ما إذا كان مربع النص متمركزًا داخل خلية أم لا. اكتب **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | يضبط الهامش السفلي في [TextFrame](../textframe/). اكتب **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | يضبط الهامش الأيسر في [TextFrame](../textframe/). اكتب **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | يضبط الهامش الأيمن في [TextFrame](../textframe/). اكتب **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | يضبط الهامش العلوي في [TextFrame](../textframe/). اكتب **double**. |
| void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) override | يضبط نوع نقطة تثبيت النص. اكتب [Slides::TextAnchorType](../textanchortype/). |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | يضبط نوع النص العمودي. اكتب [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط معامل القالب رقم n كمؤشر ضعيف (بدلاً من المشترك). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [SplitByColSpan](./splitbycolspan/)(**int32_t**) override | يقسم الخلية إلى خلتين وفقًا لفهرس العمود. |
| void [SplitByHeight](./splitbyheight/)(**double**) override | يقسم الخلية حسب الارتفاع. |
| void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) override | يقسم الخلية إلى خلتين وفقًا لفهرس الصف. |
| void [SplitByWidth](./splitbywidth/)(**double**) override | يقسم الخلية حسب العرض. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* الفئة [IDOMObject](../idomobject/)
* الفئة [ICell](../icell/)
* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)