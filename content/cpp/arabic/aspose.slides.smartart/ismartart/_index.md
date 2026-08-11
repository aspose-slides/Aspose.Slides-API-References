---
title: ISmartArt
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل مخطط SmartArt.
type: docs
weight: 1
url: /ar/aspose.slides.smartart/ismartart/
---
## ISmartArt فئة

يمثل [SmartArt](../smartart/) مخططًا.

```cpp
class ISmartArt : public virtual Aspose::Slides::IGraphicalObject
```

## طرق

| الطريقة | الوصف |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | يضيف عنصرًا نائبيًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يُحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبر NaNانين متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يُحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبر NaNانين متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_AllNodes](./get_allnodes/)() | يعيد مجموعات من جميع العقد في كائن [SmartArt](../smartart/). للقراءة فقط [ISmartArtNodeCollection](../ismartartnodecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | يعيد النص البديل المرتبط بشكل. للقراءة [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | يعيد عنوان النص البديل المرتبط بشكل. للقراءة [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | الخاصية تحدد كيف سيُعرض الشكل في وضع اللونين (أبيض وأسود). للقراءة [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual [SmartArtColorType](../smartartcolortype/) [get_ColorStyle](./get_colorstyle/)() | إرجاع أو تعيين نمط اللون لكائن [SmartArt](../smartart/). للقراءة [SmartArtColorType](../smartartcolortype/). |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | يعيد عدد نقاط الاتصال على الشكل. للقراءة فقط **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | يعيد البيانات المخصصة للشكل. للقراءة فقط [ICustomData](../../aspose.slides/icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | يعيد كائن [EffectFormat](../../aspose.slides/effectformat/) الذي يحتوي على التأثيرات البكسلية المطبقة على الشكل. للقراءة فقط [IEffectFormat](../../aspose.slides/ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | يعيد كائن [FillFormat](../../aspose.slides/fillformat/) الذي يحتوي على خصائص تنسيق التعبئة لشكل. للقراءة فقط [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | يعيد خصائص إطار الشكل. للقراءة [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | يعيد أقفال الشكل. للقراءة فقط [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | يحصل على ارتفاع الشكل، مقاسًا بالنقاط. للقراءة **float**. |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | يحدد ما إذا كان الشكل مخفيًا. للقراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | يعيد الارتباط التشعبي المحدد للنقر بالفأرة. للقراءة [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | مدير الارتباطات التشعبية للقراءة فقط [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | يعيد الارتباط التشعبي المحدد للتمرير بالفأرة. للقراءة [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | يحصل على خيار 'تمييز كزخرف' قراءة/كتابة **bool**. |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | يحدد ما إذا كان الشكل مجموعة. للقراءة فقط **bool**. |
| virtual **bool** [get_IsReversed](./get_isreversed/)() | إرجاع أو تعيين حالة مخطط [SmartArt](../smartart/) بالنسبة إلى (من اليسار إلى اليمين) LTR أو (من اليمين إلى اليسار) RTL، إذا كان المخطط يدعم العكس. للقراءة **bool**. |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | يحدد ما إذا كان الشكل حاملاً للنص. للقراءة فقط **bool**. |
| virtual [SmartArtLayoutType](../smartartlayouttype/) [get_Layout](./get_layout/)() | إرجاع أو تعيين تخطيط كائن [SmartArt](../smartart/). للقراءة [SmartArtLayoutType](../smartartlayouttype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | يعيد كائن [LineFormat](../../aspose.slides/lineformat/) الذي يحتوي على خصائص تنسيق الخط لشكل. للقراءة فقط [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | يعيد اسم الشكل. للقراءة [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_Node](./get_node/)(**int32_t**) | يعيد عقدة من مجموعة العقد الجذرية في كائن [SmartArt](../smartart/) عند الفهرس المحدد. للقراءة فقط [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_NodeFromAll](./get_nodefromall/)(**int32_t**) | يعيد عقدة من مجموعة تحتوي على جميع العقد في كائن [SmartArt](../smartart/) عند الفهرس المحدد. للقراءة فقط [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_Nodes](./get_nodes/)() | يعيد مجموعات من العقد الجذرية في كائن [SmartArt](../smartart/). للقراءة فقط [ISmartArtNodeCollection](../ismartartnodecollection/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | يعيد معرفًا فريدًا يخص الشريحة يظل ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند. للقراءة فقط **uint32_t**. انظر أيضًا [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | يعيد كائن [GroupShape](../../aspose.slides/groupshape/) الأب إذا كان الشكل مجموعة. وإلا يعيد null. للقراءة فقط [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | يعيد العنصر النائب لشكل. للقراءة فقط [IPlaceholder](../../aspose.slides/iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | يعيد العرض التقديمي. للقراءة فقط [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [SmartArtQuickStyleType](../smartartquickstyletype/) [get_QuickStyle](./get_quickstyle/)() | إرجاع أو تعيين النمط السريع لكائن [SmartArt](../smartart/). للقراءة [SmartArtQuickStyleType](../smartartquickstyletype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | يعيد خصائص إطار الشكل الخام. للقراءة [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | يعيد عدد الدرجات التي يدور فيها الشكل المحدد حول محور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة. للقراءة **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | يعيد أقفال الشكل. للقراءة فقط [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | يعيد الشريحة الأساسية. للقراءة فقط [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | يعيد كائن [ThreeDFormat](../../aspose.slides/threedformat/) الذي يحتوي على خصائص تنسيق الخط لشكل. للقراءة فقط [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | يعيد معرفًا داخليًا يخص العرض التقديمي مخصصًا للاستخدام من قبل الإضافات أو الكود الآخر. نظرًا لأنه يمكن إعادة تعيين هذه القيمة من قبل المستخدم أو برمجيًا، لا ينبغي اعتبارها مفتاحًا فريدًا دائمًا. للقراءة فقط **uint32_t**. انظر أيضًا [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | يحصل على عرض الشكل، مقاسًا بالنقاط. للقراءة **float**. |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | يحصل على الإحداثي x لزاوية الشكل العلوية اليسرى، مقاسًا بالنقاط. للقراءة **float**. |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | يحصل على الإحداثي y لزاوية الشكل العلوية اليسرى، مقاسًا بالنقاط. للقراءة **float**. |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | يعيد موقع الشكل في ترتيب z. Shapes[0] يعيد الشكل الموجود في خلفية ترتيب z، و Shapes[Shapes.Count - 1] يعيد الشكل الموجود في مقدمة ترتيب z. للقراءة فقط **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | يعيد شكل عنصر نائب أساسي (شكل من التخطيط و/أو شريحة القالب التي يُرث منها الشكل الحالي). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجعية المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح التجزئة للكائنات المخصصة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | يعيد صورة مصغرة للشكل. [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) نوع حدود الصورة المصغرة للشكل يُستخدم افتراضيًا. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | يعيد صورة مصغرة للشكل. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. مماثل لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ عملية القفل في تعبير C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | يضبط النص البديل المرتبط بشكل. كتابة [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | يضبط عنوان النص البديل المرتبط بشكل. كتابة [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | الخاصية تحدد كيف سيُعرض الشكل في وضع اللونين (أبيض وأسود). كتابة [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual void [set_ColorStyle](./set_colorstyle/)([SmartArtColorType](../smartartcolortype/)) | إرجاع أو تعيين نمط اللون لكائن [SmartArt](../smartart/). كتابة [SmartArtColorType](../smartartcolortype/). |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | يضبط خصائص إطار الشكل. كتابة [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | يضبط ارتفاع الشكل، مقاسًا بالنقاط. كتابة **float**. |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | يحدد ما إذا كان الشكل مخفيًا. كتابة **bool**. |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | يضبط الارتباط التشعبي المحدد للنقر بالفأرة. كتابة [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | يضبط الارتباط التشعبي المحدد للتمرير بالفأرة. كتابة [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | يضبط خيار 'تمييز كزخرف' قراءة/كتابة **bool**. |
| virtual void [set_IsReversed](./set_isreversed/)(**bool**) | إرجاع أو تعيين حالة مخطط [SmartArt](../smartart/) بالنسبة إلى (من اليسار إلى اليمين) LTR أو (من اليمين إلى اليسار) RTL، إذا كان المخطط يدعم العكس. كتابة **bool**. |
| virtual void [set_Layout](./set_layout/)([SmartArtLayoutType](../smartartlayouttype/)) | إرجاع أو تعيين تخطيط كائن [SmartArt](../smartart/). كتابة [SmartArtLayoutType](../smartartlayouttype/). |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | يضبط اسم الشكل. كتابة [System::String](../../system/string/). |
| virtual void [set_QuickStyle](./set_quickstyle/)([SmartArtQuickStyleType](../smartartquickstyletype/)) | إرجاع أو تعيين النمط السريع لكائن [SmartArt](../smartart/). كتابة [SmartArtQuickStyleType](../smartartquickstyletype/). |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | يضبط خصائص إطار الشكل الخام. كتابة [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | يضبط عدد درجات دوران الشكل المحدد حول محور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة. كتابة **float**. |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | يضبط عرض الشكل، مقاسًا بالنقاط. كتابة **float**. |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | يضبط الإحداثي x لزاوية الشكل العلوية اليسرى، مقاسًا بالنقاط. كتابة **float**. |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | يضبط الإحداثي y لزاوية الشكل العلوية اليسرى، مقاسًا بالنقاط. كتابة **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي n كمرجع ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع الضعف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد المرجع المشترك ويعيده. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ عملية إلغاء القفل في تعبير C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | يحفظ محتوى [Shape](../../aspose.slides/shape/) كملف SVG. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | يحفظ محتوى [Shape](../../aspose.slides/shape/) كملف SVG. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## أنظر أيضًا

* فئة [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* نطاق [Aspose::Slides::SmartArt](../)
* مكتبة [Aspose.Slides](../../)