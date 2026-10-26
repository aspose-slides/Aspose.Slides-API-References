---
title: IChart
second_title: Aspose.Slides for C++ API संदर्भ
description: एक स्लाइड पर ग्राफ़िक चार्ट का प्रतिनिधित्व करता है।
type: docs
weight: 573
url: /hi/aspose.slides.charts/ichart/
---
## IChart क्लास

एक स्लाइड पर ग्राफ़िक चार्ट का प्रतिनिधित्व करता है।

```cpp
class IChart : public virtual Aspose::Slides::IGraphicalObject,
               public Aspose::Slides::Charts::IFormattedTextContainer,
               public Aspose::Slides::Theme::IOverrideThemeable
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | यदि कोई placeholder नहीं है तो नया placeholder जोड़ता है और placeholder गुणों को एक निर्दिष्ट वाले पर सेट करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | इस themeable ऑब्जेक्ट के लिए प्रभावी थीम लौटाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | रेफरेंस टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | वैल्यू टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | एक आकृति से जुड़ा वैकल्पिक टेक्स्ट लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | एक आकृति से जुड़े वैकल्पिक टेक्स्ट का शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxesManager](../iaxesmanager/)\> [get_Axes](./get_axes/)() | चार्ट अक्षों तक पहुँच प्रदान करता है। केवल पढ़ने योग्य [IAxesManager](../iaxesmanager/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_BackWall](./get_backwall/)() | एक ऑब्जेक्ट लौटाता है जो 3D चार्ट की बैक वॉल के फॉर्मेट को बदलने की अनुमति देता है। केवल पढ़ने योग्य [IChartWall](../ichartwall/)। |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | प्रॉपर्टी निर्धारित करती है कि एक आकृति ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगी। पढ़ें [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](./)\> [get_Chart](../ichartcomponent/get_chart/)() | चार्ट लौटाता है। केवल पढ़ने योग्य [IChart](./)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartData](../ichartdata/)\> [get_ChartData](./get_chartdata/)() | एक चार्ट से जुड़े लिंक्ड या एम्बेडेड डेटा के बारे में जानकारी लौटाता है। केवल पढ़ने योग्य [IChartData](../ichartdata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataTable](../idatatable/)\> [get_ChartDataTable](./get_chartdatatable/)() | एक चार्ट की डेटा टेबल लौटाता है। केवल पढ़ने योग्य [IDataTable](../idatatable/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_ChartTitle](./get_charttitle/)() | चार्ट का शीर्षक लौटाता है। केवल पढ़ने योग्य [IChartTitle](../icharttitle/)। |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | आकृति पर कनेक्शन साइटों की संख्या लौटाता है। केवल पढ़ने योग्य **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | आकृति का कस्टम डेटा लौटाता है। केवल पढ़ने योग्य [ICustomData](../../aspose.slides/icustomdata/)। |
| virtual [DisplayBlanksAsType](../displayblanksastype/) [get_DisplayBlanksAs](./get_displayblanksas/)() | चार्ट पर खाली कोशिकाओं को प्लॉट करने का तरीका लौटाता है। पढ़ें [DisplayBlanksAsType](../displayblanksastype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | [EffectFormat](../../aspose.slides/effectformat/) ऑब्जेक्ट लौटाता है जिसमें आकृति पर लागू पिक्सेल इफ़ेक्ट्स होते हैं। केवल पढ़ने योग्य [IEffectFormat](../../aspose.slides/ieffectformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | [FillFormat](../../aspose.slides/fillformat/) ऑब्जेक्ट लौटाता है जिसमें आकृति के लिए फ़िल फ़ॉर्मेटिंग प्रॉपर्टीज़ होती हैं। केवल पढ़ने योग्य [IFillFormat](../../aspose.slides/ifillformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_Floor](./get_floor/)() | एक ऑब्जेक्ट लौटाता है जो 3D चार्ट के फ़्लोर के फॉर्मेट को बदलने की अनुमति देता है। केवल पढ़ने योग्य [IChartWall](../ichartwall/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | आकृति फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../../aspose.slides/ishapeframe/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | आकृति के लॉक लौटाता है। केवल पढ़ने योग्य [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)। |
| virtual **bool** [get_HasDataTable](./get_hasdatatable/)() | निर्धारित करता है कि क्या चार्ट में डेटा टेबल है। पढ़ें **bool**। |
| virtual **bool** [get_HasLegend](./get_haslegend/)() | निर्धारित करता है कि क्या चार्ट में लेजेंड है। पढ़ें **bool**। |
| virtual **bool** [get_HasRoundedCorners](./get_hasroundedcorners/)() | निर्दिष्ट करता है कि चार्ट एरिया में गोल कोने होने चाहिए। पढ़ें **bool**। |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | निर्धारित करता है कि क्या चार्ट में एक दृश्यमान शीर्षक है। पढ़ें **bool**। |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | आकृति की ऊँचाई पॉइंट्स में प्राप्त करता है। पढ़ें **float**। |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | निर्धारित करता है कि क्या आकृति छिपी हुई है। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../../aspose.slides/ihyperlink/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | हाइपरलिंक प्रबंधक केवल पढ़ने योग्य [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../../aspose.slides/ihyperlink/)। |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | 'Mark as decorative' विकल्प प्राप्त करता है। पढ़ें/लिखें **bool**। |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | निर्धारित करता है कि क्या आकृति ग्रुप की गई है। केवल पढ़ने योग्य **bool**। |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | निर्धारित करता है कि क्या आकृति TextHolder है। केवल पढ़ने योग्य **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegend](../ilegend/)\> [get_Legend](./get_legend/)() | एक चार्ट के लिए लेजेंड लौटाता है। केवल पढ़ने योग्य [ILegend](../ilegend/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | [LineFormat](../../aspose.slides/lineformat/) ऑब्जेक्ट लौटाता है जिसमें आकृति के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ हैं। केवल पढ़ने योग्य [ILineFormat](../../aspose.slides/ilineformat/)। |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | आकृति का नाम लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | एक स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो आकृति के जीवनकाल के दौरान स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ के कहीं से भी आकृति का भरोसेमंद रेफ़रेंस देने की सुविधा देता है। केवल पढ़ने योग्य **uint32_t**। देखें [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | यदि आकृति ग्रुप की गई है तो पैरेंट [GroupShape](../../aspose.slides/groupshape/) ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल पढ़ने योग्य [IGroupShape](../../aspose.slides/igroupshape/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | आकृति के लिए प्लेसहोल्डर लौटाता है। केवल पढ़ने योग्य [IPlaceholder](../../aspose.slides/iplaceholder/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartPlotArea](../ichartplotarea/)\> [get_PlotArea](./get_plotarea/)() | एक चार्ट के प्लॉट एरिया का प्रतिनिधित्व करता है। केवल पढ़ने योग्य [IChartPlotArea](../ichartplotarea/)। |
| virtual **bool** [get_PlotVisibleCellsOnly](./get_plotvisiblecellsonly/)() | निर्धारित करता है कि केवल दृश्यमान कोशिकाओं को प्लॉट किया जाए। दोनों दृश्यमान और छिपी हुई कोशिकाओं को प्लॉट करने के लिए False सेट करें। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | प्रेज़ेंटेशन लौटाता है। केवल पढ़ने योग्य [IPresentation](../../aspose.slides/ipresentation/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | कच्चे आकार फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../../aspose.slides/ishapeframe/)। |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | निर्दिष्ट आकृति के z-अक्ष के चारों ओर घुमाव की डिग्री संख्या लौटाता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विपरीत दिशा में। पढ़ें **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRotation3D](../irotation3d/)\> [get_Rotation3D](./get_rotation3d/)() | एक चार्ट का 3D घुमाव लौटाता है। केवल पढ़ने योग्य [IRotation3D](../irotation3d/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | आकृति के लॉक लौटाता है। केवल पढ़ने योग्य [IBaseShapeLock](../../aspose.slides/ibaseshapelock/)। |
| virtual **bool** [get_ShowDataLabelsOverMaximum](./get_showdatalabelsovermaximum/)() | निर्धारित करता है कि चार्ट के अधिकतम पर डेटा लेबल दिखाए जाएँ। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_SideWall](./get_sidewall/)() | एक ऑब्जेक्ट लौटाता है जो 3D चार्ट की साइड वॉल के फॉर्मेट को बदलने की अनुमति देता है। केवल पढ़ने योग्य [IChartWall](../ichartwall/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | बेस स्लाइड लौटाता है। केवल पढ़ने योग्य [IBaseSlide](../../aspose.slides/ibaseslide/)। |
| virtual [StyleType](../styletype/) [get_Style](./get_style/)() | चार्ट शैली लौटाता है। पढ़ें [StyleType](../styletype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | चार्ट टेक्स्ट फ़ॉर्मेट लौटाता है। केवल पढ़ने योग्य [IChartTextFormat](../icharttextformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](../../aspose.slides.theme/ioverridethemeable/get_thememanager/)() | ओवरराइड थीम मैनेजर लौटाता है। केवल पढ़ने योग्य [IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | [ThreeDFormat](../../aspose.slides/threedformat/) ऑब्जेक्ट लौटाता है जिसमें आकृति के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ हैं। केवल पढ़ने योग्य [IThreeDFormat](../../aspose.slides/ithreedformat/)। |
| virtual [ChartType](../charttype/) [get_Type](./get_type/)() | चार्ट प्रकार लौटाता है। पढ़ें [ChartType](../charttype/)। |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | एक आंतरिक, प्रेज़ेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है जिसका उपयोग ऐड-इन या अन्य कोड द्वारा किया जाता है। क्योंकि यह मान उपयोगकर्ता या प्रोग्रामेटिकली पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी नहीं माना जाना चाहिए। केवल पढ़ने योग्य **uint32_t**। देखें [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_UserShapes](./get_usershapes/)() | चार्ट के ऊपर खींची गई आकृतियों को निर्दिष्ट करता है। केवल पढ़ने योग्य [IGroupShape](../../aspose.slides/igroupshape/)। |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | आकृति की चौड़ाई पॉइंट्स में प्राप्त करता है। पढ़ें **float**। |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | आकृति के ऊपरी-बाएँ कोने का x-निर्देशांक पॉइंट्स में प्राप्त करता है। पढ़ें **float**। |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | आकृति के ऊपरी-बाएँ कोने का y-निर्देशांक पॉइंट्स में प्राप्त करता है। पढ़ें **float**। |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | z-ऑर्डर में आकृति की स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पीछे वाली आकृति लौटाता है, और Shapes[Shapes.Count - 1] आगे वाली आकृति लौटाता है। केवल पढ़ने योग्य **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | एक बुनियादी प्लेसहोल्डर आकृति लौटाता है (लेआउट और/या मास्टर स्लाइड से प्राप्त आकृति जिससे वर्तमान आकृति विरासत में मिली है)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | आकृति थंबनेल लौटाता है। डिफ़ॉल्ट रूप से [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) आकृति थंबनेल बाउंड्स टाइप उपयोग किया जाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | आकृति थंबनेल लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचें कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीनी ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास के कॉपी कंस्ट्रक्ट को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास के कॉपी कंस्ट्रक्ट को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr से रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को कम करता है। |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | परिभाषित करता है कि यह आकृति प्लेसहोल्डर नहीं है। |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | आकृति से जुड़े वैकल्पिक टेक्स्ट को सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | आकृति से जुड़े वैकल्पिक टेक्स्ट का शीर्षक सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | प्रॉपर्टी निर्धारित करती है कि एक आकृति ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगी। लिखें [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)। |
| virtual void [set_DisplayBlanksAs](./set_displayblanksas/)([DisplayBlanksAsType](../displayblanksastype/)) | चार्ट पर खाली कोशिकाओं को प्लॉट करने का तरीका सेट करता है। लिखें [DisplayBlanksAsType](../displayblanksastype/)। |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | आकृति फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../../aspose.slides/ishapeframe/)। |
| virtual void [set_HasDataTable](./set_hasdatatable/)(**bool**) | निर्धारित करता है कि क्या चार्ट में डेटा टेबल है। लिखें **bool**। |
| virtual void [set_HasLegend](./set_haslegend/)(**bool**) | निर्धारित करता है कि क्या चार्ट में लेजेंड है। लिखें **bool**। |
| virtual void [set_HasRoundedCorners](./set_hasroundedcorners/)(**bool**) | निर्दिष्ट करता है कि चार्ट एरिया में गोल कोने हों। लिखें **bool**। |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | निर्धारित करता है कि क्या चार्ट में दृश्यमान शीर्षक है। लिखें **bool**। |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | आकृति की ऊँचाई पॉइंट्स में सेट करता है। लिखें **float**। |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | निर्धारित करता है कि क्या आकृति छुपी हुई है। लिखें **bool**। |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | माउस क्लिक के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../../aspose.slides/ihyperlink/)। |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | माउस ओवर के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../../aspose.slides/ihyperlink/)। |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | सेट करता है 'Mark as decorative' विकल्प पढ़ें/लिखें **bool**। |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | आकृति का नाम सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_PlotVisibleCellsOnly](./set_plotvisiblecellsonly/)(**bool**) | निर्धारित करता है कि केवल दृश्यमान कोशिकाओं को प्लॉट किया जाए। दृश्यमान और छिपी कोशिकाओं दोनों को प्लॉट करने के लिए False सेट करें। लिखें **bool**। |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | कच्चे आकृति फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../../aspose.slides/ishapeframe/)। |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | निर्दिष्ट आकृति को z-अक्ष के चारों ओर घुमाने की डिग्री संख्या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विपरीत दिशा में। लिखें **float**। |
| virtual void [set_ShowDataLabelsOverMaximum](./set_showdatalabelsovermaximum/)(**bool**) | निर्धारित करता है कि चार्ट के अधिकतम पर डेटा लेबल दिखाए जाएँ। लिखें **bool**। |
| virtual void [set_Style](./set_style/)([StyleType](../styletype/)) | चार्ट शैली सेट करता है। लिखें [StyleType](../styletype/)। |
| virtual void [set_Type](./set_type/)([ChartType](../charttype/)) | चार्ट प्रकार सेट करता है। लिखें [ChartType](../charttype/)। |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | आकृति की चौड़ाई पॉइंट्स में सेट करता है। लिखें **float**। |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | आकृति के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट्स में सेट करता है। लिखें **float**। |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | आकृति के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट्स में सेट करता है। लिखें **float**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्गुमेंट को वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनर में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीनी ऑब्जेक्ट का उपयोग करें। |
| virtual void [ValidateChartLayout](./validatechartlayout/)() | चार्ट तत्वों के वास्तविक मानों की गणना करता है। वास्तविक मान उन तत्वों की स्थिति शामिल करते हैं जो [IActualLayout](../iactuallayout/) इंटरफ़ेस लागू करते हैं ([IActualLayout::get_ActualX](../iactuallayout/get_actualx/), [IActualLayout::get_ActualY](../iactuallayout/get_actualy/), [IActualLayout::get_ActualWidth](../iactuallayout/get_actualwidth/), [IActualLayout::get_ActualHeight](../iactuallayout/get_actualheight/)) और वास्तविक एक्सिस मान ([IAxis::get_ActualMaxValue](../iaxis/get_actualmaxvalue/), [IAxis::get_ActualMinValue](../iaxis/get_actualminvalue/), [IAxis::get_ActualMajorUnit](../iaxis/get_actualmajorunit/), [IAxis::get_ActualMinorUnit](../iaxis/get_actualminorunit/), [IAxis::get_ActualMajorUnitScale](../iaxis/get_actualmajorunitscale/), [IAxis::get_ActualMinorUnitScale](../iaxis/get_actualminorunitscale/))। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीेक रेफ़रेंस काउंट बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीेक रेफ़रेंस काउंट घटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../../aspose.slides/shape/) की सामग्री को SVG फ़ाइल के रूप में सेव करता है। |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../../aspose.slides/shape/) की सामग्री को SVG फ़ाइल के रूप में सेव करता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## संबंधित देखें

* क्लास [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* क्लास [IFormattedTextContainer](../iformattedtextcontainer/)
* क्लास [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable/)
* नामस्थान [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)