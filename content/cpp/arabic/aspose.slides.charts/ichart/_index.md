---
title: IChart
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثّل مخططًا رسوميًا على شريحة.
type: docs
weight: 573
url: /ar/aspose.slides.charts/ichart/
---
## IChart فئة


يمثل مخططًا رسوميًا على شريحة.

```cpp
class IChart : public virtual Aspose::Slides::IGraphicalObject,
               public Aspose::Slides::Charts::IFormattedTextContainer,
               public Aspose::Slides::Theme::IOverrideThemeable
```

## الأساليب

| الدالة | الوصف |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى عنصر محدد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | يعيد موضوعًا فعالًا لهذا الكائن القابل للتصميم. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوك C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يُعتبر NaNانان متساويين رغم أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يُعتبر NaNانان متساويين رغم أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | يعيد النص البديل المرتبط بشكِل. اقرأ [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | يعيد عنوان النص البديل المرتبط بشكِل. اقرأ [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxesManager](../iaxesmanager/)\> [get_Axes](./get_axes/)() | يوفر وصولًا إلى محاور المخطط. للقراءة فقط [IAxesManager](../iaxesmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_BackWall](./get_backwall/)() | يعيد كائنًا يتيح تغيير تنسيق الجدار الخلفي لمخطط ثلاثي الأبعاد. للقراءة فقط [IChartWall](../ichartwall/). |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | العنصر يحدد كيف سيُعرض الشكل في وضع أبيض-أسود. اقرأ [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](./)\> [get_Chart](../ichartcomponent/get_chart/)() | يعيد المخطط. للقراءة فقط [IChart](./). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartData](../ichartdata/)\> [get_ChartData](./get_chartdata/)() | يعيد معلومات حول البيانات المرتبطة أو المضمنة المرتبطة بمخطط. للقراءة فقط [IChartData](../ichartdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataTable](../idatatable/)\> [get_ChartDataTable](./get_chartdatatable/)() | يعيد جدول بيانات للمخطط. للقراءة فقط [IDataTable](../idatatable/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_ChartTitle](./get_charttitle/)() | يعيد عنوان المخطط. للقراءة فقط [IChartTitle](../icharttitle/). |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | يعيد عدد نقاط الاتصال على الشكل. للقراءة فقط **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | يعيد بيانات مخصصة للشكل. للقراءة فقط [ICustomData](../../aspose.slides/icustomdata/). |
| virtual [DisplayBlanksAsType](../displayblanksastype/) [get_DisplayBlanksAs](./get_displayblanksas/)() | يعيد طريقة رسم الخلايا الفارغة على المخطط. اقرأ [DisplayBlanksAsType](../displayblanksastype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | يعيد كائن [EffectFormat](../../aspose.slides/effectformat/) الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. للقراءة فقط [IEffectFormat](../../aspose.slides/ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | يعيد كائن [FillFormat](../../aspose.slides/fillformat/) الذي يحتوي على خصائص تنسيق التعبئة لشكل. للقراءة فقط [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_Floor](./get_floor/)() | يعيد كائنًا يتيح تغيير تنسيق أرضية مخطط ثلاثي الأبعاد. للقراءة فقط [IChartWall](../ichartwall/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | يعيد خصائص إطار الشكل. اقرأ [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | يعيد أقفال الشكل. للقراءة فقط [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| virtual **bool** [get_HasDataTable](./get_hasdatatable/)() | يحدد ما إذا كان للمخطط جدول بيانات. اقرأ **bool**. |
| virtual **bool** [get_HasLegend](./get_haslegend/)() | يحدد ما إذا كان للمخطط وسيلة إيضاح. اقرأ **bool**. |
| virtual **bool** [get_HasRoundedCorners](./get_hasroundedcorners/)() | يحدد أن منطقة المخطط يجب أن تكون ذات زوايا مستديرة. اقرأ **bool**. |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | يحدد ما إذا كان للمخطط عنوان مرئي. اقرأ **bool**. |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | يحصل على ارتفاع الشكل، مقاسًا بالنقاط. اقرأ **float**. |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | يحدد ما إذا كان الشكل مخفيًا. اقرأ **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | يعيد الارتباط التشعبي المحدد للنقر بالفأرة. اقرأ [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | مدير الارتباطات التشعبية للقراءة فقط [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | يعيد الارتباط التشعبي المحدد لتمرير الفأرة فوقه. اقرأ [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | يحصل على خيار 'وضع علامة كديكوري' قراءة/كتابة **bool**. |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | يحدد ما إذا كان الشكل مجموعة. للقراءة فقط **bool**. |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | يحدد ما إذا كان الشكل حاملاً للنص. للقراءة فقط **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegend](../ilegend/)\> [get_Legend](./get_legend/)() | يعيد وسيلة إيضاح للمخطط. للقراءة فقط [ILegend](../ilegend/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | يعيد كائن [LineFormat](../../aspose.slides/lineformat/) الذي يحتوي على خصائص تنسيق الخط لشكل. للقراءة فقط [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | يعيد اسم الشكل. اقرأ [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | يعيد معرفًا فريدًا محتوًى على مستوى الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو شفرة التفاعل بالإشارة إلى الشكل من أي مكان في المستند. للقراءة فقط **uint32_t**. انظر أيضًا [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | يعيد كائن [GroupShape](../../aspose.slides/groupshape/) الأب إذا كان الشكل مجموعة. وإلا يعيد null. للقراءة فقط [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | يعيد العنصر النائب لشكل. للقراءة فقط [IPlaceholder](../../aspose.slides/iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartPlotArea](../ichartplotarea/)\> [get_PlotArea](./get_plotarea/)() | يمثل منطقة الرسم للمخطط. للقراءة فقط [IChartPlotArea](../ichartplotarea/). |
| virtual **bool** [get_PlotVisibleCellsOnly](./get_plotvisiblecellsonly/)() | يحدد ما إذا كانت الخلايا المرئية فقط هي التي تُرسم. ضع false لرسم كل من الخلايا المرئية والمخفية. اقرأ **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | يعيد العرض التقديمي. للقراءة فقط [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | يعيد خصائص إطار الشكل الخام. اقرأ [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | يعيد عدد الدرجات التي يدور بها الشكل المحدد حول المحور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ والسالبة تشير إلى دوران عكس اتجاه عقارب الساعة. اقرأ **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRotation3D](../irotation3d/)\> [get_Rotation3D](./get_rotation3d/)() | يعيد دورانًا ثلاثي الأبعاد للمخطط. للقراءة فقط [IRotation3D](../irotation3d/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | يعيد أقفال الشكل. للقراءة فقط [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| virtual **bool** [get_ShowDataLabelsOverMaximum](./get_showdatalabelsovermaximum/)() | يحدد أن تسميات البيانات فوق الحد الأقصى للمخطط يجب أن تُعرض. اقرأ **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_SideWall](./get_sidewall/)() | يعيد كائنًا يتيح تغيير تنسيق الجدار الجانبي لمخطط ثلاثي الأبعاد. للقراءة فقط [IChartWall](../ichartwall/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | يعيد الشريحة الأساسية. للقراءة فقط [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [StyleType](../styletype/) [get_Style](./get_style/)() | يعيد نمط المخطط. اقرأ [StyleType](../styletype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | يعيد تنسيق نص المخطط. للقراءة فقط [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](../../aspose.slides.theme/ioverridethemeable/get_thememanager/)() | يعيد مدير سمة التجاوز. للقراءة فقط [IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | يعيد كائن [ThreeDFormat](../../aspose.slides/threedformat/) الذي يحتوي على خصائص تنسيق الخط لشكل. للقراءة فقط [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| virtual [ChartType](../charttype/) [get_Type](./get_type/)() | يعيد نوع المخطط. اقرأ [ChartType](../charttype/). |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | يعيد معرفًا داخليًا محتوًى على مستوى العرض التقديمي مخصصًا لاستخدام الإضافات أو الشفرة الأخرى. نظرًا لأنه يمكن إعادة تعيين هذه القيمة من قبل المستخدم أو برمجيًا، لا ينبغي اعتبارها مفتاحًا فريدًا مستمرًا. للقراءة فقط **uint32_t**. انظر أيضًا [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_UserShapes](./get_usershapes/)() | حدد الأشكال المرسومة فوق المخطط. للقراءة فقط [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | يحصل على عرض الشكل، مقاسًا بالنقاط. اقرأ **float**. |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | يحصل على إحداثي x لزاوية الشكل العليا اليسرى، مقاسًا بالنقاط. اقرأ **float**. |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | يحصل على إحداثي y لزاوية الشكل العليا اليسرى، مقاسًا بالنقاط. اقرأ **float**. |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | يعيد موضع الشكل في ترتيب z. Shapes[0] يعيد الشكل في خلفية ترتيب z، و Shapes[Shapes.Count - 1] يعيد الشكل في مقدمة ترتيب z. للقراءة فقط **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | يعيد شكلًا نائبًا أساسيًا (شكل من تخطيط و/أو الشريحة الرئيسية التي يرث منها الشكل الحالي). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يُمكّن تجزئة الكائنات المخصصة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | يعيد صورة مصغرة للشكل. يُستخدم النوع [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) لحدود الصورة المصغرة للشكل افتراضيًا. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | يعيد صورة مصغرة للشكل. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثالًا للنوع الموصوف بـ targetType. نظير عامل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يُمكّن استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد مراجع المشاركة بالقيمة المحددة. |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | يضبط النص البديل المرتبط بشكِل. اكتب [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | يضبط عنوان النص البديل المرتبط بشكِل. اكتب [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | العنصر يحدد كيف سيُعرض الشكل في وضع أبيض-أسود. اكتب [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual void [set_DisplayBlanksAs](./set_displayblanksas/)([DisplayBlanksAsType](../displayblanksastype/)) | يضبط طريقة رسم الخلايا الفارغة على المخطط. اكتب [DisplayBlanksAsType](../displayblanksastype/). |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | يضبط خصائص إطار الشكل. اكتب [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_HasDataTable](./set_hasdatatable/)(**bool**) | يحدد ما إذا كان للمخطط جدول بيانات. اكتب **bool**. |
| virtual void [set_HasLegend](./set_haslegend/)(**bool**) | يحدد ما إذا كان للمخطط وسيلة إيضاح. اكتب **bool**. |
| virtual void [set_HasRoundedCorners](./set_hasroundedcorners/)(**bool**) | يحدد أن منطقة المخطط يجب أن تكون ذات زوايا مستديرة. اكتب **bool**. |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | يحدد ما إذا كان للمخطط عنوان مرئي. اكتب **bool**. |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | يضبط ارتفاع الشكل، مقاسًا بالنقاط. اكتب **float**. |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | يحدد ما إذا كان الشكل مخفيًا. اكتب **bool**. |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | يضبط الارتباط التشعبي المحدد للنقر بالفأرة. اكتب [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | يضبط الارتباط التشعبي المحدد لتمرير الفأرة فوقه. اكتب [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | يضبط خيار 'وضع علامة كديكوري' قراءة/كتابة **bool**. |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | يضبط اسم الشكل. اكتب [System::String](../../system/string/). |
| virtual void [set_PlotVisibleCellsOnly](./set_plotvisiblecellsonly/)(**bool**) | يحدد ما إذا كانت الخلايا المرئية فقط هي التي تُرسم. ضع false لرسم كل من الخلايا المرئية والمخفية. اكتب **bool**. |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | يضبط خصائص إطار الشكل الخام. اكتب [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | يضبط عدد الدرجات التي يدور بها الشكل المحدد حول المحور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ السالبة إلى عكس الاتجاه. اكتب **float**. |
| virtual void [set_ShowDataLabelsOverMaximum](./set_showdatalabelsovermaximum/)(**bool**) | يحدد أن تسميات البيانات فوق الحد الأقصى للمخطط يجب أن تُعرض. اكتب **bool**. |
| virtual void [set_Style](./set_style/)([StyleType](../styletype/)) | يضبط نمط المخطط. اكتب [StyleType](../styletype/). |
| virtual void [set_Type](./set_type/)([ChartType](../charttype/)) | يضبط نوع المخطط. اكتب [ChartType](../charttype/). |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | يضبط عرض الشكل، مقاسًا بالنقاط. اكتب **float**. |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | يضبط إحداثي x لزاوية الشكل العليا اليسرى، مقاسًا بالنقاط. اكتب **float**. |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | يضبط إحداثي y لزاوية الشكل العليا اليسرى، مقاسًا بالنقاط. اكتب **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | حدد الوسيط القالب رقم n كإشارة ضعيفة (بدلاً من مشاركة). يتيح تبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المراجع المشتركة. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المراجع المشتركة. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يُمكّن تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual void [ValidateChartLayout](./validatechartlayout/)() | يحسب القيم الفعلية لعناصر المخطط. القيم الفعلية تشمل موضع العناصر التي تنفذ واجهة [IActualLayout](../iactuallayout/) ([IActualLayout::get_ActualX](../iactuallayout/get_actualx/), [IActualLayout::get_ActualY](../iactuallayout/get_actualy/), [IActualLayout::get_ActualWidth](../iactuallayout/get_actualwidth/), [IActualLayout::get_ActualHeight](../iactuallayout/get_actualheight/)) وقيم المحاور الفعلية ([IAxis::get_ActualMaxValue](../iaxis/get_actualmaxvalue/), [IAxis::get_ActualMinValue](../iaxis/get_actualminvalue/), [IAxis::get_ActualMajorUnit](../iaxis/get_actualmajorunit/), [IAxis::get_ActualMinorUnit](../iaxis/get_actualminorunit/), [IAxis::get_ActualMajorUnitScale](../iaxis/get_actualmajorunitscale/), [IAxis::get_ActualMinorUnitScale](../iaxis/get_actualminorunitscale/)). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | يحفظ محتوى [Shape](../../aspose.slides/shape/) كملف SVG. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | يحفظ محتوى [Shape](../../aspose.slides/shape/) كملف SVG. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضاً

* فئة [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* فئة [IFormattedTextContainer](../iformattedtextcontainer/)
* فئة [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable/)
* نطاق [Aspose::Slides::Charts](../)
* مكتبة [Aspose.Slides](../../)