---
title: IInk
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل كائن حبر على شريحة.
type: docs
weight: 1
url: /ar/aspose.slides.ink/iink/
---
## فئة IInk

يمثل كائن حبر على شريحة.

```cpp
class IInk : public virtual Aspose::Slides::IGraphicalObject
```

## الطرق

| Method | الوصف |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | يضيف عنصر نائبي جديد إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين حتى وإن كان وفقًا لمعيار IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين حتى وإن كان وفقًا لمعيار IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | يرجع النص البديل المرتبط بالشكل. اقرأ [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | يرجع عنوان النص البديل المرتبط بالشكل. اقرأ [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | الخاصية تحدد كيف سيظهر الشكل في وضع العرض بالأبيض والأسود. اقرأ [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | يرجع عدد نقاط الاتصال على الشكل. للقراءة فقط **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | يرجع البيانات المخصصة للشكل. للقراءة فقط [ICustomData](../../aspose.slides/icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | يرجع كائن [EffectFormat](../../aspose.slides/effectformat/) الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. للقراءة فقط [IEffectFormat](../../aspose.slides/ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | يرجع كائن [FillFormat](../../aspose.slides/fillformat/) الذي يحتوي على خصائص تنسيق التعبئة لشكل. للقراءة فقط [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | يرجع خصائص إطار الشكل. اقرأ [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | يرجع أقفال الشكل. للقراءة فقط [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | يحصل على ارتفاع الشكل، مقاسًا بالنقاط. للقراءة **float**. |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | يحدد ما إذا كان الشكل مخفيًا. للقراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | يرجع الارتباط التشعبي المحدد للنقر بالفأرة. اقرأ [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | مدير الارتباطات التشعبية للقراءة فقط [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | يرجع الارتباط التشعبي المحدد عند المرور بالفأرة. اقرأ [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | يحصل على خيار 'تحديد كزخرفة' قراءة/كتابة **bool**. |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | يحدد ما إذا كان الشكل مجمعًا. للقراءة فقط **bool**. |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | يحدد ما إذا كان الشكل حامل نص. للقراءة فقط **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | يرجع كائن [LineFormat](../../aspose.slides/lineformat/) الذي يحتوي على خصائص تنسيق الخط لشكل. للقراءة فقط [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | يرجع اسم الشكل. اقرأ [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | يرجع معرّفًا فريدًا محدودًا بالعرض يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو شفرة التفاعل بالإشارة إلى الشكل بثقة من أي مكان في المستند. للقراءة فقط **uint32_t**. انظر أيضًا [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | يرجع كائن الأب [GroupShape](../../aspose.slides/groupshape/) إذا كان الشكل مجمعًا. وإلا يرجع null. للقراءة فقط [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | يرجع العنصر النائب للشكل. للقراءة فقط [IPlaceholder](../../aspose.slides/iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | يرجع العرض التقديمي. للقراءة فقط [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | يرجع خصائص إطار الشكل الخام. اقرأ [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | يرجع عدد درجات دوران الشكل المحدد حول المحور z. القيمة الإيجابية تشير إلى دوران باتجاه عقارب الساعة؛ والقيمة السلبية تشير إلى دوران عكس اتجاه العقارب. للقراءة **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | يرجع أقفال الشكل. للقراءة فقط [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | يرجع الشريحة الأساسية. للقراءة فقط [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | يرجع كائن [ThreeDFormat](../../aspose.slides/threedformat/) الذي يحتوي على خصائص تنسيق الخط لشكل. للقراءة فقط [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IInkTrace](../iinktrace/)\>\> [get_Traces](./get_traces/)() | يحصل على جميع الآثار الموجودة في العنصر [IInk](./) [IInkTrace](../iinktrace/). للقراءة فقط. |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | يرجع معرّفًا داخليًا محدودًا بالعرض مخصصًا للاستخدام من قبل الإضافات أو شفرة أخرى. نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، فلا يجب اعتبارها مفتاحًا فريدًا دائمًا. للقراءة فقط **uint32_t**. انظر أيضًا [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | يحصل على عرض الشكل، مقاسًا بالنقاط. للقراءة **float**. |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | يحصل على إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. للقراءة **float**. |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | يحصل على إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. للقراءة **float**. |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | يرجع موضع الشكل في ترتيب الـ z. Shapes[0] يرجع الشكل في خلفية ترتيب الـ z، و Shapes[Shapes.Count - 1] يرجع الشكل في مقدمة الترتيب. للقراءة فقط **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | يرجع شكلًا عنصرًا نائبيًا أساسيًا (شكل من التخطيط و/أو الشريحة الرئيسية التي يرثها الشكل الحالي). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | يرجع صورة مصغرة للشكل. النوع [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) لحدود الصورة المصغرة للشكل يُستخدم افتراضيًا. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | يرجع صورة مصغرة للشكل. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. تماثل عامل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | يطبق قفل تعبير C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، فقط يهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات حسب المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات حسب المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد مراجع المشاركة بالقيمة المحددة. |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | يعرف أن هذا الشكل ليس عنصرًا نائبًا. |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | يضبط النص البديل المرتبط بالشكل. كتابة [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | يضبط عنوان النص البديل المرتبط بالشكل. كتابة [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | الخاصية تحدد كيف سيظهر الشكل في وضع العرض بالأبيض والأسود. كتابة [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | يضبط خصائص إطار الشكل. كتابة [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | يضبط ارتفاع الشكل، مقاسًا بالنقاط. كتابة **float**. |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | يحدد ما إذا كان الشكل مخفيًا. كتابة **bool**. |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | يضبط الارتباط التشعبي للنقر بالفأرة. كتابة [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | يضبط الارتباط التشعبي عند المرور بالفأرة. كتابة [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | يضبط خيار 'تحديد كزخرفة' قراءة/كتابة **bool**. |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | يضبط اسم الشكل. كتابة [System::String](../../system/string/). |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | يضبط خصائص إطار الشكل الخام. كتابة [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | يضبط عدد درجات دوران الشكل المحدد حول المحور z. القيمة الإيجابية تشير إلى دوران باتجاه عقارب الساعة؛ والقيمة السلبية تشير إلى دوران عكس اتجاه العقارب. كتابة **float**. |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | يضبط عرض الشكل، مقاسًا بالنقاط. كتابة **float**. |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | يضبط إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. كتابة **float**. |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | يضبط إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. كتابة **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n كإشارة ضعيفة (بدلاً من مشاركة). يسمح بتبديل الإشارات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المراجع المشاركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المراجع المشاركة. لا ينبغي استدعاؤه مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويُعيد عداد المراجع المشاركة. لا ينبغي استدعاؤه مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق قفل تعبير C# lock() لإلغاء القفل. استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | يحفظ محتوى [Shape](../../aspose.slides/shape/) كملف SVG. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | يحفظ محتوى [Shape](../../aspose.slides/shape/) كملف SVG. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* مساحة الاسم [Aspose::Slides::Ink](../)
* مكتبة [Aspose.Slides](../../)