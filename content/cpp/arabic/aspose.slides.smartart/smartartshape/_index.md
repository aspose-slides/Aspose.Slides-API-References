---
title: SmartArtShape
second_title: مرجع API Aspose.Slides للغة C++
description: يمثل شكل SmartArt
type: docs
weight: 105
url: /ar/aspose.slides.smartart/smartartshape/
---
## فئة SmartArtShape

يمثل الشكل [SmartArt](../smartart/)

```cpp
class SmartArtShape : public Aspose::Slides::GeometryShape,
                      public Aspose::Slides::SmartArt::ISmartArtShape
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى عنصر محدد. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../../aspose.slides/ishapeelement/)\>\> [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements/)() override | ينشئ ويعيد مصفوفة من عناصر الشكل. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكى مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر عددان NaN متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكى مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر عددان NaN متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../../aspose.slides/iadjustvalue/)\> [get_Adjustment](../../aspose.slides/geometryshape/get_adjustment/)(**int32_t**) override | يرجع قيمة تعديل الشكل عند الفهرس المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/)\> [get_Adjustments](../../aspose.slides/geometryshape/get_adjustments/)() override | يرجع مجموعة من قيم تعديل الشكل. للقراءة فقط [IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | يرجع النص البديل المرتبط بالشكل. القراءة [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | يرجع عنوان النص البديل المرتبط بالشكل. القراءة [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | تحدد الخاصية كيفية عرض الشكل في وضع اللونين الأبيض والأسود. القراءة [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | يرجع عدد نقاط الاتصال على الشكل. للقراءة فقط **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | يرجع البيانات المخصصة للشكل. للقراءة فقط [ICustomData](../../aspose.slides/icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | يرجع كائن [EffectFormat](../../aspose.slides/effectformat/) الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: يمكن أن يُعيد null لأنواع معينة من الأشكال التي لا تتضمن خصائص التأثير. للقراءة فقط [IEffectFormat](../../aspose.slides/ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | يرجع كائن [FillFormat](../../aspose.slides/fillformat/) الذي يحتوي على خصائص تنسيق التعبئة للشكل. ملاحظة: يمكن أن يُعيد null لأنواع معينة من الأشكال التي لا تتضمن خصائص التعبئة. للقراءة فقط [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | يرجع خصائص إطار الشكل. القراءة [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | يحصل على ارتفاع الشكل، بالوحدات النقطية. القراءة **float**. |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | يحدد ما إذا كان الشكل مخفيًا. القراءة **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | يرجع الارتباط التشعبي المحدد للنقر بالفأرة. القراءة [IHyperlink](../../aspose.slides/ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | يرجع مدير الارتباط التشعبي. للقراءة فقط [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | يرجع الارتباط التشعبي المحدد عند وضع الفأرة. القراءة [IHyperlink](../../aspose.slides/ihyperlink/). |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | يحصل على خيار 'وضع علامة كزخرفة' قراءة/كتابة **bool**. |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | يحدد ما إذا كان الشكل مجموعة. للقراءة فقط **bool**. |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | يحدد ما إذا كان الشكل TextHolder_PPT. للقراءة فقط **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | يرجع كائن [LineFormat](../../aspose.slides/lineformat/) الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: يمكن أن يُعيد null لأنواع معينة من الأشكال التي لا تتضمن خصائص الخط. للقراءة فقط [ILineFormat](../../aspose.slides/ilineformat/). |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | يرجع اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. القراءة [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | يرجع معرّفًا فريدًا نطاقًا على الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو شفرة التفاعل بالإشارة إلى الشكل من أي مكان في المستند بثقة. للقراءة فقط **uint32_t**. انظر أيضًا [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | يرجع كائن [GroupShape](../../aspose.slides/groupshape/) الأب إذا كان الشكل مجموعة. وإلا يعيد null. للقراءة فقط [IGroupShape](../../aspose.slides/igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | يرجع العنصر النائب للشكل. يعيد null إذا لم يكن للشكل عنصر نائب. للقراءة فقط [IPlaceholder](../../aspose.slides/iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | يرجع عرض الشرائح الأب للشريحة. للقراءة فقط [IPresentation](../../aspose.slides/ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | يرجع خصائص إطار الشكل الخام. القراءة [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | يرجع عدد الدرجات التي يدور فيها الشكل المحدد حول المحور z. القيمة الإيجابية تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه العقارب. القراءة **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | يرجع أقفال الشكل. للقراءة فقط [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../../aspose.slides/ishapestyle/)\> [get_ShapeStyle](../../aspose.slides/geometryshape/get_shapestyle/)() override | يرجع كائن نمط الشكل. للقراءة فقط [IShapeStyle](../../aspose.slides/ishapestyle/). |
| [Aspose::Slides::ShapeType](../../aspose.slides/shapetype/) [get_ShapeType](./get_shapetype/)() override | يرجع نوع الإعداد المسبق للهندسة. ملاحظة: عند تغيير القيمة سيعاد تعيين جميع قيم التعديل إلى القيم الافتراضية. القراءة [Slides::ShapeType](../../aspose.slides/shapetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | يرجع شريحة الأب للشكل. للقراءة فقط [IBaseSlide](../../aspose.slides/ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrame](./get_textframe/)() override | يرجع نص الشكل [SmartArt](../smartart/). للقراءة فقط [ITextFrame](../../aspose.slides/itextframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | يرجع كائن [ThreeDFormat](../../aspose.slides/threedformat/) الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يُعيد null لأنواع معينة من الأشكال التي لا تمتلك خصائص ثلاثية الأبعاد. للقراءة فقط [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | يرجع معرفًا داخليًا نطاقًا على العرض مخصصًا للاستخدام بواسطة الإضافات أو الشفرات الأخرى. لأن هذه القيمة يمكن أن يعيد المستخدم تعيينها أو برمجيًا، لا يجب اعتبارها مفتاحًا فريدًا دائمًا. للقراءة فقط **uint32_t**. انظر أيضًا [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/). |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | يحصل على عرض الشكل، بالوحدات النقطية. القراءة **float**. |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | يحصل على إحداثي x لزاوية الشكل العلوية اليسرى، بالوحدات النقطية. القراءة **float**. |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | يحصل على إحداثي y لزاوية الشكل العلوية اليسرى، بالوحدات النقطية. القراءة **float**. |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | يرجع موضع الشكل في ترتيب z. Shapes[0] يعيد الشكل الموجود في الخلف من ترتيب z، وShapes[Shapes.Count - 1] يعيد الشكل الموجود في المقدمة. للقراءة فقط **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | يرجع شكل عنصر نائب أساسي (شكل من تخطيط و/أو شريحة رئيسية يتم وراثة الشكل الحالي منها). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل عداد المرجع المرتبط بالكائن. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\> [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths/)() override | يرجع نسخة من مسار الشكل الهندسي. الإحداثيات نسبية إلى الزاوية اليسرى العليا للشكل. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | يرجع صورة مصغرة للشكل. النوع [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) لحدود الصورة المصغرة للشكل يستخدم افتراضيًا. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | يرجع صورة مصغرة للشكل. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | يحصل على حدود الشكل البصرية المحسوبة من محتواه المُعرض. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموضح بـ targetType. نظير عامل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). يُستدعى مباشرةً أو يستخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائنًا من النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | يضبط النص البديل المرتبط بالشكل. كتابة [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | يضبط عنوان النص البديل المرتبط بالشكل. كتابة [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | تحدد الخاصية كيفية عرض الشكل في وضع اللونين الأبيض والأسود. كتابة [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | يضبط خصائص إطار الشكل. كتابة [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | يضبط ارتفاع الشكل، بالوحدات النقطية. كتابة **float**. |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | يحدد ما إذا كان الشكل مخفيًا. كتابة **bool**. |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | يضبط الارتباط التشعبي المحدد للنقر بالفأرة. كتابة [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | يضبط الارتباط التشعبي المحدد عند وضع الفأرة. كتابة [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | يضبط خيار 'وضع علامة كزخرفة' قراءة/كتابة **bool**. |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | يضبط اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. كتابة [System::String](../../system/string/). |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | يضبط خصائص إطار الشكل الخام. كتابة [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | يضبط عدد الدرجات التي يدور فيها الشكل المحدد حول المحور z. القيمة الإيجابية تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه العقارب. كتابة **float**. |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../../aspose.slides/shapetype/)) override | يضبط نوع الإعداد المسبق للهندسة. ملاحظة: عند تغيير القيمة سيعاد تعيين جميع قيم التعديل إلى القيم الافتراضية. كتابة [Slides::ShapeType](../../aspose.slides/shapetype/). |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | يضبط عرض الشكل، بالوحدات النقطية. كتابة **float**. |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | يضبط إحداثي x لزاوية الشكل العلوية اليسرى، بالوحدات النقطية. كتابة **float**. |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | يضبط إحداثي y لزاوية الشكل العلوية اليسرى، بالوحدات النقطية. كتابة **float**. |
| void [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>) override | يحدّث هندسة الشكل من كائن [IGeometryPath](../../aspose.slides/igeometrypath/). يجب أن تكون الإحداثيات نسبية إلى الزاوية اليسرى العليا للشكل. يغيّر نوع الشكل ([ShapeType](../../aspose.slides/shapetype/)) إلى [ShapeType::Custom](../../aspose.slides/shapetype/). |
| void [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\>) override | يحدّث هندسة الشكل من مصفوفة [IGeometryPath](../../aspose.slides/igeometrypath/). يجب أن تكون الإحداثيات نسبية إلى الزاوية اليسرى العليا للشكل. يغيّر نوع الشكل ([ShapeType](../../aspose.slides/shapetype/)) إلى [ShapeType::Custom](../../aspose.slides/shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضع الوسيط النمطي رقم n كمؤشر ضعيف (بدلاً من المشترك). يتيح تحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل عبارة C# lock(). يُستدعى مباشرةً أو يستخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | يحفظ محتوى [Shape](../../aspose.slides/shape/) كملف SVG. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | يحفظ محتوى [Shape](../../aspose.slides/shape/) كملف SVG. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |
## انظر أيضًا

* الفئة [GeometryShape](../../aspose.slides/geometryshape/)
* الفئة [ISmartArtShape](../ismartartshape/)
* النطاق [Aspose::Slides::SmartArt](../)
* المكتبة [Aspose.Slides](../../)