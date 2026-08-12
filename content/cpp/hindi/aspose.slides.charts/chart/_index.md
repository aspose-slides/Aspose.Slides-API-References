---
title: Chart
second_title: Aspose.Slides for C++ API संदर्भ
description: स्लाइड पर एक ग्राफ़िक चार्ट को दर्शाता है।
type: docs
weight: 53
url: /hi/aspose.slides.charts/chart/
---
## Chart क्लास

Represents an graphic chart on a slide.

```cpp
class Chart : public Aspose::Slides::GraphicalObject,
              public Aspose::Slides::Charts::IChart
```

## Methods

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | यदि कोई placeholder नहीं है तो नया placeholder जोड़ता है और placeholder properties को निर्दिष्ट एक पर सेट करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](./createthemeeffective/)() override | इस chart के लिए प्रभावी theme लौटाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantics का उपयोग करके objects की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में reference type objects की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में value type objects की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-style floating point तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-style floating point तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | एक shape से जुड़ा वैकल्पिक पाठ लौटाता है। पढ़ें [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | एक shape से जुड़ी वैकल्पिक पाठ शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxesManager](../iaxesmanager/)\> [get_Axes](./get_axes/)() override | chart axes तक पहुंच प्रदान करता है। केवल पढ़ने योग्य [IAxesManager](../iaxesmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_BackWall](./get_backwall/)() override | एक object लौटाता है जो 3D chart की back wall के फ़ॉर्मेट को बदलने की अनुमति देता है। केवल पढ़ने योग्य [IChartWall](../ichartwall/). |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | गुणधर्म निर्दिष्ट करता है कि एक shape काले-और-सफ़ेद डिस्प्ले मोड में कैसे render होगा। पढ़ें [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartData](../ichartdata/)\> [get_ChartData](./get_chartdata/)() override | chart से जुड़े linked या embedded डेटा की जानकारी लौटाता है। केवल पढ़ने योग्य [IChartData](../ichartdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataTable](../idatatable/)\> [get_ChartDataTable](./get_chartdatatable/)() override | chart की डेटा तालिका लौटाता है। केवल पढ़ने योग्य [IDataTable](../idatatable/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_ChartTitle](./get_charttitle/)() override | chart का शीर्षक लौटाता है। केवल पढ़ने योग्य [IChartTitle](../icharttitle/). |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल पढ़ने योग्य **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | shape के custom डेटा को लौटाता है। केवल पढ़ने योग्य [ICustomData](../../aspose.slides/icustomdata/). |
| [DisplayBlanksAsType](../displayblanksastype/) [get_DisplayBlanksAs](./get_displayblanksas/)() override | chart पर खाली कोशिकाओं को plot करने का तरीका लौटाता है। पढ़ें [DisplayBlanksAsType](../displayblanksastype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | एक [EffectFormat](../../aspose.slides/effectformat/) object लौटाता है जिसमें shape पर लागू pixel effects शामिल हैं। नोट: उन प्रकार के shape के लिए जो effect properties नहीं रखते, null लौट सकता है। केवल पढ़ने योग्य [IEffectFormat](../../aspose.slides/ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | एक [FillFormat](../../aspose.slides/fillformat/) object लौटाता है जिसमें shape के fill formatting properties शामिल हैं। नोट: उन प्रकार के shape के लिए जो fill properties नहीं रखते, null लौट सकता है। केवल पढ़ने योग्य [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_Floor](./get_floor/)() override | 3D chart की floor के फ़ॉर्मेट को बदलने की अनुमति देता है। केवल पढ़ने योग्य [IChartWall](../ichartwall/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | shape frame की properties लौटाता है। पढ़ें [IShapeFrame](../../aspose.slides/ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/graphicalobject/get_graphicalobjectlock/)() override | shape के locks लौटाता है। केवल पढ़ने योग्य [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| **bool** [get_HasDataTable](./get_hasdatatable/)() override | निर्धारित करता है कि chart में डेटा तालिका है या नहीं। पढ़ें **bool**. |
| **bool** [get_HasLegend](./get_haslegend/)() override | निर्धारित करता है कि chart में legend है या नहीं। पढ़ें **bool**. |
| **bool** [get_HasRoundedCorners](./get_hasroundedcorners/)() override | chart area के rounded corners होने को निर्दिष्ट करता है। पढ़ें **bool**. |
| **bool** [get_HasTitle](./get_hastitle/)() override | निर्धारित करता है कि chart में visible title है या नहीं। पढ़ें **bool**. |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | shape की ऊँचाई points में प्राप्त करता है। पढ़ें **float**. |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | निर्धारित करता है कि shape छिपा हुआ है या नहीं। पढ़ें **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | mouse click के लिए परिभाषित hyperlink लौटाता है। पढ़ें [IHyperlink](../../aspose.slides/ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | hyperlink manager लौटाता है। केवल पढ़ने योग्य [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | mouse over के लिए परिभाषित hyperlink लौटाता है। पढ़ें [IHyperlink](../../aspose.slides/ihyperlink/). |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | ‘Mark as decorative’ विकल्प प्राप्त करता है पढ़ने/लिखने योग्य **bool**. |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | निर्धारित करता है कि shape समूहित है या नहीं। केवल पढ़ने योग्य **bool**. |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | निर्धारित करता है कि shape TextHolder_PPT है या नहीं। केवल पढ़ने योग्य **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegend](../ilegend/)\> [get_Legend](./get_legend/)() override | chart के लिए legend लौटाता है। केवल पढ़ने योग्य [ILegend](../ilegend/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | एक [LineFormat](../../aspose.slides/lineformat/) object लौटाता है जिसमें shape के line formatting properties शामिल हैं। नोट: उन प्रकार के shape के लिए जो line properties नहीं रखते, null लौट सकता है। केवल पढ़ने योग्य [ILineFormat](../../aspose.slides/ilineformat/). |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | shape का नाम लौटाता है। null नहीं होना चाहिए। आवश्यकता पड़ने पर खाली स्ट्रिंग प्रयोग करें। पढ़ें [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | slide-scoped unique identifier लौटाता है जो shape के lifetime के दौरान स्थिर रहता है और PowerPoint या interop code को दस्तावेज़ के किसी भी स्थान से shape को विश्वसनीय रूप से संदर्भित करने देता है। केवल पढ़ने योग्य **uint32_t**. देखें भी [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | यदि shape समूहित है तो parent [GroupShape](../../aspose.slides/groupshape/) object लौटाता है। अन्यथा null लौटाता है। केवल पढ़ने योग्य [IGroupShape](../../aspose.slides/igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | shape के लिए placeholder लौटाता है। यदि shape का कोई placeholder नहीं है तो null लौटाता है। केवल पढ़ने योग्य [IPlaceholder](../../aspose.slides/iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartPlotArea](../ichartplotarea/)\> [get_PlotArea](./get_plotarea/)() override | chart के plot area को दर्शाता है। केवल पढ़ने योग्य [IChartPlotArea](../ichartplotarea/). |
| **bool** [get_PlotVisibleCellsOnly](./get_plotvisiblecellsonly/)() override | निर्धारित करता है कि केवल visible cells plot हों। दोनों visible और hidden cells plot करने के लिए false उपयोग करें। पढ़ें **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | slide की parent presentation लौटाता है। केवल पढ़ने योग्य [IPresentation](../../aspose.slides/ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | raw shape frame की properties लौटाता है। पढ़ें [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | निर्दिष्ट shape की z-axis के चारों ओर घुमाव की डिग्री प्राप्त करता है। सकारात्मक मान clockwise rotation दर्शाता है; नकारात्मक मान counterclockwise rotation दर्शाता है। पढ़ें **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRotation3D](../irotation3d/)\> [get_Rotation3D](./get_rotation3d/)() override | chart की 3D rotation लौटाता है। केवल पढ़ने योग्य [IRotation3D](../irotation3d/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | shape के locks लौटाता है। केवल पढ़ने योग्य [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| **bool** [get_ShowDataLabelsOverMaximum](./get_showdatalabelsovermaximum/)() override | निर्दिष्ट करता है कि chart के अधिकतम पर डेटा लेबल दिखाए जाएँ। पढ़ें **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_SideWall](./get_sidewall/)() override | 3D chart की side wall के फ़ॉर्मेट को बदलने की अनुमति देता है। केवल पढ़ने योग्य [IChartWall](../ichartwall/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | shape की parent slide लौटाता है। केवल पढ़ने योग्य [IBaseSlide](../../aspose.slides/ibaseslide/). |
| [StyleType](../styletype/) [get_Style](./get_style/)() override | chart style लौटाता है। पढ़ें [StyleType](../styletype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | chart text format लौटाता है। यह property निम्नलिखित प्रकारों के लिए लागू नहीं है: [ChartType::Treemap](../charttype/), [ChartType::Sunburst](../charttype/), [ChartType::Waterfall](../charttype/), [ChartType::Histogram](../charttype/), [ChartType::Funnel](../charttype/),[ChartType::BoxAndWhisker](../charttype/). केवल पढ़ने योग्य [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](./get_thememanager/)() override | theme manager लौटाता है। केवल पढ़ने योग्य [Aspose::Slides::Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | एक [ThreeDFormat](../../aspose.slides/threedformat/) object लौटाता है जिसमें shape के 3d effect properties होते हैं। नोट: उन प्रकार के shape के लिए जो 3d properties नहीं रखते, null लौट सकता है। केवल पढ़ने योग्य [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| [ChartType](../charttype/) [get_Type](./get_type/)() override | chart type लौटाता है। पढ़ें [ChartType](../charttype/). |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | एक internal, presentation-scoped identifier लौटाता है जिसे add-ins या अन्य code द्वारा उपयोग किया जाता है। क्योंकि यह मान उपयोगकर्ता या programmatically पुन: असाइन किया जा सकता है, इसे स्थायी unique key के रूप में नहीं माना जाना चाहिए। केवल पढ़ने योग्य **uint32_t**. देखें भी [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_UserShapes](./get_usershapes/)() override | chart के ऊपर खींचे गए shapes को निर्दिष्ट करता है। केवल पढ़ने योग्य [IGroupShape](../../aspose.slides/igroupshape/). |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | shape की चौड़ाई points में प्राप्त करता है। पढ़ें **float**. |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | shape के ऊपरी-बाएँ कोने के x-coordinate को points में प्राप्त करता है। पढ़ें **float**. |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | shape के ऊपरी-बाएँ कोने के y-coordinate को points में प्राप्त करता है। पढ़ें **float**. |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | z-order में shape की स्थिति लौटाता है। Shapes[0] z-order के पीछे का shape लौटाता है, और Shapes[Shapes.Count - 1] आगे का shape लौटाता है। केवल पढ़ने योग्य **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | एक basic placeholder shape लौटाता है (layout और/या master slide से shape जो वर्तमान shape को विरासत में मिला है)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े reference counter डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) method का analog। कस्टम objects की hashing सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | shape thumbnail लौटाता है। [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) shape thumbnail bounds type डिफ़ॉल्ट रूप से उपयोग किया जाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | shape thumbnail लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का analog। |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | shape के rendered content से गणना किए गए visual bounds प्राप्त करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि object targetType द्वारा वर्णित प्रकार का instance है या नहीं। C# 'is' ऑपरेटर का analog। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) sentry object प्रयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method का analog। कस्टम टाइप्स की cloning सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी internal डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और subclasses की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और subclasses की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | objects की reference द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | objects की reference द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | value type object की nullptr से reference-compare करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | string और nullptr के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | strings के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से shared reference count घटाता है। |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | परिभाषित करता है कि यह shape placeholder नहीं है। |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | shape से जुड़ा वैकल्पिक पाठ सेट करता है। लिखें [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | shape से जुड़ी वैकल्पिक पाठ शीर्षक सेट करता है। लिखें [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | गुणधर्म निर्दिष्ट करता है कि shape काले-और-सफ़ेद डिस्प्ले मोड में कैसे render होगा। लिखें [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| void [set_DisplayBlanksAs](./set_displayblanksas/)([DisplayBlanksAsType](../displayblanksastype/)) override | chart पर खाली कोशिकाओं को plot करने का तरीका सेट करता है। लिखें [DisplayBlanksAsType](../displayblanksastype/). |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | shape frame की properties सेट करता है। लिखें [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_HasDataTable](./set_hasdatatable/)(**bool**) override | chart में डेटा तालिका है या नहीं निर्धारित करता है। लिखें **bool**. |
| void [set_HasLegend](./set_haslegend/)(**bool**) override | chart में legend है या नहीं निर्धारित करता है। लिखें **bool**. |
| void [set_HasRoundedCorners](./set_hasroundedcorners/)(**bool**) override | chart area के rounded corners होने को निर्दिष्ट करता है। लिखें **bool**. |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | chart में visible title है या नहीं निर्धारित करता है। लिखें **bool**. |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | shape की ऊँचाई points में सेट करता है। लिखें **float**. |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | shape छुपा हुआ है या नहीं निर्धारित करता है। लिखें **bool**. |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | mouse click के लिए hyperlink सेट करता है। लिखें [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | mouse over के लिए hyperlink सेट करता है। लिखें [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | ‘Mark as decorative’ विकल्प सेट करता है पढ़ने/लिखने योग्य **bool**. |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | shape का नाम सेट करता है। null नहीं होना चाहिए। आवश्यकता पड़ने पर खाली स्ट्रिंग प्रयोग करें। लिखें [System::String](../../system/string/). |
| void [set_PlotVisibleCellsOnly](./set_plotvisiblecellsonly/)(**bool**) override | केवल visible cells plot हों या नहीं निर्धारित करता है। दोनों visible और hidden cells plot करने के लिए false प्रयोग करें। लिखें **bool**. |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | raw shape frame की properties सेट करता है। लिखें [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | shape के z-axis के चारों ओर घुमाव की डिग्री सेट करता है। सकारात्मक मान clockwise rotation दर्शाता है; नकारात्मक मान counterclockwise rotation दर्शाता है। लिखें **float**. |
| void [set_ShowDataLabelsOverMaximum](./set_showdatalabelsovermaximum/)(**bool**) override | chart के अधिकतम पर डेटा लेबल दिखाए जाने को निर्दिष्ट करता है। लिखें **bool**. |
| void [set_Style](./set_style/)([StyleType](../styletype/)) override | chart style सेट करता है। लिखें [StyleType](../styletype/). |
| void [set_Type](./set_type/)([ChartType](../charttype/)) override | chart type सेट करता है। लिखें [ChartType](../charttype/). |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | shape की चौड़ाई points में सेट करता है। लिखें **float**. |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | shape के ऊपरी-बाएँ कोने के x-coordinate को points में सेट करता है। लिखें **float**. |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | shape के ऊपरी-बाएँ कोने के y-coordinate को points में सेट करता है। लिखें **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth template argument को weak pointer (shared की बजाय) के रूप में सेट करता है। कंटेनर में pointers को weak mode में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | shared reference counter का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | shared reference count बढ़ाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय smart pointers या ThisProtector प्रयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | shared reference count घटाता और लौटाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय smart pointers या ThisProtector प्रयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) method का analog। कस्टम objects को string में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) construct लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) sentry object प्रयोग करें। |
| void [ValidateChartLayout](./validatechartlayout/)() override | chart elements के वास्तविक मान गणना करता है। वास्तविक मान में उन तत्वों की स्थिति शामिल है जो [IActualLayout](../iactuallayout/) interface ([IActualLayout::get_ActualX](../iactuallayout/get_actualx/), [IActualLayout::get_ActualY](../iactuallayout/get_actualy/), [IActualLayout::get_ActualWidth](../iactuallayout/get_actualwidth/), [IActualLayout::get_ActualHeight](../iactuallayout/get_actualheight/)) को लागू करते हैं तथा वास्तविक axes मान ([IAxis::get_ActualMaxValue](../iaxis/get_actualmaxvalue/), [IAxis::get_ActualMinValue](../iaxis/get_actualminvalue/), [IAxis::get_ActualMajorUnit](../iaxis/get_actualmajorunit/), [IAxis::get_ActualMinorUnit](../iaxis/get_actualminorunit/), [IAxis::get_ActualMajorUnitScale](../iaxis/get_actualmajorunitscale/), [IAxis::get_ActualMinorUnitScale](../iaxis/get_actualminorunitscale/)) शामिल हैं। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak reference count बढ़ाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय smart pointers या ThisProtector प्रयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak reference count घटाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय smart pointers या ThisProtector प्रयोग करें। |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../../aspose.slides/shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../../aspose.slides/shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी internal डेटा संरचनाओं को मुक्त करता है। |
## देखें भी

* Class [GraphicalObject](../../aspose.slides/graphicalobject/)
* Class [IChart](../ichart/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)