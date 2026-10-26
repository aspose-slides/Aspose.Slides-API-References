---
title: ITable
second_title: مرجع API Aspose.Slides للغة C++
description: يمثل جدولًا على شريحة.
type: docs
weight: 4018
url: /ar/aspose.slides/itable/
---
## فئة ITable

يمثل جدولًا على الشريحة.

```cpp
class ITable : public virtual Aspose::Slides::IGraphicalObject,
               public Aspose::Slides::IBulkTextFormattable
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | يضيف عنصر نائب جديد إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين رغم أنه وفقًا لـ IEC 60559:1989 فإن NaN ليست مساوية لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين رغم أنه وفقًا لـ IEC 60559:1989 فإن NaN ليست مساوية لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | يعيد النص البديل المرتبط بشكيلة. اقرأ [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | يعيد عنوان النص البديل المرتبط بشكيلة. اقرأ [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | تحدد الخاصية كيفية عرض الشكيلة في وضع العرض بالأبيض والأسود. اقرأ [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_Column](./get_column/)(**int32_t**) | يعيد عمودًا عند الفهرس المحدد. للقراءة فقط [Aspose::Slides::IColumn](../icolumn/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumnCollection](../icolumncollection/)\> [get_Columns](./get_columns/)() | يعيد مجموعة الأعمدة. للقراءة فقط [IColumnCollection](../icolumncollection/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | يعيد عدد مواقع الاتصال على الشكيلة. للقراءة فقط **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | يعيد بيانات مخصصة للشكيلة. للقراءة فقط [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | يعيد كائن [EffectFormat](../effectformat/) الذي يحتوي على تأثيرات البكسل المطبقة على شكيلة. للقراءة فقط [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | يعيد كائن [FillFormat](../fillformat/) الذي يحتوي على خصائص تنسيق التعبئة للشكيلة. للقراءة فقط [IFillFormat](../ifillformat/). |
| virtual **bool** [get_FirstCol](./get_firstcol/)() | يحدد ما إذا كان يجب رسم العمود الأول من الجدول بتنسيق خاص. قراءة **bool**. |
| virtual **bool** [get_FirstRow](./get_firstrow/)() | يحدد ما إذا كان يجب رسم الصف الأول من الجدول بتنسيق خاص. قراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | يعيد خصائص إطار الشكيلة. اقرأ [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | يعيد أقفال الشكيلة. للقراءة فقط [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | يحصل على ارتفاع الشكيلة، مقاسًا بالنقاط. قراءة **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | يحدد ما إذا كانت الشكيلة مخفية. قراءة **bool**. |
| virtual **bool** [get_HorizontalBanding](./get_horizontalbanding/)() | يحدد ما إذا كان يجب رسم الصفوف الزوجية بتنسيق مختلف. قراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | يعيد الرابط التشعبي المحدد للنقر بالفأرة. اقرأ [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | مدير الروابط التشعبية للقراءة فقط [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | يعيد الرابط التشعبي المحدد للتمرير فوق الفأرة. اقرأ [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | يحصل على خيار 'Mark as decorative' قراءة/كتابة **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | يحدد ما إذا كانت الشكيلة مجموعة. للقراءة فقط **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | يحدد ما إذا كانت الشكيلة TextHolder. للقراءة فقط **bool**. |
| virtual **bool** [get_LastCol](./get_lastcol/)() | يحدد ما إذا كان يجب رسم العمود الأخير من الجدول بتنسيق خاص. قراءة **bool**. |
| virtual **bool** [get_LastRow](./get_lastrow/)() | يحدد ما إذا كان يجب رسم الصف الأخير من الجدول بتنسيق خاص. قراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | يعيد كائن [LineFormat](../lineformat/) الذي يحتوي على خصائص تنسيق الخط للشكيلة. للقراءة فقط [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | يعيد اسم الشكيلة. اقرأ [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | يعيد معرفًا فريدًا على مستوى الشريحة يبقى ثابتًا طوال عمر الشكيلة ويسمح لبرنامج PowerPoint أو كود التفاعل بالمرجع إلى الشكيلة بأمان من أي مكان في المستند. للقراءة فقط **uint32_t**. راجع أيضًا [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | يعيد كائن [GroupShape](../groupshape/) الأب إذا كانت الشكيلة مجموعة. وإلا يعيد null. للقراءة فقط [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | يعيد العنصر النائب للشكيلة. للقراءة فقط [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | يعيد العرض التقديمي. للقراءة فقط [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | يعيد خصائص إطار الشكيلة الخام. اقرأ [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_RightToLeft](./get_righttoleft/)() | يحدد ما إذا كان للجدول ترتيب قراءة من اليمين إلى اليسار. قراءة **bool**. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | يعيد عدد درجات دوران الشكيلة المحددة حول محور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس عقارب الساعة. قراءة **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_Row](./get_row/)(**int32_t**) | يعيد صفًا عند الفهرس المحدد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRowCollection](../irowcollection/)\> [get_Rows](./get_rows/)() | يعيد مجموعة الصفوف. للقراءة فقط [IRowCollection](../irowcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | يعيد أقفال الشكيلة. للقراءة فقط [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | يعيد الشريحة الأساسية. للقراءة فقط [IBaseSlide](../ibaseslide/). |
| virtual [TableStylePreset](../tablestylepreset/) [get_StylePreset](./get_stylepreset/)() | يحصل أو يعيّن نمط الجدول المدمج. اقرأ [TableStylePreset](../tablestylepreset/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITableFormat](../itableformat/)\> [get_TableFormat](./get_tableformat/)() | يعيد كائن [TableFormat](../tableformat/) الذي يحتوي على خصائص تنسيق لهذا الجدول. للقراءة فقط [ITableFormat](../itableformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | يعيد كائن [ThreeDFormat](../threedformat/) الذي يحتوي على خصائص تنسيق الخط للشكيلة. للقراءة فقط [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | يعيد معرفًا داخليًا على مستوى العرض التقديمي مخصصًا لاستخدام الإضافات أو الكود الآخر. بما أن هذه القيمة يمكن أن يعيد تعيينها المستخدم أو برمجيًا، فلا يجب اعتبارها مفتاحًا فريدًا دائمًا. للقراءة فقط **uint32_t**. راجع أيضًا [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **bool** [get_VerticalBanding](./get_verticalbanding/)() | يحدد ما إذا كان يجب رسم الأعمدة الزوجية بتنسيق مختلف. قراءة **bool**. |
| virtual **float** [get_Width](../ishape/get_width/)() | يحصل على عرض الشكيلة، مقاسًا بالنقاط. قراءة **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | يحصل على الإحداثي السيني للزاوية العليا اليسرى للشكيلة، مقاسًا بالنقاط. قراءة **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | يحصل على الإحداثي الصادي للزاوية العليا اليسرى للشكيلة، مقاسًا بالنقاط. قراءة **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | يعيد موضع الشكيلة في ترتيب z. Shapes[0] يعيد الشكيلة في الخلف، وShapes[Shapes.Count - 1] يعيد الشكيلة في المقدمة. للقراءة فقط **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | يعيد شكيلة عنصر نائب أساسية (شكيلة من التخطيط و/أو الشريحة الرئيسية التي يرث منها الشكل الحالي). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | يعيد مصغّر الشكيلة. النوع الافتراضي هو حدود مصغّر الشكيلة [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | يعيد مصغّر الشكيلة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل نداء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) | يعيد الخلية عند فهارس العمود والصف المحددين. للقراءة فقط [ICell](../icell/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ بيان القفل C# lock(). استدعِه مباشرة أو استخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [MergeCells](./mergecells/)([System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, **bool**) | يدمج الخلايا المجاورة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع بنى البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنشئ نسخة. لا ينسخ شيئًا فعليًا، يهيء كائنًا جديدًا ويمكّن النسخ للأنواع الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | معامل الإسناد. لا ينسخ شيئًا فعليًا، يهيء كائنًا جديدًا ويمكّن النسخ للأنواع الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | يحدد أن هذه الشكيلة ليست عنصرًا نائبًا. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | يضبط النص البديل المرتبط بشكيلة. اكتب [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | يضبط عنوان النص البديل المرتبط بشكيلة. اكتب [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | تحدد الخاصية كيفية عرض الشكيلة في وضع العرض بالأبيض والأسود. اكتب [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_FirstCol](./set_firstcol/)(**bool**) | يحدد ما إذا كان يجب رسم العمود الأول من الجدول بتنسيق خاص. اكتب **bool**. |
| virtual void [set_FirstRow](./set_firstrow/)(**bool**) | يحدد ما إذا كان يجب رسم الصف الأول من الجدول بتنسيق خاص. اكتب **bool**. |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | يضبط خصائص إطار الشكيلة. اكتب [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | يضبط ارتفاع الشكيلة، مقاسًا بالنقاط. اكتب **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | يحدد ما إذا كانت الشكيلة مخفية. اكتب **bool**. |
| virtual void [set_HorizontalBanding](./set_horizontalbanding/)(**bool**) | يحدد ما إذا كان يجب رسم الصفوف الزوجية بتنسيق مختلف. اكتب **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | يضبط الرابط التشعبي المحدد للنقر بالفأرة. اكتب [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | يضبط الرابط التشعبي المحدد للتمرير فوق الفأرة. اكتب [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | يضبط خيار 'Mark as decorative' قراءة/كتابة **bool**. |
| virtual void [set_LastCol](./set_lastcol/)(**bool**) | يحدد ما إذا كان يجب رسم العمود الأخير من الجدول بتنسيق خاص. اكتب **bool**. |
| virtual void [set_LastRow](./set_lastrow/)(**bool**) | يحدد ما إذا كان يجب رسم الصف الأخير من الجدول بتنسيق خاص. اكتب **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | يضبط اسم الشكيلة. اكتب [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | يضبط خصائص إطار الشكيلة الخام. اكتب [IShapeFrame](../ishapeframe/). |
| virtual void [set_RightToLeft](./set_righttoleft/)(**bool**) | يحدد ما إذا كان للجدول ترتيب قراءة من اليمين إلى اليسار. اكتب **bool**. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | يضبط عدد درجات دوران الشكيلة المحددة حول محور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس عقارب الساعة. اكتب **float**. |
| virtual void [set_StylePreset](./set_stylepreset/)([TableStylePreset](../tablestylepreset/)) | يحصل أو يعيّن نمط الجدول المدمج. اكتب [TableStylePreset](../tablestylepreset/). |
| virtual void [set_VerticalBanding](./set_verticalbanding/)(**bool**) | يحدد ما إذا كان يجب رسم الأعمدة الزوجية بتنسيق مختلف. اكتب **bool**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | يضبط عرض الشكيلة، مقاسًا بالنقاط. اكتب **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | يضبط الإحداثي السيني للزاوية العليا اليسرى للشكيلة، مقاسًا بالنقاط. اكتب **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | يضبط الإحداثي الصادي للزاوية العليا اليسرى للشكيلة، مقاسًا بالنقاط. اكتب **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي n كإشارة ضعيفة (بدلاً من مشترك). يتيح تبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\>) | يضبط خصائص تنسيق الجزء المحدد لجميع أجزاء العنصر. |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormat](../iparagraphformat/)\>) | يضبط خصائص تنسيق الفقرة المحددة لجميع فقرات العنصر. |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormat](../itextframeformat/)\>) | يضبط خصائص تنسيق إطار النص المحددة لجميع إطارات النص للعنصر. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ بيان إلغاء القفل C# lock(). استدعِه مباشرة أو استخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | يحفظ محتوى [Shape](../shape/) كملف SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | يحفظ محتوى [Shape](../shape/) كملف SVG. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## أنظر أيضًا

* الفئة [IGraphicalObject](../igraphicalobject/)
* الفئة [IBulkTextFormattable](../ibulktextformattable/)
* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)