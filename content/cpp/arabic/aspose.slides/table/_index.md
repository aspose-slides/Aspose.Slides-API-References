---
title: Table
second_title: مرجع API Aspose.Slides للـ C++
description: يمثل جدولًا على شريحة.
type: docs
weight: 5409
url: /ar/aspose.slides/table/
---
## فئة الجدول

يمثل جدولًا على شريحة.

```cpp
class Table : public Aspose::Slides::GraphicalObject,
              public Aspose::Slides::ITable
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى عنصر محدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقاط العائمة بأسلوب C# حيث يُعتبر NaNان اثنان متساويين على الرغم من أن وفقًا لـ IEC 60559:1989 NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقاط العائمة بأسلوب C# حيث يُعتبر NaNان اثنان متساويين على الرغم من أن وفقًا لـ IEC 60559:1989 NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لغايات داخلية فقط. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | يعيد النص البديل المرتبط بشكل. قراءة [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | يعيد عنوان النص البديل المرتبط بشكل. قراءة [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | تحدد الخاصية كيفية عرض الشكل في وضعية الأبيض والأسود. قراءة [Slides::BlackWhiteMode](../blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_Column](./get_column/)(**int32_t**) override | يعيد عمودًا عند الفهرس المحدد. للقراءة فقط [Aspose::Slides::IColumn](../icolumn/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumnCollection](../icolumncollection/)\> [get_Columns](./get_columns/)() override | يعيد مجموعة الأعمدة. للقراءة فقط [IColumnCollection](../icolumncollection/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | يعيد عدد نقاط الاتصال على الشكل. للقراءة فقط **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | يعيد بيانات مخصصة للشكل. للقراءة فقط [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | يعيد كائن [EffectFormat](../effectformat/) الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يُعيد null لأنواع معينة من الأشكال التي لا تملك خصائص تأثير. للقراءة فقط [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | يعيد كائن [TableFormat::get_FillFormat](../tableformat/get_fillformat/) يحتوي على تنسيق التعبئة لـ [Table](./). للقراءة فقط [IFillFormat](../ifillformat/). |
| **bool** [get_FirstCol](./get_firstcol/)() override | يحدد ما إذا كان يجب رسم العمود الأول من الجدول بتنسيق خاص. قراءة **bool**. |
| **bool** [get_FirstRow](./get_firstrow/)() override | يحدد ما إذا كان يجب رسم الصف الأول من الجدول بتنسيق خاص. قراءة **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | يعيد خصائص إطار الشكل. قراءة [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | يعيد أقفال الشكل. للقراءة فقط [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | يحصل على ارتفاع الشكل، مقاسًا بالنقاط. قراءة **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | يحدد ما إذا كان الشكل مخفيًا. قراءة **bool**. |
| **bool** [get_HorizontalBanding](./get_horizontalbanding/)() override | يحدد ما إذا كان يجب رسم الصفوف الزوجية بتنسيق مختلف. قراءة **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | يعيد الرابط التشعبي المحدد للنقر بالماوس. قراءة [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | يعيد مدير الروابط التشعبية. للقراءة فقط [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | يعيد الرابط التشعبي المحدد للتحويم بالماوس. قراءة [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | يحصل على خيار 'وضع علامة كزخرف'. قراءة/كتابة **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | يحدد ما إذا كان الشكل مجموعة. للقراءة فقط **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | يحدد ما إذا كان الشكل TextHolder_PPT. للقراءة فقط **bool**. |
| **bool** [get_LastCol](./get_lastcol/)() override | يحدد ما إذا كان يجب رسم العمود الأخير من الجدول بتنسيق خاص. قراءة **bool**. |
| **bool** [get_LastRow](./get_lastrow/)() override | يحدد ما إذا كان يجب رسم الصف الأخير من الجدول بتنسيق خاص. قراءة **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | يعيد كائن [LineFormat](../lineformat/) الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: قد يُعيد null لأنواع معينة من الأشكال التي لا تملك خصائص الخط. للقراءة فقط [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | يعيد اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قراءة [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | يعيد معرفًا فريدًا يخص الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو رمز التفاعل بالإشارة إلى الشكل من أي مكان في المستند. للقراءة فقط **uint32_t**. انظر أيضًا [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | يعيد كائن [GroupShape](../groupshape/) الأب إذا كان الشكل مجموعة. وإلا يعيد null. للقراءة فقط [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | يعيد العنصر النائب للشكل. يعيد null إذا لم يكن للشكل عنصر نائب. للقراءة فقط [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | يعيد العرض الرئيسي للشرحة. للقراءة فقط [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | يعيد خصائص إطار الشكل الخام. قراءة [IShapeFrame](../ishapeframe/). |
| **bool** [get_RightToLeft](./get_righttoleft/)() override | يحدد ما إذا كان للجدول ترتيب قراءة من اليمين إلى اليسار. قراءة **bool**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | يعيد عدد درجات دوران الشكل المحدد حول محور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه العقارب. قراءة **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_Row](./get_row/)(**int32_t**) override | يعيد صفًا عند الفهرس المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRowCollection](../irowcollection/)\> [get_Rows](./get_rows/)() override | يعيد مجموعة الصفوف. للقراءة فقط [IRowCollection](../irowcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | يعيد أقفال الشكل. للقراءة فقط [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | يعيد الشريحة الأم للشكل. للقراءة فقط [IBaseSlide](../ibaseslide/). |
| [TableStylePreset](../tablestylepreset/) [get_StylePreset](./get_stylepreset/)() override | يحصل على نمط الجدول المدمج. قراءة [TableStylePreset](../tablestylepreset/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITableFormat](../itableformat/)\> [get_TableFormat](./get_tableformat/)() override | يعيد كائن [TableFormat](../tableformat/) الذي يحتوي على خصائص التنسيق لهذا الجدول. للقراءة فقط [ITableFormat](../itableformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | يعيد كائن [ThreeDFormat](../threedformat/) الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يُعيد null لأنواع معينة من الأشكال التي لا تملك خصائص ثلاثية الأبعاد. للقراءة فقط [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | يعيد معرفًا داخليًا يخص العرض يُقصد به الاستخدام من قبل الإضافات أو أكواد أخرى. نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، فلا ينبغي التعامل معها كمفتاح فريد دائم. للقراءة فقط **uint32_t**. انظر أيضًا [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **bool** [get_VerticalBanding](./get_verticalbanding/)() override | يحدد ما إذا كان يجب رسم الأعمدة الزوجية بتنسيق مختلف. قراءة **bool**. |
| **float** [get_Width](../shape/get_width/)() override | يحصل على عرض الشكل، مقاسًا بالنقاط. قراءة **float**. |
| **float** [get_X](../shape/get_x/)() override | يحصل على إحداثي x للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. قراءة **float**. |
| **float** [get_Y](../shape/get_y/)() override | يحصل على إحداثي y للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. قراءة **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | يعيد موضع الشكل في ترتيب z. Shapes[0] يعيد الشكل في الخلف من ترتيب z، و Shapes[Shapes.Count - 1] يعيد الشكل في المقدمة من ترتيب z. للقراءة فقط **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | يعيد شكلًا نائبًا أساسيًا (شكل من التخطيط و/أو شريحة الرئيسة التي يرث منها الشكل الحالي). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل بيانات عداد المرجعية المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | يعيد صورة مصغرة للشكل. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) نوع حدود الصورة المصغرة للشكل يُستخدم افتراضيًا. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | يعيد صورة مصغرة للشكل. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | يحصل على حدود الشكل البصرية المحسوبة من المحتوى المُعرض. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) override | يعيد الخلية عند فهارس العمود والصف المحددين. للقراءة فقط [Cell](../cell/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن المراقبة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [MergeCells](./mergecells/)([System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, **bool**) override | يدمج الخلايا المجاورة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع قيم مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجعية المشتركة بقيمة محددة. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | يضبط النص البديل المرتبط بالشكل. كتابة [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | يضبط عنوان النص البديل المرتبط بالشكل. كتابة [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | تحدد الخاصية كيفية عرض الشكل في وضعية الأبيض والأسود. كتابة [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_FirstCol](./set_firstcol/)(**bool**) override | يحدد ما إذا كان يجب رسم العمود الأول من الجدول بتنسيق خاص. كتابة **bool**. |
| void [set_FirstRow](./set_firstrow/)(**bool**) override | يحدد ما إذا كان يجب رسم الصف الأول من الجدول بتنسيق خاص. كتابة **bool**. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | يضبط خصائص إطار الشكل. كتابة [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | يضبط ارتفاع الشكل، مقاسًا بالنقاط. كتابة **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | يحدد ما إذا كان الشكل مخفيًا. كتابة **bool**. |
| void [set_HorizontalBanding](./set_horizontalbanding/)(**bool**) override | يحدد ما إذا كان يجب رسم الصفوف الزوجية بتنسيق مختلف. كتابة **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | يضبط الرابط التشعبي المحدد للنقر بالماوس. كتابة [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | يضبط الرابط التشعبي المحدد للتحويم بالماوس. كتابة [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | يضبط خيار 'وضع علامة كزخرف'. قراءة/كتابة **bool**. |
| void [set_LastCol](./set_lastcol/)(**bool**) override | يحدد ما إذا كان يجب رسم العمود الأخير من الجدول بتنسيق خاص. كتابة **bool**. |
| void [set_LastRow](./set_lastrow/)(**bool**) override | يحدد ما إذا كان يجب رسم الصف الأخير من الجدول بتنسيق خاص. كتابة **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | يضبط اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. كتابة [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | يضبط خصائص إطار الشكل الخام. كتابة [IShapeFrame](../ishapeframe/). |
| void [set_RightToLeft](./set_righttoleft/)(**bool**) override | يحدد ما إذا كان للجدول ترتيب قراءة من اليمين إلى اليسار. كتابة **bool**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | يضبط عدد درجات دوران الشكل المحدد حول محور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه العقارب. كتابة **float**. |
| void [set_StylePreset](./set_stylepreset/)([TableStylePreset](../tablestylepreset/)) override | يضبط نمط الجدول المدمج. كتابة [TableStylePreset](../tablestylepreset/). |
| void [set_VerticalBanding](./set_verticalbanding/)(**bool**) override | يحدد ما إذا كان يجب رسم الأعمدة الزوجية بتنسيق مختلف. كتابة **bool**. |
| void [set_Width](../shape/set_width/)(**float**) override | يضبط عرض الشكل، مقاسًا بالنقاط. كتابة **float**. |
| void [set_X](../shape/set_x/)(**float**) override | يضبط إحداثي x للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. كتابة **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | يضبط إحداثي y للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. كتابة **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي رقم n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتبديل الإشارات في الحاويات إلى وضع ضعيف. |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\>) override | يضبط خصائص تنسيق الجزء المحدد لجميع أجزاء خلايا الجدول. |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormat](../iparagraphformat/)\>) override | يضبط خصائص تنسيق الفقرة المحددة لجميع فقرات خلايا الجدول. |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormat](../itextframeformat/)\>) override | يضبط خصائص تنسيق إطار النص المحددة لجميع إطارات نص خلايا الجدول. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجعية المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجعية المشتركة. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجعية المشتركة. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن المراقبة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجعية الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجعية الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | يحفظ محتوى [Shape](../shape/) كملف SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | يحفظ محتوى [Shape](../shape/) كملف SVG. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* الفئة [GraphicalObject](../graphicalobject/)
* الفئة [ITable](../itable/)
* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)