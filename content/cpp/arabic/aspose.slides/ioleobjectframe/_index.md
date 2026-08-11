---
title: IOleObjectFrame
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل كائن OLE على شريحة.
type: docs
weight: 3095
url: /ar/aspose.slides/ioleobjectframe/
---
## IOleObjectFrame فئة

Represents an OLE object on a slide.

```cpp
class IOleObjectFrame : public virtual Aspose::Slides::IGraphicalObject
```

## الطرق

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | يضيف عنصر نائب جديد إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى ما هو محدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُ considered القيم NaN متساوية على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُ considered القيم NaN متساوية على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | يُعيد النص البديل المرتبط بشكل. اقرأ [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | يُعيد عنوان النص البديل المرتبط بشكل. اقرأ [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | تحدد الخاصية طريقة عرض الشكل في وضع العرض بالأبيض والأسود. اقرأ [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | يُعيد عدد نقاط الاتصال على الشكل. للقراءة فقط **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | يُعيد البيانات المخصصة للشكل. للقراءة فقط [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | يُعيد كائن [EffectFormat](../effectformat/) الذي يحتوي على التأثيرات البكسلية المطبقة على الشكل. للقراءة فقط [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\> [get_EmbeddedData](./get_embeddeddata/)() | يحصل على معلومات حول بيانات OLE المضمّنة. للقراءة فقط [IOleEmbeddedDataInfo](../ioleembeddeddatainfo/). |
| virtual [System::String](../../system/string/) [get_EmbeddedFileLabel](./get_embeddedfilelabel/)() | يُعيد اسم ملف كائن OLE المضمّن. |
| virtual [System::String](../../system/string/) [get_EmbeddedFileName](./get_embeddedfilename/)() | يُعيد مسار كائن OLE المضمّن. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | يُعيد كائن [FillFormat](../fillformat/) الذي يحتوي على خصائص تنسيق التعبئة لشكل. للقراءة فقط [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | يُعيد خصائص إطار الشكل. اقرأ [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | يُعيد أقفال الشكل. للقراءة فقط [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | يحصل على ارتفاع الشكل، مقاسًا بوحدات النقاط. قراءة **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | يحدد ما إذا كان الشكل مخفيًا. قراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | يُعيد الارتباط التشعبي المحدد للنقر بالفأرة. اقرأ [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | مدير الروابط التشعبية. للقراءة فقط [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | يُعيد الارتباط التشعبي المحدد لتحويم الفأرة. اقرأ [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | يحصل على خيار 'تحديد كديكوري' قراءة/كتابة **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | يحدد ما إذا كان الشكل مجموعة. للقراءة فقط **bool**. |
| virtual **bool** [get_IsObjectIcon](./get_isobjecticon/)() | يحدد ما إذا كان الكائن مرئيًا كأيقونة. قراءة **bool**. |
| virtual **bool** [get_IsObjectLink](./get_isobjectlink/)() | يحدد ما إذا كان الكائن مرتبطًا بملف خارجي. للقراءة فقط **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | يحدد ما إذا كان الشكل TextHolder. للقراءة فقط **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | يُعيد كائن [LineFormat](../lineformat/) الذي يحتوي على خصائص تنسيق الخط لشكل. للقراءة فقط [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_LinkFileName](./get_linkfilename/)() | يُعيد المسار الكامل لملف مرتبط. سيتم استخدام اسم الملف القصير. للقراءة فقط [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | يُعيد المسار الكامل لملف مرتبط. سيتم استخدام اسم الملف الطويل. اقرأ [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_LinkPathRelative](./get_linkpathrelative/)() | يُعيد المسار النسبي لملف مرتبط إذا كان موجودًا، وإلا يُعيد سلسلة فارغة. للقراءة فقط [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | يُعيد اسم الشكل. اقرأ [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ObjectName](./get_objectname/)() | يُعيد اسم الكائن. اقرأ [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ObjectProgId](./get_objectprogid/)() | يُعيد ProgID للكائن. للقراءة فقط [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | يُعيد معرفًا فريدًا على مستوى الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند. للقراءة فقط **uint32_t**. انظر أيضًا [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | يُعيد كائن [GroupShape](../groupshape/) الأب إذا كان الشكل مجموعة. وإلا يُعيد null. للقراءة فقط [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | يُعيد العنصر النائب للشكل. للقراءة فقط [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | يُعيد العرض التقديمي. للقراءة فقط [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | يُعيد خصائص إطار الشكل الخام. اقرأ [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | يُعيد عدد الدرجات التي يُدوَّر بها الشكل المحدد حول المحور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ والقيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة. قراءة **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | يُعيد أقفال الشكل. للقراءة فقط [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | يُعيد الشريحة الأساسية. للقراءة فقط [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_SubstitutePictureFormat](./get_substitutepictureformat/)() | يُعيد كائن خصائص تعبئة صورة OleObject. للقراءة فقط [IPictureFillFormat](../ipicturefillformat/). |
| virtual [System::String](../../system/string/) [get_SubstitutePictureTitle](./get_substitutepicturetitle/)() | يُعيد العنوان لأيقونة OleObject. اقرأ [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | يُعيد كائن [ThreeDFormat](../threedformat/) الذي يحتوي على خصائص تنسيق الخط لشكل. للقراءة فقط [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | يُعيد معرفًا داخليًا على مستوى العرض التقديمي مخصصًا للاستخدام من قبل الإضافات أو الكود الآخر. نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، لا يجب معاملتها كمفتاح فريد دائم. للقراءة فقط **uint32_t**. انظر أيضًا [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **bool** [get_UpdateAutomatic](./get_updateautomatic/)() | يحدد ما إذا كان الكائن المضمّن المرتبط يُحدَّث تلقائيًا عند فتح أو طباعة العرض التقديمي. قراءة **bool**. |
| virtual **float** [get_Width](../ishape/get_width/)() | يحصل على عرض الشكل، مقاسًا بوحدات النقاط. قراءة **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | يحصل على إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بوحدات النقاط. قراءة **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | يحصل على إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بوحدات النقاط. قراءة **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | يُعيد موضع الشكل في ترتيب z. Shapes[0] يُعيد الشكل في مؤخرة ترتيب z، وShapes[Shapes.Count - 1] يُعيد الشكل في مقدمة ترتيب z. للقراءة فقط **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | يُعيد شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الرئيسة التي يُستمد منه الشكل الحالي). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تمثيل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | يُعيد صورة مصغرة للشكل. نوع حدود الصورة المصغرة [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) يُستخدم افتراضيًا. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | يُعيد صورة مصغرة للشكل. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تمثيل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموضح بـ targetType. تمثيل لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تمثيل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | يُعرّف أن هذا الشكل ليس عنصرًا نائبًا. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | يضبط النص البديل المرتبط بشكل. كتابة [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | يضبط عنوان النص البديل المرتبط بشكل. كتابة [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | تحدد الخاصية طريقة عرض الشكل في وضع العرض بالأبيض والأسود. كتابة [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | يضبط خصائص إطار الشكل. كتابة [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | يضبط ارتفاع الشكل، مقاسًا بوحدات النقاط. كتابة **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | يحدد ما إذا كان الشكل مخفيًا. كتابة **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | يضبط الارتباط التشعبي المحدد للنقر بالفأرة. كتابة [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | يضبط الارتباط التشعبي المحدد لتحويم الفأرة. كتابة [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | يضبط خيار 'تحديد كديكوري' قراءة/كتابة **bool**. |
| virtual void [set_IsObjectIcon](./set_isobjecticon/)(**bool**) | يحدد ما إذا كان الكائن مرئيًا كأيقونة. كتابة **bool**. |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | يضبط المسار الكامل لملف مرتبط. سيتم استخدام اسم الملف الطويل. كتابة [System::String](../../system/string/). |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | يضبط اسم الشكل. كتابة [System::String](../../system/string/). |
| virtual void [set_ObjectName](./set_objectname/)([System::String](../../system/string/)) | يضبط اسم الكائن. كتابة [System::String](../../system/string/). |
| virtual void [set_ObjectProgId](./set_objectprogid/)([System::String](../../system/string/)) | يُعيد ProgID للكائن. للقراءة فقط [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | يضبط خصائص إطار الشكل الخام. كتابة [IShapeFrame](../ishapeframe/). |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | يضبط عدد الدرجات التي يُدوَّر بها الشكل المحدد حول المحور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ والقيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة. كتابة **float**. |
| virtual void [set_SubstitutePictureTitle](./set_substitutepicturetitle/)([System::String](../../system/string/)) | يضبط العنوان لأيقونة OleObject. كتابة [System::String](../../system/string/). |
| virtual void [set_UpdateAutomatic](./set_updateautomatic/)(**bool**) | يحدد ما إذا كان الكائن المضمّن المرتبط يُحدَّث تلقائيًا عند فتح أو طباعة العرض التقديمي. كتابة **bool**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | يضبط عرض الشكل، مقاسًا بوحدات النقاط. كتابة **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | يضبط إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بوحدات النقاط. كتابة **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | يضبط إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بوحدات النقاط. كتابة **float**. |
| virtual void [SetEmbeddedData](./setembeddeddata/)([System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) | يضبط معلومات حول بيانات OLE المضمّنة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل الإشارات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويُعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تمثيل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | يحفظ محتوى [Shape](../shape/) كملف SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | يحفظ محتوى [Shape](../shape/) كملف SVG. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [IGraphicalObject](../igraphicalobject/)
* مساحة الاسم [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)