---
title: PictureFrame
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يمثل إطارًا يحتوي على صورة بداخله.
type: docs
weight: 4733
url: /ar/aspose.slides/pictureframe/
---
## PictureFrame class


يمثل إطارًا يحتوي على صورة داخلية.

```cpp
class PictureFrame : public Aspose::Slides::GeometryShape,
                     public virtual Aspose::Slides::IPictureFrame
```

## Methods

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | ينشئ ويعيد مصفوفة من عناصر الشكل. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقلد مقارنة النقطة العائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين رغم أنه وفقًا لـ IEC 60559:1989، NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقلد مقارنة النقطة العائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين رغم أنه وفقًا لـ IEC 60559:1989، NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | يرجع قيمة تعديل الشكل عند الفهرس المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | يرجع مجموعة من قيم تعديل الشكل. قراءة فقط [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | يرجع النص البديل المرتبط بالشكل. قراءة [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | يرجع عنوان النص البديل المرتبط بالشكل. قراءة [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | تحدد الخاصية كيف سيُعرض الشكل في وضع العرض بالأبيض والأسود. قراءة [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | يرجع عدد نقاط الاتصال على الشكل. قراءة فقط **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | يرجع البيانات المخصصة للشكل. قراءة فقط [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | يرجع كائن [EffectFormat](../effectformat/) الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يُعيد null لأنواع معينة من الأشكال التي لا تمتلك خصائص تأثير. قراءة فقط [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | يرجع كائن [FillFormat](../fillformat/) الذي يحتوي على خصائص تنسيق التعبئة للشكل. ملاحظة: قد يُعيد null لأنواع معينة من الأشكال التي لا تمتلك خصائص تعبئة. قراءة فقط [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | يرجع خصائص إطار الشكل. قراءة [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | يحصل على ارتفاع الشكل، مقاسًا بالنقاط. قراءة **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | يحدد ما إذا كان الشكل مخفيًا. قراءة **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | يرجع الارتباط التشعبي المحدد للنقر بالماوس. قراءة [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | يرجع مدير الارتباط التشعبي. قراءة فقط [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | يرجع الارتباط التشعبي المحدد عند مرور الماوس. قراءة [IHyperlink](../ihyperlink/). |
| **bool** [get_IsCameo](./get_iscameo/)() | يحدد ما إذا كان [PictureFrame](./) كائن Cameo أم لا. قراءة فقط **bool**. |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | يحصل على خيار 'وضع علامة كديكور' قراءة/كتابة **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | يحدد ما إذا كان الشكل مجموعة. قراءة فقط **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | يحدد ما إذا كان الشكل TextHolder_PPT. قراءة فقط **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | يرجع كائن [LineFormat](../lineformat/) الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: قد يُعيد null لأنواع معينة من الأشكال التي لا تمتلك خصائص خط. قراءة فقط [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | يرجع اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قراءة [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | يرجع معرفًا فريدًا نطاقه الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند. قراءة فقط **uint32_t**. انظر أيضًا [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | يرجع كائن [GroupShape](../groupshape/) الأب إذا كان الشكل مجموعة. وإلا يرجع null. قراءة فقط [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](./get_pictureformat/)() override | يرجع كائن [PictureFillFormat](../picturefillformat/) لإطار الصورة. قراءة فقط [IPictureFillFormat](../ipicturefillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](./get_pictureframelock/)() override | يرجع أقفال الشكل. قراءة فقط [IPictureFrameLock](../ipictureframelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | يرجع العنصر النائب للشكل. يرجع null إذا لم يكن للشكل عنصر نائب. قراءة فقط [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | يرجع عرض الشرائح الأب للعرض. قراءة فقط [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | يرجع خصائص إطار الشكل الخام. قراءة [IShapeFrame](../ishapeframe/). |
| **float** [get_RelativeScaleHeight](./get_relativescaleheight/)() override | يرجع مقياس الارتفاع (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تعادل 100٪. قراءة **float**. |
| **float** [get_RelativeScaleWidth](./get_relativescalewidth/)() override | يرجع مقياس العرض (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تعادل 100٪. قراءة **float**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | يرجع عدد الدرجات التي يدور فيها الشكل حول المحور z. القيمة الموجبة تشير إلى دوران clockwise؛ والقيمة السالبة إلى دوران counterclockwise. قراءة **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | يرجع أقفال الشكل. قراءة فقط [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | يرجع كائن نمط الشكل. قراءة فقط [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](./get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | يرجع شريحة الشكل الأب. قراءة فقط [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | يرجع كائن [ThreeDFormat](../threedformat/) الذي يحتوي على خصائص تأثير 3D للشكل. ملاحظة: قد يُعيد null لأنواع معينة من الأشكال التي لا تمتلك خصائص 3D. قراءة فقط [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | يرجع معرفًا داخليًا نطاقه العرض مخصص للاستخدام من قبل الإضافات أو كود آخر. نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، يجب ألا تُعامل كمفتاح فريد دائم. قراءة فقط **uint32_t**. انظر أيضًا [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | يحصل على عرض الشكل، مقاسًا بالنقاط. قراءة **float**. |
| **float** [get_X](../shape/get_x/)() override | يحصل على الإحداثي x لزاوية الشكل العليا اليسرى، مقاسًا بالنقاط. قراءة **float**. |
| **float** [get_Y](../shape/get_y/)() override | يحصل على الإحداثي y لزاوية الشكل العليا اليسرى، مقاسًا بالنقاط. قراءة **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | يرجع موضع الشكل في ترتيب z. Shapes[0] يرجع الشكل الخلفي في ترتيب z، وShapes[Shapes.Count - 1] يرجع الشكل الأمامي. قراءة فقط **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | يرجع شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الرئيسية التي يرث منها الشكل الحالي). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | يرجع نسخة من مسار الشكل الهندسي. الإحداثيات نسبية إلى الزاوية اليسرى العليا للشكل. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يسمح بتجزئة الكائنات المخصصة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | يرجع صورة مصغرة للشكل. نوع حدود الصورة المصغرة [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) يُستخدم افتراضيًا. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | يرجع صورة مصغرة للشكل. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | يحصل على الحدود البصرية للشكل محسوبة من محتواه المرسوم. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل C# lock() . استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يسمح باستنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنشئ نسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | يضبط النص البديل المرتبط بالشكل. كتابة [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | يضبط عنوان النص البديل المرتبط بالشكل. كتابة [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | تحدد الخاصية كيف سيُعرض الشكل في وضع العرض بالأبيض والأسود. كتابة [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | يضبط خصائص إطار الشكل. كتابة [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | يضبط ارتفاع الشكل، مقاسًا بالنقاط. كتابة **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | يحدد ما إذا كان الشكل مخفيًا. كتابة **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | يضبط الارتباط التشعبي للنقر بالماوس. كتابة [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | يضبط الارتباط التشعبي عند مرور الماوس. كتابة [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | يضبط خيار 'وضع علامة كديكور' قراءة/كتابة **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | يضبط اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. كتابة [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | يضبط خصائص إطار الشكل الخام. كتابة [IShapeFrame](../ishapeframe/). |
| void [set_RelativeScaleHeight](./set_relativescaleheight/)(**float**) override | يضبط مقياس ارتفاع إطار الصورة (نسبة إلى حجم الصورة الأصلي). القيمة 1.0 تعادل 100٪. كتابة **float**. |
| void [set_RelativeScaleWidth](./set_relativescalewidth/)(**float**) override | يضبط مقياس عرض إطار الصورة (نسبة إلى حجم الصورة الأصلي). القيمة 1.0 تعادل 100٪. كتابة **float**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | يضبط عدد الدرجات التي يدور فيها الشكل حول المحور z. القيمة الموجبة تشير إلى دوران clockwise؛ والسالبة إلى دوران counterclockwise. كتابة **float**. |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_Width](../shape/set_width/)(**float**) override | يضبط عرض الشكل، مقاسًا بالنقاط. كتابة **float**. |
| void [set_X](../shape/set_x/)(**float**) override | يضبط الإحداثي x للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. كتابة **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | يضبط الإحداثي y للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. كتابة **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | يحدّث هندسة الشكل من كائن [IGeometryPath](../igeometrypath/). يجب أن تكون الإحداثيات نسبية إلى الزاوية اليسرى العليا للشكل. يغيّر نوع الشكل ([ShapeType](../shapetype/)) إلى [ShapeType::Custom](../shapetype/). |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | يحدّث هندسة الشكل من مصفوفة [IGeometryPath](../igeometrypath/). يجب أن تكون الإحداثيات نسبية إلى الزاوية اليسرى العليا للشكل. يغيّر نوع الشكل ([ShapeType](../shapetype/)) إلى [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يحدد الوسيط القالب nth كمؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يُستدعى مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا يُستدعى مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ي解除 قفل C# lock() . استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يُستدعى مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا يُستدعى مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | يحفظ محتوى [Shape](../shape/) كملف SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | يحفظ محتوى [Shape](../shape/) كملف SVG. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |
## Remarks


الأمثلة التالية توضح كيفية تغيير [Audio](../audio/) إطار الصورة المصغرة.
```cpp
auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// يضيف إطار صوت إلى الشريحة بموقع وحجم محددين.
auto audioStream = System::MakeObject<System::IO::FileStream>(u"sample2.mp3", System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(150.0f, 100.0f, 50.0f, 50.0f, audioStream);
audioStream->Dispose();

// يضيف صورة إلى موارد العرض.
auto imageStream = System::IO::File::OpenRead(u"eagle.jpeg");
auto audioImage = presentation->get_Images()->AddImage(imageStream);
imageStream->Dispose();

// يضبط الصورة لإطار الصوت.
audioFrame->get_PictureFormat()->get_Picture()->set_Image(audioImage);

//يحفظ العرض المعدل إلى القرص
presentation->Save(u"example_out.pptx", SaveFormat::Pptx);
```

## See Also

* الفئة [GeometryShape](../geometryshape/)
* الفئة [IPictureFrame](../ipictureframe/)
* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)